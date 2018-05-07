# Report for 'install lua 5.1.5-1 lua-sdl2'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- lua-sdl2 2.0.5.6.0-1

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1
- **lua-sdl2 2.0.5.6.0-1**
    - **remote:** git://github.com/LuaDist-testing/lua-sdl2.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-sdl2 2.0.5.6.0-1

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

### lua-sdl2 2.0.5.6.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-sdl2 2.0.5.6.0-1/lua-sdl2-2.0.5.6.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-sdl2 2.0.5.6.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-sdl2 2.0.5.6.0-1-build'
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
- **Error:** Error building package 'lua-sdl2 2.0.5.6.0-1': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-sdl2 2.0.5.6.0-1-build/cmake.cache'
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
See also "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-sdl2 2.0.5.6.0-1-build/CMakeFiles/CMakeOutput.log".

stderr:
CMake Warning at CMakeLists.txt:40 (find_package):
  By not providing "FindSDL2.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "SDL2", but
  CMake did not find one.

  Could not find a package configuration file provided by "SDL2" with any of
  the following names:

    SDL2Config.cmake
    sdl2-config.cmake

  Add the installation prefix of "SDL2" to CMAKE_PREFIX_PATH or set
  "SDL2_DIR" to a directory containing one of the above files.  If "SDL2"
  provides a separate development package or SDK, be sure it has been
  installed.


CMake Warning at CMakeLists.txt:44 (find_package):
  By not providing "FindSDL2_image.cmake" in CMAKE_MODULE_PATH this project
  has asked CMake to find a package configuration file provided by
  "SDL2_image", but CMake did not find one.

  Could not find a package configuration file provided by "SDL2_image" with
  any of the following names:

    SDL2_imageConfig.cmake
    sdl2_image-config.cmake

  Add the installation prefix of "SDL2_image" to CMAKE_PREFIX_PATH or set
  "SDL2_image_DIR" to a directory containing one of the above files.  If
  "SDL2_image" provides a separate development package or SDK, be sure it has
  been installed.


CMake Warning at CMakeLists.txt:48 (find_package):
  By not providing "FindSDL2_mixer.cmake" in CMAKE_MODULE_PATH this project
  has asked CMake to find a package configuration file provided by
  "SDL2_mixer", but CMake did not find one.

  Could not find a package configuration file provided by "SDL2_mixer" with
  any of the following names:

    SDL2_mixerConfig.cmake
    sdl2_mixer-config.cmake

  Add the installation prefix of "SDL2_mixer" to CMAKE_PREFIX_PATH or set
  "SDL2_mixer_DIR" to a directory containing one of the above files.  If
  "SDL2_mixer" provides a separate development package or SDK, be sure it has
  been installed.


CMake Warning at CMakeLists.txt:52 (find_package):
  By not providing "FindSDL2_net.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "SDL2_net",
  but CMake did not find one.

  Could not find a package configuration file provided by "SDL2_net" with any
  of the following names:

    SDL2_netConfig.cmake
    sdl2_net-config.cmake

  Add the installation prefix of "SDL2_net" to CMAKE_PREFIX_PATH or set
  "SDL2_net_DIR" to a directory containing one of the above files.  If
  "SDL2_net" provides a separate development package or SDK, be sure it has
  been installed.


CMake Warning at CMakeLists.txt:56 (find_package):
  By not providing "FindSDL2_ttf.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "SDL2_ttf",
  but CMake did not find one.

  Could not find a package configuration file provided by "SDL2_ttf" with any
  of the following names:

    SDL2_ttfConfig.cmake
    sdl2_ttf-config.cmake

  Add the installation prefix of "SDL2_ttf" to CMAKE_PREFIX_PATH or set
  "SDL2_ttf_DIR" to a directory containing one of the above files.  If
  "SDL2_ttf" provides a separate development package or SDK, be sure it has
  been installed.


CMake Error at CMakeLists.txt:83 (set):
  Syntax error in cmake code at

    /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua-sdl2 2.0.5.6.0-1/CMakeLists.txt:83

  when parsing string

    ${(SDL2_INCDIR)/SDL2}

  Invalid character ('(') in a variable name: ''



