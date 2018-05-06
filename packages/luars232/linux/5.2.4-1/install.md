# Report for 'install lua 5.2.4-1 luars232'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- luars232 1.0.3-1

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **luars232 1.0.3-1**
    - **remote:** git://github.com/LuaDist-testing/luars232.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1

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

### luars232 1.0.3-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/luars232-1.0.3-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1-build'
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
- **Error:** Error building package 'luars232 1.0.3-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1-build'
stdout:
Scanning dependencies of target luars232
[ 25%] Building C object CMakeFiles/luars232.dir/src/rs232.c.o
[ 50%] Building C object CMakeFiles/luars232.dir/src/rs232_posix.c.o
[ 75%] Building C object CMakeFiles/luars232.dir/bindings/lua/luars232.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:386:1: error: unknown type name ‘luaL_reg’
 static luaL_reg port_methods[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:387:2: warning: braces around scalar initializer [enabled by default]
  { "__tostring", lua_port_tostring },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:387:2: warning: (near initialization for ‘port_methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:387:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:387:2: warning: (near initialization for ‘port_methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:387:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:387:2: error: (near initialization for ‘port_methods[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:387:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:387:2: warning: (near initialization for ‘port_methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:388:2: warning: braces around scalar initializer [enabled by default]
  { "__gc", lua_port_close },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:388:2: warning: (near initialization for ‘port_methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:388:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:388:2: warning: (near initialization for ‘port_methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:388:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:388:2: error: (near initialization for ‘port_methods[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:388:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:388:2: warning: (near initialization for ‘port_methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:389:2: warning: braces around scalar initializer [enabled by default]
  { "read", lua_port_read },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:389:2: warning: (near initialization for ‘port_methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:389:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:389:2: warning: (near initialization for ‘port_methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:389:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:389:2: error: (near initialization for ‘port_methods[2]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:389:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:389:2: warning: (near initialization for ‘port_methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:390:2: warning: braces around scalar initializer [enabled by default]
  { "write", lua_port_write },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:390:2: warning: (near initialization for ‘port_methods[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:390:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:390:2: warning: (near initialization for ‘port_methods[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:390:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:390:2: error: (near initialization for ‘port_methods[3]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:390:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:390:2: warning: (near initialization for ‘port_methods[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:391:2: warning: braces around scalar initializer [enabled by default]
  { "close", lua_port_close },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:391:2: warning: (near initialization for ‘port_methods[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:391:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:391:2: warning: (near initialization for ‘port_methods[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:391:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:391:2: error: (near initialization for ‘port_methods[4]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:391:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:391:2: warning: (near initialization for ‘port_methods[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:392:2: warning: braces around scalar initializer [enabled by default]
  { "flush", lua_port_flush },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:392:2: warning: (near initialization for ‘port_methods[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:392:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:392:2: warning: (near initialization for ‘port_methods[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:392:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:392:2: error: (near initialization for ‘port_methods[5]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:392:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:392:2: warning: (near initialization for ‘port_methods[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:393:2: warning: braces around scalar initializer [enabled by default]
  { "device", lua_port_device },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:393:2: warning: (near initialization for ‘port_methods[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:393:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:393:2: warning: (near initialization for ‘port_methods[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:393:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:393:2: error: (near initialization for ‘port_methods[6]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:393:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:393:2: warning: (near initialization for ‘port_methods[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:394:2: warning: braces around scalar initializer [enabled by default]
  { "fd", lua_port_fd },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:394:2: warning: (near initialization for ‘port_methods[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:394:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:394:2: warning: (near initialization for ‘port_methods[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:394:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:394:2: error: (near initialization for ‘port_methods[7]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:394:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:394:2: warning: (near initialization for ‘port_methods[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:396:2: warning: braces around scalar initializer [enabled by default]
  { "baud_rate", lua_port_get_baud },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:396:2: warning: (near initialization for ‘port_methods[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:396:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:396:2: warning: (near initialization for ‘port_methods[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:396:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:396:2: error: (near initialization for ‘port_methods[8]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:396:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:396:2: warning: (near initialization for ‘port_methods[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:397:2: warning: braces around scalar initializer [enabled by default]
  { "baud_rate_tostring", lua_port_get_strbaud },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:397:2: warning: (near initialization for ‘port_methods[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:397:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:397:2: warning: (near initialization for ‘port_methods[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:397:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:397:2: error: (near initialization for ‘port_methods[9]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:397:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:397:2: warning: (near initialization for ‘port_methods[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:398:2: warning: braces around scalar initializer [enabled by default]
  { "set_baud_rate", lua_port_set_baud },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:398:2: warning: (near initialization for ‘port_methods[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:398:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:398:2: warning: (near initialization for ‘port_methods[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:398:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:398:2: error: (near initialization for ‘port_methods[10]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:398:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:398:2: warning: (near initialization for ‘port_methods[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:400:2: warning: braces around scalar initializer [enabled by default]
  { "data_bits", lua_port_get_data },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:400:2: warning: (near initialization for ‘port_methods[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:400:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:400:2: warning: (near initialization for ‘port_methods[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:400:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:400:2: error: (near initialization for ‘port_methods[11]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:400:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:400:2: warning: (near initialization for ‘port_methods[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:401:2: warning: braces around scalar initializer [enabled by default]
  { "data_bits_tostring", lua_port_get_strdata },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:401:2: warning: (near initialization for ‘port_methods[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:401:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:401:2: warning: (near initialization for ‘port_methods[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:401:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:401:2: error: (near initialization for ‘port_methods[12]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:401:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:401:2: warning: (near initialization for ‘port_methods[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:402:2: warning: braces around scalar initializer [enabled by default]
  { "set_data_bits", lua_port_set_data },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:402:2: warning: (near initialization for ‘port_methods[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:402:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:402:2: warning: (near initialization for ‘port_methods[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:402:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:402:2: error: (near initialization for ‘port_methods[13]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:402:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:402:2: warning: (near initialization for ‘port_methods[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:404:2: warning: braces around scalar initializer [enabled by default]
  { "stop_bits", lua_port_get_stop },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:404:2: warning: (near initialization for ‘port_methods[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:404:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:404:2: warning: (near initialization for ‘port_methods[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:404:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:404:2: error: (near initialization for ‘port_methods[14]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:404:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:404:2: warning: (near initialization for ‘port_methods[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:405:2: warning: braces around scalar initializer [enabled by default]
  { "stop_bits_tostring", lua_port_get_strstop },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:405:2: warning: (near initialization for ‘port_methods[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:405:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:405:2: warning: (near initialization for ‘port_methods[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:405:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:405:2: error: (near initialization for ‘port_methods[15]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:405:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:405:2: warning: (near initialization for ‘port_methods[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:406:2: warning: braces around scalar initializer [enabled by default]
  { "set_stop_bits", lua_port_set_stop },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:406:2: warning: (near initialization for ‘port_methods[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:406:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:406:2: warning: (near initialization for ‘port_methods[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:406:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:406:2: error: (near initialization for ‘port_methods[16]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:406:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:406:2: warning: (near initialization for ‘port_methods[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:408:2: warning: braces around scalar initializer [enabled by default]
  { "parity", lua_port_get_parity },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:408:2: warning: (near initialization for ‘port_methods[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:408:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:408:2: warning: (near initialization for ‘port_methods[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:408:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:408:2: error: (near initialization for ‘port_methods[17]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:408:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:408:2: warning: (near initialization for ‘port_methods[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:409:2: warning: braces around scalar initializer [enabled by default]
  { "parity_tostring", lua_port_get_strparity },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:409:2: warning: (near initialization for ‘port_methods[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:409:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:409:2: warning: (near initialization for ‘port_methods[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:409:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:409:2: error: (near initialization for ‘port_methods[18]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:409:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:409:2: warning: (near initialization for ‘port_methods[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:410:2: warning: braces around scalar initializer [enabled by default]
  { "set_parity", lua_port_set_parity },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:410:2: warning: (near initialization for ‘port_methods[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:410:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:410:2: warning: (near initialization for ‘port_methods[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:410:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:410:2: error: (near initialization for ‘port_methods[19]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:410:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:410:2: warning: (near initialization for ‘port_methods[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:412:2: warning: braces around scalar initializer [enabled by default]
  { "flow_control", lua_port_get_flow },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:412:2: warning: (near initialization for ‘port_methods[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:412:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:412:2: warning: (near initialization for ‘port_methods[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:412:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:412:2: error: (near initialization for ‘port_methods[20]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:412:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:412:2: warning: (near initialization for ‘port_methods[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:413:2: warning: braces around scalar initializer [enabled by default]
  { "flow_control_tostring", lua_port_get_strflow },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:413:2: warning: (near initialization for ‘port_methods[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:413:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:413:2: warning: (near initialization for ‘port_methods[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:413:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:413:2: error: (near initialization for ‘port_methods[21]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:413:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:413:2: warning: (near initialization for ‘port_methods[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:414:2: warning: braces around scalar initializer [enabled by default]
  { "set_flow_control", lua_port_set_flow },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:414:2: warning: (near initialization for ‘port_methods[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:414:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:414:2: warning: (near initialization for ‘port_methods[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:414:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:414:2: error: (near initialization for ‘port_methods[22]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:414:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:414:2: warning: (near initialization for ‘port_methods[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:416:2: warning: braces around scalar initializer [enabled by default]
  { "dtr", lua_port_get_dtr },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:416:2: warning: (near initialization for ‘port_methods[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:416:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:416:2: warning: (near initialization for ‘port_methods[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:416:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:416:2: error: (near initialization for ‘port_methods[23]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:416:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:416:2: warning: (near initialization for ‘port_methods[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:417:2: warning: braces around scalar initializer [enabled by default]
  { "dtr_tostring", lua_port_get_strdtr },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:417:2: warning: (near initialization for ‘port_methods[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:417:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:417:2: warning: (near initialization for ‘port_methods[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:417:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:417:2: error: (near initialization for ‘port_methods[24]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:417:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:417:2: warning: (near initialization for ‘port_methods[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:418:2: warning: braces around scalar initializer [enabled by default]
  { "set_dtr", lua_port_set_dtr },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:418:2: warning: (near initialization for ‘port_methods[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:418:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:418:2: warning: (near initialization for ‘port_methods[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:418:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:418:2: error: (near initialization for ‘port_methods[25]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:418:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:418:2: warning: (near initialization for ‘port_methods[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:420:2: warning: braces around scalar initializer [enabled by default]
  { "rts", lua_port_get_rts },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:420:2: warning: (near initialization for ‘port_methods[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:420:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:420:2: warning: (near initialization for ‘port_methods[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:420:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:420:2: error: (near initialization for ‘port_methods[26]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:420:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:420:2: warning: (near initialization for ‘port_methods[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:421:2: warning: braces around scalar initializer [enabled by default]
  { "rts_tostring", lua_port_get_strrts },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:421:2: warning: (near initialization for ‘port_methods[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:421:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:421:2: warning: (near initialization for ‘port_methods[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:421:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:421:2: error: (near initialization for ‘port_methods[27]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:421:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:421:2: warning: (near initialization for ‘port_methods[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:422:2: warning: braces around scalar initializer [enabled by default]
  { "set_rts", lua_port_set_rts },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:422:2: warning: (near initialization for ‘port_methods[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:422:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:422:2: warning: (near initialization for ‘port_methods[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:422:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:422:2: error: (near initialization for ‘port_methods[28]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:422:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:422:2: warning: (near initialization for ‘port_methods[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:423:2: warning: braces around scalar initializer [enabled by default]
  { NULL, NULL }
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:423:2: warning: (near initialization for ‘port_methods[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:423:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:423:2: warning: (near initialization for ‘port_methods[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:423:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:423:2: warning: (near initialization for ‘port_methods[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:426:1: error: unknown type name ‘luaL_reg’
 static luaL_reg port_functions[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:427:2: warning: braces around scalar initializer [enabled by default]
  { "open", lua_port_open },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:427:2: warning: (near initialization for ‘port_functions[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:427:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:427:2: warning: (near initialization for ‘port_functions[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:427:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:427:2: error: (near initialization for ‘port_functions[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:427:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:427:2: warning: (near initialization for ‘port_functions[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:428:2: warning: braces around scalar initializer [enabled by default]
  { "error_tostring", lua_port_strerror },
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:428:2: warning: (near initialization for ‘port_functions[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:428:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:428:2: warning: (near initialization for ‘port_functions[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:428:2: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:428:2: error: (near initialization for ‘port_functions[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:428:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:428:2: warning: (near initialization for ‘port_functions[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:429:2: warning: braces around scalar initializer [enabled by default]
  { NULL, NULL }
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:429:2: warning: (near initialization for ‘port_functions[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:429:2: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:429:2: warning: (near initialization for ‘port_functions[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:429:2: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:429:2: warning: (near initialization for ‘port_functions[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:432:1: error: unknown type name ‘luaL_reg’
 static void create_metatables(lua_State *L, const char *name, const luaL_reg *methods)
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c: In function ‘create_metatables’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:437:2: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
  luaL_register(L, NULL, methods);
  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:26:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lauxlib.h:202:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c: In function ‘luaopen_luars232’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:445:2: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
  luaL_register(L, MODULE_NAMESPACE, port_functions);
  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luars232 1.0.3-1/bindings/lua/luars232.c:26:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lauxlib.h:202:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
make[2]: *** [CMakeFiles/luars232.dir/bindings/lua/luars232.c.o] Error 1
make[1]: *** [CMakeFiles/luars232.dir/all] Error 2
make: *** [all] Error 2

