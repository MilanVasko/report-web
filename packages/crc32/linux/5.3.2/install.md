# Report for 'install lua 5.3.2 crc32'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- crc32 1.1-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **crc32 1.1-1**
    - **remote:** git://github.com/LuaDist-testing/crc32.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1

## 4. Installing packages


### lua 5.3.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1/lua-5.3.2-1.rockspec'
- Package 'lua 5.3.2-1': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/lib;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/share/luadist2/manifest-file'

### crc32 1.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1/crc32-1.1-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/lib;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- **Error:** Error building package 'crc32 1.1-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1-build'
stdout:
Scanning dependencies of target crc32
[ 33%] Building C object CMakeFiles/crc32.dir/crc32.c.o
[ 66%] Building C object CMakeFiles/crc32.dir/wrap.c.o

stderr:
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1/wrap.c:4:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lua.h:385:50: error: expected declaration specifiers or ‘...’ before ‘(’ token
 #define lua_pushunsigned(L,n) lua_pushinteger(L, (lua_Integer)(n))
                                                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1/wrap.c:113:13: note: in expansion of macro ‘lua_pushunsigned’
 static void lua_pushunsigned (lua_State *L, lua_Unsigned u) {
             ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1/wrap.c:5:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lauxlib.h:239:48: error: expected ‘)’ before ‘luaL_checkinteger’
 #define luaL_checkunsigned(L,a) ((lua_Unsigned)luaL_checkinteger(L,a))
                                                ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/crc32 1.1-1/wrap.c:121:21: note: in expansion of macro ‘luaL_checkunsigned’
 static lua_Unsigned luaL_checkunsigned (lua_State *L, int arg) {
                     ^
make[2]: *** [CMakeFiles/crc32.dir/wrap.c.o] Error 1
make[1]: *** [CMakeFiles/crc32.dir/all] Error 2
make: *** [all] Error 2

