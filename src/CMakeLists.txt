
set(SOURCES
    compile.c
    extra.c
    gencode.c
    lex.c
    optimize.c
    parse.c
    parseext.c
    parselib.c
)

set(HEADERS
    extra.h
    gencode.h
    lex.h
    noconfig.h
    opcodes.h
    opextra.h
    oplib.h
    parseext.h
    parse.h
    parselib.h
    resource.h
    sfalltok.h
    tokens.h
)

add_executable(sslc ${SOURCES} ${HEADERS})

set_target_properties(sslc PROPERTIES COMPILE_FLAGS "-m32" LINK_FLAGS "-m32")