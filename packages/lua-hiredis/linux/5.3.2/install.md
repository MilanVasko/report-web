# Report for 'install lua 5.3.2 lua-hiredis'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- lua-hiredis 0.2.1-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **lua-hiredis 0.2.1-1**
    - **remote:** git://github.com/LuaDist-testing/lua-hiredis.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1

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

### lua-hiredis 0.2.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/lua-hiredis-0.2.1-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1-build'
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
- **Error:** Error building package 'lua-hiredis 0.2.1-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1-build'
stdout:
Scanning dependencies of target hiredis
[ 14%] Building C object CMakeFiles/hiredis.dir/src/lua-hiredis.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:80:30: error: array type has incomplete element type
 static const struct luaL_reg CONST_MT[] =
                              ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:139:30: error: array type has incomplete element type
 static const struct luaL_reg STATUS_MT[] =
                              ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:421:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg M[] =
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:423:3: warning: braces around scalar initializer [enabled by default]
   { "command", lconn_command },
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:423:3: warning: (near initialization for ‘M[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:423:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:423:3: warning: (near initialization for ‘M[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:423:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:423:3: error: (near initialization for ‘M[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:423:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:423:3: warning: (near initialization for ‘M[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:424:3: warning: braces around scalar initializer [enabled by default]
   { "append_command", lconn_append_command },
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:424:3: warning: (near initialization for ‘M[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:424:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:424:3: warning: (near initialization for ‘M[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:424:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:424:3: error: (near initialization for ‘M[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:424:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:424:3: warning: (near initialization for ‘M[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:425:3: warning: braces around scalar initializer [enabled by default]
   { "get_reply", lconn_get_reply },
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:425:3: warning: (near initialization for ‘M[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:425:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:425:3: warning: (near initialization for ‘M[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:425:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:425:3: error: (near initialization for ‘M[2]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:425:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:425:3: warning: (near initialization for ‘M[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:427:3: warning: braces around scalar initializer [enabled by default]
   { "close", lconn_close },
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:427:3: warning: (near initialization for ‘M[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:427:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:427:3: warning: (near initialization for ‘M[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:427:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:427:3: error: (near initialization for ‘M[3]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:427:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:427:3: warning: (near initialization for ‘M[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:428:3: warning: braces around scalar initializer [enabled by default]
   { "__gc", lconn_gc },
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:428:3: warning: (near initialization for ‘M[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:428:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:428:3: warning: (near initialization for ‘M[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:428:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:428:3: error: (near initialization for ‘M[4]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:428:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:428:3: warning: (near initialization for ‘M[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:429:3: warning: braces around scalar initializer [enabled by default]
   { "__tostring", lconn_tostring },
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:429:3: warning: (near initialization for ‘M[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:429:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:429:3: warning: (near initialization for ‘M[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:429:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:429:3: error: (near initialization for ‘M[5]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:429:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:429:3: warning: (near initialization for ‘M[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:431:3: warning: braces around scalar initializer [enabled by default]
   { NULL, NULL }
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:431:3: warning: (near initialization for ‘M[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:431:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:431:3: warning: (near initialization for ‘M[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:431:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:431:3: warning: (near initialization for ‘M[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c: In function ‘lhiredis_connect’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:475:5: warning: passing argument 2 of ‘setfuncs’ from incompatible pointer type [enabled by default]
     setfuncs(L, M, 1);
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:54:13: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 static void setfuncs (lua_State *L, const luaL_Reg *l, int nup) {
             ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c: At top level:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:570:30: error: array type has incomplete element type
 static const struct luaL_reg E[] = /* Empty */
                              ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:576:30: error: array type has incomplete element type
 static const struct luaL_reg R[] =
                              ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c: In function ‘luaopen_hiredis’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:593:3: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
   luaL_register(L, "hiredis", E);
   ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:11:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lauxlib.h:199:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:623:5: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
     luaL_register(L, NULL, STATUS_MT);
     ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:11:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lauxlib.h:199:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:642:3: warning: passing argument 2 of ‘setfuncs’ from incompatible pointer type [enabled by default]
   setfuncs(L, R, 1);
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-hiredis 0.2.1-1/src/lua-hiredis.c:54:13: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 static void setfuncs (lua_State *L, const luaL_Reg *l, int nup) {
             ^
make[2]: *** [CMakeFiles/hiredis.dir/src/lua-hiredis.c.o] Error 1
make[1]: *** [CMakeFiles/hiredis.dir/all] Error 2
make: *** [all] Error 2

