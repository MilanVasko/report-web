# Report for 'install lua 5.2.4-1 perimeterx-nginx-plugin'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- lua-resty-http 0.12-0
- lua-resty-nettle 0.105-1
- luasocket 3.0rc1-2
- lustache 1.3.1-0
- perimeterx-nginx-plugin 3.3-0

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **lua-resty-http 0.12-0**
    - **remote:** git://github.com/LuaDist-testing/lua-resty-http.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-http 0.12-0
- **lua-resty-nettle 0.105-1**
    - **remote:** git://github.com/LuaDist-testing/lua-resty-nettle.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-nettle 0.105-1
- **luasocket 3.0rc1-2**
    - **remote:** git://github.com/LuaDist-testing/luasocket.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luasocket 3.0rc1-2
- **lustache 1.3.1-0**
    - **remote:** git://github.com/LuaDist-testing/lustache.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lustache 1.3.1-0
- **perimeterx-nginx-plugin 3.3-0**
    - **remote:** git://github.com/LuaDist-testing/perimeterx-nginx-plugin.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/perimeterx-nginx-plugin 3.3-0

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

### lua-resty-http 0.12-0
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-http 0.12-0/lua-resty-http-0.12-0.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-http 0.12-0'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-http 0.12-0-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-http 0.12-0-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-http 0.12-0'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-http 0.12-0-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/share/luadist2/manifest-file'

### lua-resty-nettle 0.105-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-nettle 0.105-1/lua-resty-nettle-0.105-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-nettle 0.105-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-nettle 0.105-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-nettle 0.105-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-nettle 0.105-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua-resty-nettle 0.105-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/share/luadist2/manifest-file'

### luasocket 3.0rc1-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luasocket 3.0rc1-2/luasocket-3.0rc1-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luasocket 3.0rc1-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luasocket 3.0rc1-2-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luasocket 3.0rc1-2-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luasocket 3.0rc1-2'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/luasocket 3.0rc1-2-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/share/luadist2/manifest-file'

### lustache 1.3.1-0
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lustache 1.3.1-0/lustache-1.3.1-0.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lustache 1.3.1-0'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lustache 1.3.1-0-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lustache 1.3.1-0-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lustache 1.3.1-0'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lustache 1.3.1-0-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/share/luadist2/manifest-file'

### perimeterx-nginx-plugin 3.3-0
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/perimeterx-nginx-plugin 3.3-0/perimeterx-nginx-plugin-3.3-0.rockspec'
- **Error:** Could not generate cmake commands for package 'perimeterx-nginx-plugin 3.3-0': Unhandled rockspec build type: "make"
