# Report for 'install lua 5.1.5-1 battery_status'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- lgi 0.7.2-1
- lrexlib-posix 2.7.2-1
- luafilesystem 1.6.2-2
- battery_status 1.1-1

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1
- **lgi 0.7.2-1**
    - **remote:** git://github.com/LuaDist-testing/lgi.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lgi 0.7.2-1
- **lrexlib-posix 2.7.2-1**
    - **remote:** git://github.com/LuaDist-testing/lrexlib-posix.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lrexlib-posix 2.7.2-1
- **luafilesystem 1.6.2-2**
    - **remote:** git://github.com/LuaDist-testing/luafilesystem.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/luafilesystem 1.6.2-2
- **battery_status 1.1-1**
    - **remote:** git://github.com/LuaDist-testing/battery_status.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/battery_status 1.1-1

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

### lgi 0.7.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lgi 0.7.2-1/lgi-0.7.2-1.rockspec'
- **Error:** Could not generate cmake commands for package 'lgi 0.7.2-1': Unhandled rockspec build type: "make"
