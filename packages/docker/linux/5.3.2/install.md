# Report for 'install lua 5.3.2 docker'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- deviant 0.1.3-1
- web 0.2.4-1
- docker 0.1-4

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **deviant 0.1.3-1**
    - **remote:** git://github.com/LuaDist-testing/deviant.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/deviant 0.1.3-1
- **web 0.2.4-1**
    - **remote:** git://github.com/LuaDist-testing/web.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/web 0.2.4-1
- **docker 0.1-4**
    - **remote:** git://github.com/LuaDist-testing/docker.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/docker 0.1-4

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

### deviant 0.1.3-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/deviant 0.1.3-1/deviant-0.1.3-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/deviant 0.1.3-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/deviant 0.1.3-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/deviant 0.1.3-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/deviant 0.1.3-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/deviant 0.1.3-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/share/luadist2/manifest-file'

### web 0.2.4-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/web 0.2.4-1/web-0.2.4-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/web 0.2.4-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/web 0.2.4-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/web 0.2.4-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/web 0.2.4-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/web 0.2.4-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/share/luadist2/manifest-file'

### docker 0.1-4
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/docker 0.1-4/docker-0.1-4.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/docker 0.1-4'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/docker 0.1-4-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/docker 0.1-4-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/docker 0.1-4'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/docker 0.1-4-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/share/luadist2/manifest-file'
