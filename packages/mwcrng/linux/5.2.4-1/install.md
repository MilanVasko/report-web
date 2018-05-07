# Report for 'install lua 5.2.4-1 mwcrng'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- mwcrng 1.2-1

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **mwcrng 1.2-1**
    - **remote:** git://github.com/LuaDist-testing/mwcrng.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1

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

### mwcrng 1.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/mwcrng-1.2-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1-build'
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
- **Error:** Error building package 'mwcrng 1.2-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1-build'
stdout:
Scanning dependencies of target mwcrng
[ 50%] Building C object CMakeFiles/mwcrng.dir/l_rng.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:7:1: error: unknown type name ‘uint32_t’
 static uint32_t seeds[NUMBER_OF_SEEDS];
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:8:1: error: unknown type name ‘uint32_t’
 static uint32_t carry = 362436;
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:12:15: error: unknown type name ‘uint32_t’
 void init_rng(uint32_t metaseed)
               ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:32:1: error: unknown type name ‘uint32_t’
 static uint32_t CMWC4096()
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c: In function ‘CMWC4096’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:35:5: error: unknown type name ‘uint64_t’
     uint64_t multiplier = 18782;
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:36:5: error: unknown type name ‘uint32_t’
     static uint32_t seed_selection = NUMBER_OF_SEEDS - 1;
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:37:5: error: unknown type name ‘uint64_t’
     uint64_t t = 0;
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:38:5: error: unknown type name ‘uint32_t’
     uint32_t j = 0;
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:39:5: error: unknown type name ‘uint32_t’
     static uint32_t lag = 0xfffffffe;
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:43:5: warning: right shift count >= width of type [enabled by default]
     carry = (t>>32);
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c: In function ‘l_init’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:58:15: error: ‘uint32_t’ undeclared (first use in this function)
     init_rng((uint32_t) luaL_checkinteger(L, 1));
               ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:58:15: note: each undeclared identifier is reported only once for each function it appears in
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:58:25: error: expected ‘)’ before ‘luaL_checkinteger’
     init_rng((uint32_t) luaL_checkinteger(L, 1));
                         ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c: In function ‘l_dice’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:84:5: error: ‘for’ loop initial declarations are only allowed in C99 mode
     for(int t = 0; t < throws; t++)
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/mwcrng 1.2-1/l_rng.c:84:5: note: use option -std=c99 or -std=gnu99 to compile your code
make[2]: *** [CMakeFiles/mwcrng.dir/l_rng.c.o] Error 1
make[1]: *** [CMakeFiles/mwcrng.dir/all] Error 2
make: *** [all] Error 2

