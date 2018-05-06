# Report for 'install lua 5.2.4-1 escher'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- luafilesystem 1.6.3-2
- rapidjson 0.4.5-1
- luacrypto 0.3.2-2
- date 2.1.1-1
- escher 0.2-17

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **luafilesystem 1.6.3-2**
    - **remote:** git://github.com/LuaDist-testing/luafilesystem.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luafilesystem 1.6.3-2
- **rapidjson 0.4.5-1**
    - **remote:** git://github.com/LuaDist-testing/rapidjson.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/rapidjson 0.4.5-1
- **luacrypto 0.3.2-2**
    - **remote:** git://github.com/LuaDist-testing/luacrypto.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luacrypto 0.3.2-2
- **date 2.1.1-1**
    - **remote:** git://github.com/LuaDist-testing/date.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/date 2.1.1-1
- **escher 0.2-17**
    - **remote:** git://github.com/LuaDist-testing/escher.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/escher 0.2-17

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

### luafilesystem 1.6.3-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luafilesystem 1.6.3-2/luafilesystem-1.6.3-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luafilesystem 1.6.3-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luafilesystem 1.6.3-2-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luafilesystem 1.6.3-2-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luafilesystem 1.6.3-2'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luafilesystem 1.6.3-2-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/share/luadist2/manifest-file'

### rapidjson 0.4.5-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/rapidjson 0.4.5-1/rapidjson-0.4.5-1.rockspec'
- Package 'rapidjson 0.4.5-1': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/rapidjson 0.4.5-1-build'
- **CMake Variables:**
    - `BUILD_SHARED_LIBS` = ON
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
    - `LUA_INCLUDE_DIR` = $(LUA_INCDIR)
    - `LUA_RAPIDJSON_VERSION` = 0.4.5
- **Error:** Error building package 'rapidjson 0.4.5-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/rapidjson 0.4.5-1-build'
stdout:
Scanning dependencies of target rapidjson
[ 50%] Building CXX object CMakeFiles/rapidjson.dir/src/rapidjson.cpp.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/rapidjson 0.4.5-1/src/rapidjson.cpp:8:19: fatal error: lua.hpp: No such file or directory
 #include "lua.hpp"
                   ^
compilation terminated.
make[2]: *** [CMakeFiles/rapidjson.dir/src/rapidjson.cpp.o] Error 1
make[1]: *** [CMakeFiles/rapidjson.dir/all] Error 2
make: *** [all] Error 2

