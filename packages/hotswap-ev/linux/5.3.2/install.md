# Report for 'install lua 5.3.2 hotswap-ev'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- hotswap 1.3-2
- lua-ev v1.4-1
- luaposix 33.2.1-1
- xxhash v1.0-1
- hotswap-ev 1.2-2

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **hotswap 1.3-2**
    - **remote:** git://github.com/LuaDist-testing/hotswap.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/hotswap 1.3-2
- **lua-ev v1.4-1**
    - **remote:** git://github.com/LuaDist-testing/lua-ev.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-ev v1.4-1
- **luaposix 33.2.1-1**
    - **remote:** git://github.com/LuaDist-testing/luaposix.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luaposix 33.2.1-1
- **xxhash v1.0-1**
    - **remote:** git://github.com/LuaDist-testing/xxhash.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/xxhash v1.0-1
- **hotswap-ev 1.2-2**
    - **remote:** git://github.com/LuaDist-testing/hotswap-ev.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/hotswap-ev 1.2-2

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

### hotswap 1.3-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/hotswap 1.3-2/hotswap-1.3-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/hotswap 1.3-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/hotswap 1.3-2-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/hotswap 1.3-2-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/hotswap 1.3-2'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/hotswap 1.3-2-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/share/luadist2/manifest-file'

### lua-ev v1.4-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-ev v1.4-1/lua-ev-v1.4-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-ev v1.4-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-ev v1.4-1-build'
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
- **Error:** Error building package 'lua-ev v1.4-1': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-ev v1.4-1-build/cmake.cache'
stdout:
loading initial cache file cache.cmake
-- The C compiler identification is GNU 4.8.4
-- The CXX compiler identification is GNU 4.8.4
-- Check for working C compiler: /usr/bin/gcc
-- Check for working C compiler: /usr/bin/gcc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Found Lua: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/lib/liblua.so;/usr/lib/x86_64-linux-gnu/libm.so (found version "5.3.2") 
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-ev v1.4-1-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Warning at CMakeLists.txt:40 (find_package):
  By not providing "FindLIBEV.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "LIBEV", but
  CMake did not find one.

  Could not find a package configuration file provided by "LIBEV" with any of
  the following names:

    LIBEVConfig.cmake
    libev-config.cmake

  Add the installation prefix of "LIBEV" to CMAKE_PREFIX_PATH or set
  "LIBEV_DIR" to a directory containing one of the above files.  If "LIBEV"
  provides a separate development package or SDK, be sure it has been
  installed.


CMake Error at CMakeLists.txt:73 (target_link_libraries):
  Target "ev" of type MODULE_LIBRARY may not be linked into another target.
  One may link only to STATIC or SHARED libraries, or to executables with the
  ENABLE_EXPORTS property set.



