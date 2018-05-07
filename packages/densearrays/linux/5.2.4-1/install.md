# Report for 'install lua 5.2.4-1 densearrays'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- densearrays 1.0-2

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **densearrays 1.0-2**
    - **remote:** git://github.com/LuaDist-testing/densearrays.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2

## 4. Installing packages


### lua 5.2.4-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1/lua-5.2.4-1.rockspec'
- Package 'lua 5.2.4-1': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/lib;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/share/luadist2/manifest-file'

### densearrays 1.0-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/densearrays-1.0-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/lib;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- **Error:** Error building package 'densearrays 1.0-2': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2-build'
stdout:
Scanning dependencies of target array
[ 50%] Building C object CMakeFiles/array.dir/array.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:489:1: error: unknown type name ‘luaL_reg’
 static luaL_reg functions[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:490:2: warning: braces around scalar initializer [enabled by default]
  {"array", l_array},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:490:2: warning: (near initialization for ‘functions[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:490:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:490:2: warning: (near initialization for ‘functions[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:490:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:490:2: error: (near initialization for ‘functions[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:490:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:490:2: warning: (near initialization for ‘functions[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:492:2: warning: braces around scalar initializer [enabled by default]
  {NULL, NULL}
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:492:2: warning: (near initialization for ‘functions[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:492:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:492:2: warning: (near initialization for ‘functions[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:492:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:492:2: warning: (near initialization for ‘functions[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:495:1: error: unknown type name ‘luaL_reg’
 static luaL_reg methods[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:496:2: warning: braces around scalar initializer [enabled by default]
  {"set", lm_array_set},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:496:2: warning: (near initialization for ‘methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:496:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:496:2: warning: (near initialization for ‘methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:496:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:496:2: error: (near initialization for ‘methods[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:496:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:496:2: warning: (near initialization for ‘methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:497:2: warning: braces around scalar initializer [enabled by default]
  {"get", lm_array_get},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:497:2: warning: (near initialization for ‘methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:497:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:497:2: warning: (near initialization for ‘methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:497:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:497:2: error: (near initialization for ‘methods[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:497:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:497:2: warning: (near initialization for ‘methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:499:2: warning: braces around scalar initializer [enabled by default]
  {"clear", lm_array_clear},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:499:2: warning: (near initialization for ‘methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:499:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:499:2: warning: (near initialization for ‘methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:499:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:499:2: error: (near initialization for ‘methods[2]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:499:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:499:2: warning: (near initialization for ‘methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:501:2: warning: braces around scalar initializer [enabled by default]
  {"copy", lm_array_copy},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:501:2: warning: (near initialization for ‘methods[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:501:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:501:2: warning: (near initialization for ‘methods[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:501:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:501:2: error: (near initialization for ‘methods[3]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:501:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:501:2: warning: (near initialization for ‘methods[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:503:2: warning: braces around scalar initializer [enabled by default]
  {"bnot", lm_array_bnot},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:503:2: warning: (near initialization for ‘methods[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:503:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:503:2: warning: (near initialization for ‘methods[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:503:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:503:2: error: (near initialization for ‘methods[4]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:503:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:503:2: warning: (near initialization for ‘methods[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:504:2: warning: braces around scalar initializer [enabled by default]
  {"bor", lm_array_bor},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:504:2: warning: (near initialization for ‘methods[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:504:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:504:2: warning: (near initialization for ‘methods[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:504:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:504:2: error: (near initialization for ‘methods[5]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:504:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:504:2: warning: (near initialization for ‘methods[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:505:2: warning: braces around scalar initializer [enabled by default]
  {"band", lm_array_band},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:505:2: warning: (near initialization for ‘methods[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:505:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:505:2: warning: (near initialization for ‘methods[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:505:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:505:2: error: (near initialization for ‘methods[6]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:505:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:505:2: warning: (near initialization for ‘methods[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:506:2: warning: braces around scalar initializer [enabled by default]
  {"bxor", lm_array_bxor},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:506:2: warning: (near initialization for ‘methods[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:506:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:506:2: warning: (near initialization for ‘methods[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:506:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:506:2: error: (near initialization for ‘methods[7]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:506:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:506:2: warning: (near initialization for ‘methods[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:508:2: warning: braces around scalar initializer [enabled by default]
  {"add", lm_array_add},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:508:2: warning: (near initialization for ‘methods[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:508:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:508:2: warning: (near initialization for ‘methods[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:508:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:508:2: error: (near initialization for ‘methods[8]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:508:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:508:2: warning: (near initialization for ‘methods[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:509:2: warning: braces around scalar initializer [enabled by default]
  {"multiply", lm_array_multiply},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:509:2: warning: (near initialization for ‘methods[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:509:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:509:2: warning: (near initialization for ‘methods[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:509:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:509:2: error: (near initialization for ‘methods[9]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:509:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:509:2: warning: (near initialization for ‘methods[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:510:2: warning: braces around scalar initializer [enabled by default]
  {"negate", lm_array_negate},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:510:2: warning: (near initialization for ‘methods[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:510:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:510:2: warning: (near initialization for ‘methods[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:510:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:510:2: error: (near initialization for ‘methods[10]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:510:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:510:2: warning: (near initialization for ‘methods[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:512:2: warning: braces around scalar initializer [enabled by default]
  {"shiftcopy", lm_array_shiftcopy},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:512:2: warning: (near initialization for ‘methods[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:512:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:512:2: warning: (near initialization for ‘methods[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:512:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:512:2: error: (near initialization for ‘methods[11]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:512:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:512:2: warning: (near initialization for ‘methods[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:514:2: warning: braces around scalar initializer [enabled by default]
  {"getpointer", lm_array_getpointer},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:514:2: warning: (near initialization for ‘methods[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:514:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:514:2: warning: (near initialization for ‘methods[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:514:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:514:2: error: (near initialization for ‘methods[12]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:514:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:514:2: warning: (near initialization for ‘methods[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:516:2: warning: braces around scalar initializer [enabled by default]
  {NULL, NULL}
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:516:2: warning: (near initialization for ‘methods[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:516:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:516:2: warning: (near initialization for ‘methods[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:516:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:516:2: warning: (near initialization for ‘methods[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:519:1: error: unknown type name ‘luaL_reg’
 static luaL_reg metamethods[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:520:2: warning: braces around scalar initializer [enabled by default]
  {"__gc", lmm_array_gc},
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:520:2: warning: (near initialization for ‘metamethods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:520:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:520:2: warning: (near initialization for ‘metamethods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:520:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:520:2: error: (near initialization for ‘metamethods[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:520:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:520:2: warning: (near initialization for ‘metamethods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:522:2: warning: braces around scalar initializer [enabled by default]
  {NULL, NULL}
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:522:2: warning: (near initialization for ‘metamethods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:522:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:522:2: warning: (near initialization for ‘metamethods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:522:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:522:2: warning: (near initialization for ‘metamethods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c: In function ‘luaopen_array’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:530:26: error: request for member ‘name’ in something not a structure or union
  for (i=0; metamethods[i].name; i++)
                          ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:1:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:532:38: error: request for member ‘func’ in something not a structure or union
   lua_pushcfunction(L, metamethods[i].func);
                                      ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lua.h:329:53: note: in definition of macro ‘lua_pushcfunction’
 #define lua_pushcfunction(L,f) lua_pushcclosure(L, (f), 0)
                                                     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:532:3: warning: passing argument 2 of ‘lua_pushcclosure’ from incompatible pointer type [enabled by default]
   lua_pushcfunction(L, metamethods[i].func);
   ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:1:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lua.h:214:16: note: expected ‘lua_CFunction’ but argument is of type ‘int *’
 LUA_API void  (lua_pushcclosure) (lua_State *L, lua_CFunction fn, int n);
                ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:533:37: error: request for member ‘name’ in something not a structure or union
   lua_setfield(L, -2, metamethods[i].name);
                                     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:533:3: warning: passing argument 3 of ‘lua_setfield’ from incompatible pointer type [enabled by default]
   lua_setfield(L, -2, metamethods[i].name);
   ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:1:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lua.h:240:16: note: expected ‘const char *’ but argument is of type ‘int *’
 LUA_API void  (lua_setfield) (lua_State *L, int idx, const char *k);
                ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:537:22: error: request for member ‘name’ in something not a structure or union
  for (i=0; methods[i].name; i++)
                      ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:1:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:539:34: error: request for member ‘func’ in something not a structure or union
   lua_pushcfunction(L, methods[i].func);
                                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lua.h:329:53: note: in definition of macro ‘lua_pushcfunction’
 #define lua_pushcfunction(L,f) lua_pushcclosure(L, (f), 0)
                                                     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:539:3: warning: passing argument 2 of ‘lua_pushcclosure’ from incompatible pointer type [enabled by default]
   lua_pushcfunction(L, methods[i].func);
   ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:1:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lua.h:214:16: note: expected ‘lua_CFunction’ but argument is of type ‘int *’
 LUA_API void  (lua_pushcclosure) (lua_State *L, lua_CFunction fn, int n);
                ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:540:33: error: request for member ‘name’ in something not a structure or union
   lua_setfield(L, -2, methods[i].name);
                                 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:540:3: warning: passing argument 3 of ‘lua_setfield’ from incompatible pointer type [enabled by default]
   lua_setfield(L, -2, methods[i].name);
   ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:1:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lua.h:240:16: note: expected ‘const char *’ but argument is of type ‘int *’
 LUA_API void  (lua_setfield) (lua_State *L, int idx, const char *k);
                ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:546:2: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
  luaL_register(L, "array", functions);
  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/densearrays 1.0-2/array.c:2:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lauxlib.h:202:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
make[2]: *** [CMakeFiles/array.dir/array.c.o] Error 1
make[1]: *** [CMakeFiles/array.dir/all] Error 2
make: *** [all] Error 2

