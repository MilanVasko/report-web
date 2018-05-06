# Report for 'install lua 5.1.5-1 luastepper'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- luastepper 1.16.06.17-1

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1
- **luastepper 1.16.06.17-1**
    - **remote:** git://github.com/LuaDist-testing/luastepper.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1

## 4. Installing packages


### lua 5.1.5-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1/lua-5.1.5-1.rockspec'
- Package 'lua 5.1.5-1': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/lib;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### luastepper 1.16.06.17-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/luastepper-1.16.06.17-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/lib;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/bin
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
- **Error:** Error building package 'luastepper 1.16.06.17-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1-build'
stdout:
Scanning dependencies of target LuaStepper
[ 50%] Building C object CMakeFiles/LuaStepper.dir/LuaStepper.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c: In function ‘callParentFunc’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:137:14: error: ‘LUA_OK’ undeclared (first use in this function)
         case LUA_OK:
              ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:137:14: note: each undeclared identifier is reported only once for each function it appears in
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:155:14: error: ‘LUA_ERRGCMM’ undeclared (first use in this function)
         case LUA_ERRGCMM:
              ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c: In function ‘addTask’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:325:50: error: ‘luaopen_coroutine’ undeclared (first use in this function)
     luaL_requiref(taskq[i].luaVM, LUA_COLIBNAME, luaopen_coroutine, 1);          // Coroutine library
                                                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:330:35: error: ‘LUA_BITLIBNAME’ undeclared (first use in this function)
     luaL_requiref(taskq[i].luaVM, LUA_BITLIBNAME, luaopen_bit32, 1);             // Bit library
                                   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:330:51: error: ‘luaopen_bit32’ undeclared (first use in this function)
     luaL_requiref(taskq[i].luaVM, LUA_BITLIBNAME, luaopen_bit32, 1);             // Bit library
                                                   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:546:14: error: ‘LUA_OK’ undeclared (first use in this function)
         case LUA_OK:
              ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:558:22: error: ‘LUA_ERRGCMM’ undeclared (first use in this function)
                 case LUA_ERRGCMM:
                      ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c: In function ‘setTaskData’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:1018:57: error: ‘LUA_RIDX_GLOBALS’ undeclared (first use in this function)
     lua_rawgeti(taskq[tIndex].luaVM, LUA_REGISTRYINDEX, LUA_RIDX_GLOBALS);
                                                         ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c: In function ‘taskStatus’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:1212:9: error: ‘LUA_OK’ undeclared (first use in this function)
    case LUA_OK:
         ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c: In function ‘runLoop’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:1279:11: error: ‘LUA_OK’ undeclared (first use in this function)
      case LUA_OK:
           ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:1294:7: warning: passing argument 2 of ‘lua_resume’ makes integer from pointer without a cast [enabled by default]
       switch(lua_resume(taskq[i].thread,NULL,0))
       ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:24:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/include/lua.h:214:15: note: expected ‘int’ but argument is of type ‘void *’
 LUA_API int  (lua_resume) (lua_State *L, int narg);
               ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:1294:7: error: too many arguments to function ‘lua_resume’
       switch(lua_resume(taskq[i].thread,NULL,0))
       ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luastepper 1.16.06.17-1/LuaStepper.c:24:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/include/lua.h:214:15: note: declared here
 LUA_API int  (lua_resume) (lua_State *L, int narg);
               ^
make[2]: *** [CMakeFiles/LuaStepper.dir/LuaStepper.c.o] Error 1
make[1]: *** [CMakeFiles/LuaStepper.dir/all] Error 2
make: *** [all] Error 2

