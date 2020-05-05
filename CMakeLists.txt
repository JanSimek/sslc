cmake_minimum_required(VERSION 3.5)

project(sslc LANGUAGES C)

#set(CMAKE_CXX_STANDARD 11)
#set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(sslc
    compile.c
    extra.c
    extra.h
    gencode.c
    gencode.h
    lex.c
    lex.h

    # MCPP
    system.h
    internal.h
    mcpp_directive.c
    mcpp_eval.c
    mcpp_expand.c
    mcpp_main.c
    mcpp_support.c
    mcpp_system.c

    noconfig.h
    opcodes.h
    opextra.h
    oplib.h
    optimize.c
    parse.c
    parseext.c
    parseext.h
    parse.h
    parselib.c
    parselib.h
    resource.h
    sfalltok.h
    tokens.h
)

set_target_properties(sslc PROPERTIES COMPILE_FLAGS "-m32" LINK_FLAGS "-m32")
