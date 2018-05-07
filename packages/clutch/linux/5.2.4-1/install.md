# Report for 'install lua 5.2.4-1 clutch'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- clutch 1.2-2

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **clutch 1.2-2**
    - **remote:** git://github.com/LuaDist-testing/clutch.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2

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

### clutch 1.2-2
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch-1.2-2.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2-build'
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
- **Error:** Error building package 'clutch 1.2-2': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2-build'
stdout:
Scanning dependencies of target clutch
[ 50%] Building C object CMakeFiles/clutch.dir/clutch.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c: In function ‘bind_params’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c:242:3: error: ‘for’ loop initial declarations are only allowed in C99 mode
   for (int i = 1; i <= count; ++i) {
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c:242:3: note: use option -std=c99 or -std=gnu99 to compile your code
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c: In function ‘bind_locals’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c:304:3: error: ‘for’ loop initial declarations are only allowed in C99 mode
   for (int i = 1; i <= count; ++i) {
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c: In function ‘find_local’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c:324:3: error: ‘for’ loop initial declarations are only allowed in C99 mode
   for (int level = 1; lua_getstack(L, level, &debug); ++level) {
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c: In function ‘step_all’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c:353:3: error: ‘for’ loop initial declarations are only allowed in C99 mode
   for (int i = 1; step(L, stmt); ++i)
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c: In function ‘handle_row’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/clutch 1.2-2/clutch.c:374:3: error: ‘for’ loop initial declarations are only allowed in C99 mode
   for (int i = 0; i < count; ++i) {
   ^
make[2]: *** [CMakeFiles/clutch.dir/clutch.c.o] Error 1
make[1]: *** [CMakeFiles/clutch.dir/all] Error 2
make: *** [all] Error 2

