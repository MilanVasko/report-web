# Report for 'install lua 5.3.2 bigint'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- bigint 1.0.2-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **bigint 1.0.2-1**
    - **remote:** git://github.com/LuaDist-testing/bigint.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1

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

### bigint 1.0.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/bigint-1.0.2-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1-build'
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
- **Error:** Error building package 'bigint 1.0.2-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1-build'
stdout:
Scanning dependencies of target bigint
[ 25%] Building CXX object CMakeFiles/bigint.dir/BigInt.cpp.o
[ 50%] Building C object CMakeFiles/bigint.dir/mainlib.c.o
[ 75%] Building CXX object CMakeFiles/bigint.dir/bigint-glue.cpp.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.cpp: In member function ‘BigInt BigInt::inv(const BigInt&) const’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.cpp:1411:12: warning: deprecated conversion from string constant to ‘char*’ [-Wwrite-strings]
    bi_p[0] = (const char *)"0";
            ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.cpp:1447:10: warning: deprecated conversion from string constant to ‘char*’ [-Wwrite-strings]
   bi_ret = (const char *)"0";
          ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/bigint-glue.cpp: In function ‘void construct_bigint(lua_State*, int)’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/bigint-glue.cpp:75:45: error: call of overloaded ‘BigInt(lua_Integer)’ is ambiguous
     *b = new BigInt(lua_tointeger(L, argidx));
                                             ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/bigint-glue.cpp:75:45: note: candidates are:
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/bigint-glue.cpp:40:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.h:61:2: note: BigInt::BigInt(const unsigned char*) <near match>
  BigInt(const unsigned char*);
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.h:61:2: note:   no known conversion for argument 1 from ‘lua_Integer {aka long long int}’ to ‘const unsigned char*’
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.h:60:2: note: BigInt::BigInt(const char*) <near match>
  BigInt(const char*);
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.h:60:2: note:   no known conversion for argument 1 from ‘lua_Integer {aka long long int}’ to ‘const char*’
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.h:59:2: note: BigInt::BigInt(long unsigned int)
  BigInt(unsigned long);
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.h:58:2: note: BigInt::BigInt(long int)
  BigInt(long);
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/bigint 1.0.2-1/BigInt.h:55:2: note: BigInt::BigInt(const BigInt&)
  BigInt(const BigInt&);
  ^
make[2]: *** [CMakeFiles/bigint.dir/bigint-glue.cpp.o] Error 1
make[1]: *** [CMakeFiles/bigint.dir/all] Error 2
make: *** [all] Error 2

