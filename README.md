# sslc

Script compiler/parser for Star-Trek Scripting Language used in Fallout 2.

## Goals

These are the project goals ranked by priority:

1. cross-platform support - make it run on Linux and OS X in addition to Windows
2. port from C to C++
3. replace MCPP with something simpler, e.g. [tiny_preproc](https://github.com/smiley3/tiny_preproc), [tcpp](https://github.com/bnoazx005/tcpp), [simplecpp](https://github.com/danmar/simplecpp) or [vrm_pp](https://github.com/SuperV1234/vrm_pp)
4. split into a simple compiler executable and library target
5. add test framework, e.g. [Catch2](https://github.com/catchorg/Catch2) ([example](https://github.com/bnoazx005/tcpp/blob/master/tests/coreTests.cpp)) or Google Test
6. remove all Sfall additions and focus on the vanilla engine and [Falltergeist](https://github.com/falltergeist/falltergeist)
