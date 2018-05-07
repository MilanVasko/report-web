# Report for 'install lua 5.1.5-1 sleep'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.1.5-1
- sleep 1.0.0-3

## 3. Fetching packages

- **lua 5.1.5-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/lua 5.1.5-1
- **sleep 1.0.0-3**
    - **remote:** git://github.com/LuaDist-testing/sleep.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep 1.0.0-3

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

### sleep 1.0.0-3
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep 1.0.0-3/sleep-1.0.0-3.rockspec'
- Package 'sleep 1.0.0-3': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep 1.0.0-3-build'
- **CMake Variables:**
    - `CMAKE_BUILD_WITH_INSTALL_RPATH` = FALSE
    - `CMAKE_C_FLAGS` = $(CFLAGS)
    - `CMAKE_INCLUDE_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/include
    - `CMAKE_INSTALL_NAME_DIR` = @executable_path/../lib
    - `CMAKE_INSTALL_PREFIX` = /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1
    - `CMAKE_INSTALL_RPATH` = $ORIGIN/../lib
    - `CMAKE_INSTALL_RPATH_USE_LINK_PATH` = TRUE
    - `CMAKE_LIBRARY_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/lib;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/bin
    - `CMAKE_MODULE_LINKER_FLAGS` = $(LIBFLAG)
    - `CMAKE_PROGRAM_PATH` = ;/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/bin
    - `CMAKE_SKIP_BUILD_RPATH` = FALSE
    - `INSTALL_BIN` = bin
    - `INSTALL_CMOD` = lib/lua
    - `INSTALL_ETC` = etc
    - `INSTALL_LIB` = lib
    - `INSTALL_LMOD` = lib/lua
    - `INSTALL_SHARE` = share
    - `LUAROCKS_INSTALL_LIBDIR` = $(LIBDIR)
- **Error:** Error building package 'sleep 1.0.0-3': Could not preload the CMake cache script '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep 1.0.0-3-build/cmake.cache'
stdout:
loading initial cache file cache.cmake
-- The C compiler identification is GNU 4.8.4
-- Check for working C compiler: /usr/bin/gcc
-- Check for working C compiler: /usr/bin/gcc -- broken
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep 1.0.0-3-build/CMakeFiles/CMakeOutput.log".
See also "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep 1.0.0-3-build/CMakeFiles/CMakeError.log".

stderr:
CMake Error at /usr/local/cmake-3.9.2/share/cmake-3.9/Modules/CMakeTestCCompiler.cmake:51 (message):
  The C compiler "/usr/bin/gcc" is not able to compile a simple test program.

  It fails with the following output:

   Change Dir: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep 1.0.0-3-build/CMakeFiles/CMakeTmp

  

  Run Build Command:"/usr/bin/make" "cmTC_73ae4/fast"

  /usr/bin/make -f CMakeFiles/cmTC_73ae4.dir/build.make
  CMakeFiles/cmTC_73ae4.dir/build

  make[1]: Entering directory
  `/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep
  1.0.0-3-build/CMakeFiles/CMakeTmp'

  Building C object CMakeFiles/cmTC_73ae4.dir/testCCompiler.c.o

  /usr/bin/gcc -o CMakeFiles/cmTC_73ae4.dir/testCCompiler.c.o -c
  "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep
  1.0.0-3-build/CMakeFiles/CMakeTmp/testCCompiler.c"

  Linking C executable cmTC_73ae4

  /usr/local/cmake-3.9.2/bin/cmake -E cmake_link_script
  CMakeFiles/cmTC_73ae4.dir/link.txt --verbose=1

  /usr/bin/gcc $(CFLAGS) -rdynamic
  CMakeFiles/cmTC_73ae4.dir/testCCompiler.c.o -o cmTC_73ae4

  gcc: error: $(CFLAGS): No such file or directory

  make[1]: *** [cmTC_73ae4] Error 1

  make[1]: Leaving directory
  `/home/travis/build/LuaDist-testing/_luadist_install/lua 5.1.5-1/tmp/sleep
  1.0.0-3-build/CMakeFiles/CMakeTmp'

  make: *** [cmTC_73ae4/fast] Error 2

  

  

  CMake will not be able to correctly generate this project.
Call Stack (most recent call first):
  CMakeLists.txt:2 (project)



