# Report for 'install lua 5.3.2 simpleitk'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- simpleitk 1.1.0-0

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **simpleitk 1.1.0-0**
    - **remote:** git://github.com/LuaDist-testing/simpleitk.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0

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

### simpleitk 1.1.0-0
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0/simpleitk-1.1.0-0.rockspec'
- Package 'simpleitk 1.1.0-0': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0-build'
- **CMake Variables:**
    - `CFLAGS:STRING` = $(CFLAGS)
    - `CMAKE_BUILD_TYPE` = $(CMAKE_BUILD_TYPE)
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
    - `SimpleITK_VERSION` = 1.1.0
- **Error:** Error building package 'simpleitk 1.1.0-0': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0-build'
stdout:
Scanning dependencies of target SimpleITKSuperbuild-download
[  6%] Creating directories for 'SimpleITKSuperbuild-download'
[ 12%] Performing download step (git clone) for 'SimpleITKSuperbuild-download'
Your branch is up to date with 'origin/master'.
[ 18%] No patch step for 'SimpleITKSuperbuild-download'
[ 25%] Performing update step for 'SimpleITKSuperbuild-download'
Current branch master is up to date.
[ 31%] No configure step for 'SimpleITKSuperbuild-download'
[ 37%] No build step for 'SimpleITKSuperbuild-download'
[ 43%] No install step for 'SimpleITKSuperbuild-download'
[ 50%] Completed 'SimpleITKSuperbuild-download'
[ 50%] Built target SimpleITKSuperbuild-download
Scanning dependencies of target SimpleITKSuperbuild
[ 56%] Creating directories for 'SimpleITKSuperbuild'
[ 62%] No download step for 'SimpleITKSuperbuild'
[ 68%] No patch step for 'SimpleITKSuperbuild'
[ 75%] No update step for 'SimpleITKSuperbuild'
[ 81%] Performing configure step for 'SimpleITKSuperbuild'
loading initial cache file /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0-build/SimpleITKSuperbuild-prefix/tmp/SimpleITKSuperbuild-cache-.cmake
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
-- Found Git: /usr/bin/git (found version "2.15.1") 
-- Setting build type to 'Release' as none was specified.
-- Performing Test CXX_HAS_stdcxx11
-- Performing Test CXX_HAS_stdcxx11 - Success
-- Checking if c++11 is required...
-- Checking if c++11 is required... NO
-- Performing Test Weak Link MODULE -> SHARED (gnu_ld_ignore) - Failed
-- Performing Test Weak Link MODULE -> SHARED (osx_dynamic_lookup) - Failed
-- Performing Test Weak Link MODULE -> SHARED (no_flag) - Failed
-- Found Tclsh: /usr/bin/tclsh (found version "8.6") 
-- Found BISON: /usr/bin/bison (found version "3.0.2") 
-- Passing variable "ITK_BUILD_DEFAULT_MODULES=ON" to ITK external project.
-- Passing variable "Module_ITKReview=ON" to ITK external project.
-- Passing variable "Module_SimpleITKFilters=ON" to ITK external project.
-- Passing variable "SITK_CXX11_NOT_REQUIRED=TRUE" to SimpleITK external project.
-- Passing variable "SimpleITK_4D_IMAGES=ON" to SimpleITK external project.
-- Passing variable "SimpleITK_GIT_PROTOCOL=https" to SimpleITK external project.
-- Passing variable "SimpleITK_LUA_EXECUTABLE=/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0-build/SimpleITKSuperbuild-build/Lua/bin/lua" to SimpleITK external project.
-- Configuring incomplete, errors occurred!
See also "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0-build/SimpleITKSuperbuild-build/CMakeFiles/CMakeOutput.log".
See also "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0-build/SimpleITKSuperbuild-build/CMakeFiles/CMakeError.log".

stderr:
Cloning into 'SimpleITKSuperbuild'...
warning: redirecting to https://itk.org/SimpleITK.git/
Already on 'master'
warning: redirecting to https://itk.org/SimpleITK.git/
CMake Error: Error processing file: /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/simpleitk 1.1.0-0-build/SimpleITKSuperbuild-prefix/tmp/SimpleITKSuperbuild-cache-.cmake
make[2]: *** [SimpleITKSuperbuild-prefix/src/SimpleITKSuperbuild-stamp/SimpleITKSuperbuild-configure] Error 1
make[1]: *** [CMakeFiles/SimpleITKSuperbuild.dir/all] Error 2
make: *** [all] Error 2

