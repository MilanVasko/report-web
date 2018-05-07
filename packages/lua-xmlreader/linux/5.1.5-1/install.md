# Report for 'install lua 5.1.5-1 lua-xmlreader'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- lua-xmlreader 0.1-2

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1
- **lua-xmlreader 0.1-2**
    - **remote:** git://github.com/LuaDist-testing/lua-xmlreader.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-xmlreader 0.1-2

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

### lua-xmlreader 0.1-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-xmlreader 0.1-2/lua-xmlreader-0.1-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-xmlreader 0.1-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-xmlreader 0.1-2-build'
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
- **Error:** Error building package 'lua-xmlreader 0.1-2': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-xmlreader 0.1-2-build/cmake.cache'
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
-- Found Lua: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/lib/liblua.so;/usr/lib/x86_64-linux-gnu/libm.so (found version "5.1.5") 
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-xmlreader 0.1-2-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Warning at CMakeLists.txt:40 (find_package):
  By not providing "FindLIBXML2.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "LIBXML2", but
  CMake did not find one.

  Could not find a package configuration file provided by "LIBXML2" with any
  of the following names:

    LIBXML2Config.cmake
    libxml2-config.cmake

  Add the installation prefix of "LIBXML2" to CMAKE_PREFIX_PATH or set
  "LIBXML2_DIR" to a directory containing one of the above files.  If
  "LIBXML2" provides a separate development package or SDK, be sure it has
  been installed.


CMake Error at CMakeLists.txt:44 (set):
  Syntax error in cmake code at

    /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-xmlreader 0.1-2/CMakeLists.txt:44

  when parsing string

    ${(LIBXML2_INCDIR)/libxml2}

  Invalid character ('(') in a variable name: ''



