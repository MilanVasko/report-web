# Report for 'install lua 5.3.2 lrexlib-oniguruma'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- lrexlib-oniguruma 2.9.0-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **lrexlib-oniguruma 2.9.0-1**
    - **remote:** git://github.com/LuaDist-testing/lrexlib-oniguruma.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1

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

### lrexlib-oniguruma 2.9.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1/lrexlib-oniguruma-2.9.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1-build'
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
- **Error:** Error building package 'lrexlib-oniguruma 2.9.0-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1-build'
stdout:
Scanning dependencies of target rex_onig
[ 25%] Building C object CMakeFiles/rex_onig.dir/src/common.c.o
[ 50%] Building C object CMakeFiles/rex_onig.dir/src/oniguruma/lonig.c.o

stderr:
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lua.h:16:0,
                 from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1/src/common.c:7:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/luaconf.h:244:0: warning: "LUA_COMPAT_5_2" redefined [enabled by default]
 #define LUA_COMPAT_5_2
 ^
<command-line>:0:0: note: this is the location of the previous definition
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1/src/common.c:9:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1/src/common.h:10:0: warning: "lua_objlen" redefined [enabled by default]
 # define lua_objlen lua_rawlen
 ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lua.h:16:0,
                 from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1/src/common.c:7:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/luaconf.h:327:0: note: this is the location of the previous definition
 #define lua_objlen(L,i)  lua_rawlen(L, (i))
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lrexlib-oniguruma 2.9.0-1/src/oniguruma/lonig.c:8:23: fatal error: oniguruma.h: No such file or directory
 #include <oniguruma.h>
                       ^
compilation terminated.
make[2]: *** [CMakeFiles/rex_onig.dir/src/oniguruma/lonig.c.o] Error 1
make[1]: *** [CMakeFiles/rex_onig.dir/all] Error 2
make: *** [all] Error 2

