# Report for 'install lua 5.2.4-1 luacrypto'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- luacrypto 0.3.2-2

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **luacrypto 0.3.2-2**
    - **remote:** git://github.com/LuaDist-testing/luacrypto.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luacrypto 0.3.2-2

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

### luacrypto 0.3.2-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luacrypto 0.3.2-2/luacrypto-0.3.2-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luacrypto 0.3.2-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luacrypto 0.3.2-2-build'
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
- **Error:** Error building package 'luacrypto 0.3.2-2': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luacrypto 0.3.2-2-build/cmake.cache'
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
-- Found Lua: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/lib/liblua.so;/usr/lib/x86_64-linux-gnu/libm.so (found version "5.2.4") 
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luacrypto 0.3.2-2-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Warning at CMakeLists.txt:40 (find_package):
  By not providing "FindOPENSSL.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "OPENSSL", but
  CMake did not find one.

  Could not find a package configuration file provided by "OPENSSL" with any
  of the following names:

    OPENSSLConfig.cmake
    openssl-config.cmake

  Add the installation prefix of "OPENSSL" to CMAKE_PREFIX_PATH or set
  "OPENSSL_DIR" to a directory containing one of the above files.  If
  "OPENSSL" provides a separate development package or SDK, be sure it has
  been installed.


CMake Error at CMakeLists.txt:84 (target_link_libraries):
  Target "crypto" of type MODULE_LIBRARY may not be linked into another
  target.  One may link only to STATIC or SHARED libraries, or to executables
  with the ENABLE_EXPORTS property set.



