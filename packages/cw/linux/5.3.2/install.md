# Report for 'install lua 5.3.2 cw'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- luaposix 33.2.1-1
- ansicolors 1.0.2-3
- luafilesystem 1.7.0-2
- penlight 1.5.4-1
- markdown 0.33-1
- ldoc 1.4.6-2
- cw 2.0.3-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **luaposix 33.2.1-1**
    - **remote:** git://github.com/LuaDist-testing/luaposix.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luaposix 33.2.1-1
- **ansicolors 1.0.2-3**
    - **remote:** git://github.com/LuaDist-testing/ansicolors.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/ansicolors 1.0.2-3
- **luafilesystem 1.7.0-2**
    - **remote:** git://github.com/LuaDist-testing/luafilesystem.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luafilesystem 1.7.0-2
- **penlight 1.5.4-1**
    - **remote:** git://github.com/LuaDist-testing/penlight.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/penlight 1.5.4-1
- **markdown 0.33-1**
    - **remote:** git://github.com/LuaDist-testing/markdown.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/markdown 0.33-1
- **ldoc 1.4.6-2**
    - **remote:** git://github.com/LuaDist-testing/ldoc.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/ldoc 1.4.6-2
- **cw 2.0.3-1**
    - **remote:** git://github.com/LuaDist-testing/cw.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/cw 2.0.3-1

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

### luaposix 33.2.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luaposix 33.2.1-1/luaposix-33.2.1-1.rockspec'
- **Error:** Could not generate cmake commands for package 'luaposix 33.2.1-1': Unhandled rockspec build type: "command"
