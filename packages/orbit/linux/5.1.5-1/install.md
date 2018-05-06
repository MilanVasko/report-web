# Report for 'install lua 5.1.5-1 orbit'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- luafilesystem 1.7.0-2
- lpeg 1.0.1-1
- rings 1.3.0-1
- coxpcall 1.17.0-1
- wsapi 1.7-1
- luasocket 3.0rc1-2
- copas 2.0.2-1
- xavante 2.4.0-1
- wsapi-xavante 1.7-1
- cosmo 16.06.04-1
- orbit 2.2.4-1

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1
- **luafilesystem 1.7.0-2**
    - **remote:** git://github.com/LuaDist-testing/luafilesystem.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.7.0-2
- **lpeg 1.0.1-1**
    - **remote:** git://github.com/LuaDist-testing/lpeg.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lpeg 1.0.1-1
- **rings 1.3.0-1**
    - **remote:** git://github.com/LuaDist-testing/rings.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/rings 1.3.0-1
- **coxpcall 1.17.0-1**
    - **remote:** git://github.com/LuaDist-testing/coxpcall.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/coxpcall 1.17.0-1
- **wsapi 1.7-1**
    - **remote:** git://github.com/LuaDist-testing/wsapi.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi 1.7-1
- **luasocket 3.0rc1-2**
    - **remote:** git://github.com/LuaDist-testing/luasocket.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luasocket 3.0rc1-2
- **copas 2.0.2-1**
    - **remote:** git://github.com/LuaDist-testing/copas.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/copas 2.0.2-1
- **xavante 2.4.0-1**
    - **remote:** git://github.com/LuaDist-testing/xavante.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/xavante 2.4.0-1
- **wsapi-xavante 1.7-1**
    - **remote:** git://github.com/LuaDist-testing/wsapi-xavante.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi-xavante 1.7-1
- **cosmo 16.06.04-1**
    - **remote:** git://github.com/LuaDist-testing/cosmo.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/cosmo 16.06.04-1
- **orbit 2.2.4-1**
    - **remote:** git://github.com/LuaDist-testing/orbit.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/orbit 2.2.4-1

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

### luafilesystem 1.7.0-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.7.0-2/luafilesystem-1.7.0-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.7.0-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.7.0-2-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.7.0-2-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.7.0-2'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.7.0-2-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### lpeg 1.0.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lpeg 1.0.1-1/lpeg-1.0.1-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lpeg 1.0.1-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lpeg 1.0.1-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lpeg 1.0.1-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lpeg 1.0.1-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lpeg 1.0.1-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### rings 1.3.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/rings 1.3.0-1/rings-1.3.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/rings 1.3.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/rings 1.3.0-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/rings 1.3.0-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/rings 1.3.0-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/rings 1.3.0-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### coxpcall 1.17.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/coxpcall 1.17.0-1/coxpcall-1.17.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/coxpcall 1.17.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/coxpcall 1.17.0-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/coxpcall 1.17.0-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/coxpcall 1.17.0-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/coxpcall 1.17.0-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### wsapi 1.7-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi 1.7-1/wsapi-1.7-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi 1.7-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi 1.7-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi 1.7-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi 1.7-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi 1.7-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### luasocket 3.0rc1-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luasocket 3.0rc1-2/luasocket-3.0rc1-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luasocket 3.0rc1-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luasocket 3.0rc1-2-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luasocket 3.0rc1-2-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luasocket 3.0rc1-2'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luasocket 3.0rc1-2-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### copas 2.0.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/copas 2.0.2-1/copas-2.0.2-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/copas 2.0.2-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/copas 2.0.2-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/copas 2.0.2-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/copas 2.0.2-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/copas 2.0.2-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### xavante 2.4.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/xavante 2.4.0-1/xavante-2.4.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/xavante 2.4.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/xavante 2.4.0-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/xavante 2.4.0-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/xavante 2.4.0-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/xavante 2.4.0-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### wsapi-xavante 1.7-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi-xavante 1.7-1/wsapi-xavante-1.7-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi-xavante 1.7-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi-xavante 1.7-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi-xavante 1.7-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi-xavante 1.7-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/wsapi-xavante 1.7-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### cosmo 16.06.04-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/cosmo 16.06.04-1/cosmo-16.06.04-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/cosmo 16.06.04-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/cosmo 16.06.04-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/cosmo 16.06.04-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/cosmo 16.06.04-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/cosmo 16.06.04-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/luadist2/manifest-file'

### orbit 2.2.4-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/orbit 2.2.4-1/orbit-2.2.4-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/orbit 2.2.4-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/orbit 2.2.4-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/orbit 2.2.4-1-build" && cmake -P cmake_install.cmake'
- **Error:** Could not install package 'orbit 2.2.4-1' from directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/orbit 2.2.4-1-build'
stdout:
-- Install configuration: ""
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/makedoc.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/license.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/example.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/reference.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/doc.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/pages.md
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/reference.md
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/pages.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/orbit.png
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/markdown.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/license.md
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/example.md
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/index.md
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/doc/us/index.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/op.ws
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/populate_mysql_blog.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms_schema.mysql
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/dump.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/markdown.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms.fcgi
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/post_pages.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/archive.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/post.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/images
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/images/head.jpg
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/home.xml
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/style.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/layout.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/blog/home.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/layout.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/styles
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/styles/print.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/styles/stylesheet1.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/styles/stylesheet2.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/section_menu-people.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/simple_post.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/post.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/list_pubs.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/images
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/images/xavante.png
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/images/header.jpg
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/section_menu-projects.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/section_menu-publications.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/index_short_info.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/lablua/home.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/archive.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/base_styles.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/theme_styles.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/post.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/images
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/images/orbit.png
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/images/head.jpg
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/home.xml
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/style.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/layout.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/templates/aboutanything/home.html
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/populate_mysql_lablua.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/lablua.db
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms_schema.sql
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/admin_style.css
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms.ws
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/index.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms.db
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/.htaccess
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms_config.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/blog.db
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/blog.dump.sqlite3
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms_admin.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms_plugins.lua
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/cached.diff
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/toycms/toycms.cgi
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/README
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/songs
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/songs/songs.cgi
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/songs/songs.ws
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/songs/songs.fcgi
-- Installing: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/share/orbit/samples/songs/songs.lua

stderr:
CMake Error at cmake_install.cmake:36 (file):
  file INSTALL cannot find
  "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/orbit
  2.2.4-1/samples/doc".



