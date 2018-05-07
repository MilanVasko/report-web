# Report for 'install lua 5.2.4-1 cdb'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- cdb 1.0-1

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **cdb 1.0-1**
    - **remote:** git://github.com/LuaDist-testing/cdb.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1

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

### cdb 1.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/cdb-1.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1-build'
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
- **Error:** Error building package 'cdb 1.0-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1-build'
stdout:
Scanning dependencies of target cdb
[ 33%] Building C object CMakeFiles/cdb.dir/src/cdb.c.o
[ 66%] Building C object CMakeFiles/cdb.dir/src/lcdb.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:108:24: error: array type has incomplete element type
 static struct luaL_reg lcdb_meta_lib[] = {
                        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:118:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg lcdb_lib[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:119:3: warning: braces around scalar initializer [enabled by default]
   { "open", lcdb_open }
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:119:3: warning: (near initialization for ‘lcdb_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:119:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:119:3: warning: (near initialization for ‘lcdb_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:119:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:119:3: error: (near initialization for ‘lcdb_lib[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:119:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:119:3: warning: (near initialization for ‘lcdb_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:120:2: warning: braces around scalar initializer [enabled by default]
  ,{ 0, 0 }
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:120:2: warning: (near initialization for ‘lcdb_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:120:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:120:2: warning: (near initialization for ‘lcdb_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c: In function ‘luaopen_cdb’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:125:2: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
  luaL_register(L, 0, lcdb_meta_lib);
  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:14:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lauxlib.h:202:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:130:2: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
  luaL_register( L, "cdb", lcdb_lib );
  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/cdb 1.0-1/src/lcdb.c:14:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lauxlib.h:202:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
make[2]: *** [CMakeFiles/cdb.dir/src/lcdb.c.o] Error 1
make[1]: *** [CMakeFiles/cdb.dir/all] Error 2
make: *** [all] Error 2

