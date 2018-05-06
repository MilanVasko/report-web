# Report for 'install lua 5.2.4-1 ldecnumber'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- ldecnumber 2.1-1

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **ldecnumber 2.1-1**
    - **remote:** git://github.com/LuaDist-testing/ldecnumber.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1

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

### ldecnumber 2.1-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecnumber-2.1-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1-build'
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
- **Error:** Error building package 'ldecnumber 2.1-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1-build'
stdout:
Scanning dependencies of target ldecNumber
[ 25%] Building C object CMakeFiles/ldecNumber.dir/ldecNumber.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c: In function ‘ldn_set_context’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:163:20: error: ‘LUA_ENVIRONINDEX’ undeclared (first use in this function)
     lua_rawset (L, LUA_ENVIRONINDEX);
                    ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:163:20: note: each undeclared identifier is reported only once for each function it appears in
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c: In function ‘ldn_push_context’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:179:20: error: ‘LUA_ENVIRONINDEX’ undeclared (first use in this function)
     lua_rawget (L, LUA_ENVIRONINDEX);
                    ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c: At top level:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:904:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg dn_drandom_meta_lib[] =
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:906:5: warning: braces around scalar initializer [enabled by default]
     { "__call",     drs_call  },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:906:5: warning: (near initialization for ‘dn_drandom_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:906:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:906:5: warning: (near initialization for ‘dn_drandom_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:906:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:906:5: error: (near initialization for ‘dn_drandom_meta_lib[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:906:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:906:5: warning: (near initialization for ‘dn_drandom_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:907:5: warning: braces around scalar initializer [enabled by default]
     { NULL,         NULL      }
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:907:5: warning: (near initialization for ‘dn_drandom_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:907:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:907:5: warning: (near initialization for ‘dn_drandom_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:907:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:907:5: warning: (near initialization for ‘dn_drandom_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:911:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg dn_dnumber_meta_lib[] =
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:913:5: warning: braces around scalar initializer [enabled by default]
     {"eq",              dn_eq     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:913:5: warning: (near initialization for ‘dn_dnumber_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:913:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:913:5: warning: (near initialization for ‘dn_dnumber_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:913:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:913:5: error: (near initialization for ‘dn_dnumber_meta_lib[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:913:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:913:5: warning: (near initialization for ‘dn_dnumber_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:914:5: warning: braces around scalar initializer [enabled by default]
     {"lt",              dn_lt     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:914:5: warning: (near initialization for ‘dn_dnumber_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:914:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:914:5: warning: (near initialization for ‘dn_dnumber_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:914:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:914:5: error: (near initialization for ‘dn_dnumber_meta_lib[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:914:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:914:5: warning: (near initialization for ‘dn_dnumber_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:915:5: warning: braces around scalar initializer [enabled by default]
     {"le",              dn_le     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:915:5: warning: (near initialization for ‘dn_dnumber_meta_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:915:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:915:5: warning: (near initialization for ‘dn_dnumber_meta_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:915:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:915:5: error: (near initialization for ‘dn_dnumber_meta_lib[2]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:915:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:915:5: warning: (near initialization for ‘dn_dnumber_meta_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:917:5: warning: braces around scalar initializer [enabled by default]
     {"exp",             dn_exp    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:917:5: warning: (near initialization for ‘dn_dnumber_meta_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:917:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:917:5: warning: (near initialization for ‘dn_dnumber_meta_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:917:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:917:5: error: (near initialization for ‘dn_dnumber_meta_lib[3]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:917:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:917:5: warning: (near initialization for ‘dn_dnumber_meta_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:918:5: warning: braces around scalar initializer [enabled by default]
     {"ln",              dn_ln     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:918:5: warning: (near initialization for ‘dn_dnumber_meta_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:918:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:918:5: warning: (near initialization for ‘dn_dnumber_meta_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:918:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:918:5: error: (near initialization for ‘dn_dnumber_meta_lib[4]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:918:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:918:5: warning: (near initialization for ‘dn_dnumber_meta_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:919:5: warning: braces around scalar initializer [enabled by default]
     {"log10",           dn_log10  },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:919:5: warning: (near initialization for ‘dn_dnumber_meta_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:919:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:919:5: warning: (near initialization for ‘dn_dnumber_meta_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:919:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:919:5: error: (near initialization for ‘dn_dnumber_meta_lib[5]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:919:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:919:5: warning: (near initialization for ‘dn_dnumber_meta_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:920:5: warning: braces around scalar initializer [enabled by default]
     {"abs",             dn_abs    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:920:5: warning: (near initialization for ‘dn_dnumber_meta_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:920:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:920:5: warning: (near initialization for ‘dn_dnumber_meta_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:920:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:920:5: error: (near initialization for ‘dn_dnumber_meta_lib[6]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:920:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:920:5: warning: (near initialization for ‘dn_dnumber_meta_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:921:5: warning: braces around scalar initializer [enabled by default]
     {"minus",           dn_neg    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:921:5: warning: (near initialization for ‘dn_dnumber_meta_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:921:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:921:5: warning: (near initialization for ‘dn_dnumber_meta_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:921:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:921:5: error: (near initialization for ‘dn_dnumber_meta_lib[7]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:921:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:921:5: warning: (near initialization for ‘dn_dnumber_meta_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:922:5: warning: braces around scalar initializer [enabled by default]
     {"normalize",       dn_norm   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:922:5: warning: (near initialization for ‘dn_dnumber_meta_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:922:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:922:5: warning: (near initialization for ‘dn_dnumber_meta_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:922:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:922:5: error: (near initialization for ‘dn_dnumber_meta_lib[8]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:922:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:922:5: warning: (near initialization for ‘dn_dnumber_meta_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:923:5: warning: braces around scalar initializer [enabled by default]
     {"plus",            dn_plus   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:923:5: warning: (near initialization for ‘dn_dnumber_meta_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:923:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:923:5: warning: (near initialization for ‘dn_dnumber_meta_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:923:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:923:5: error: (near initialization for ‘dn_dnumber_meta_lib[9]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:923:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:923:5: warning: (near initialization for ‘dn_dnumber_meta_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:924:5: warning: braces around scalar initializer [enabled by default]
     {"squareroot",      dn_sqrt   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:924:5: warning: (near initialization for ‘dn_dnumber_meta_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:924:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:924:5: warning: (near initialization for ‘dn_dnumber_meta_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:924:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:924:5: error: (near initialization for ‘dn_dnumber_meta_lib[10]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:924:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:924:5: warning: (near initialization for ‘dn_dnumber_meta_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:925:5: warning: braces around scalar initializer [enabled by default]
     {"tointegralvalue", dn_intval },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:925:5: warning: (near initialization for ‘dn_dnumber_meta_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:925:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:925:5: warning: (near initialization for ‘dn_dnumber_meta_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:925:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:925:5: error: (near initialization for ‘dn_dnumber_meta_lib[11]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:925:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:925:5: warning: (near initialization for ‘dn_dnumber_meta_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:926:5: warning: braces around scalar initializer [enabled by default]
     {"invert",          dn_invert },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:926:5: warning: (near initialization for ‘dn_dnumber_meta_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:926:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:926:5: warning: (near initialization for ‘dn_dnumber_meta_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:926:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:926:5: error: (near initialization for ‘dn_dnumber_meta_lib[12]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:926:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:926:5: warning: (near initialization for ‘dn_dnumber_meta_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:927:5: warning: braces around scalar initializer [enabled by default]
     {"logb",            dn_logb   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:927:5: warning: (near initialization for ‘dn_dnumber_meta_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:927:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:927:5: warning: (near initialization for ‘dn_dnumber_meta_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:927:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:927:5: error: (near initialization for ‘dn_dnumber_meta_lib[13]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:927:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:927:5: warning: (near initialization for ‘dn_dnumber_meta_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:928:5: warning: braces around scalar initializer [enabled by default]
     {"tointegralexact", dn_intxct },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:928:5: warning: (near initialization for ‘dn_dnumber_meta_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:928:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:928:5: warning: (near initialization for ‘dn_dnumber_meta_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:928:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:928:5: error: (near initialization for ‘dn_dnumber_meta_lib[14]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:928:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:928:5: warning: (near initialization for ‘dn_dnumber_meta_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:929:5: warning: braces around scalar initializer [enabled by default]
     {"nextminus",       dn_intnmn },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:929:5: warning: (near initialization for ‘dn_dnumber_meta_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:929:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:929:5: warning: (near initialization for ‘dn_dnumber_meta_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:929:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:929:5: error: (near initialization for ‘dn_dnumber_meta_lib[15]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:929:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:929:5: warning: (near initialization for ‘dn_dnumber_meta_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:930:5: warning: braces around scalar initializer [enabled by default]
     {"nextplus",        dn_intnpl },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:930:5: warning: (near initialization for ‘dn_dnumber_meta_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:930:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:930:5: warning: (near initialization for ‘dn_dnumber_meta_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:930:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:930:5: error: (near initialization for ‘dn_dnumber_meta_lib[16]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:930:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:930:5: warning: (near initialization for ‘dn_dnumber_meta_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:932:5: warning: braces around scalar initializer [enabled by default]
     {"copy",            dn_copy       },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:932:5: warning: (near initialization for ‘dn_dnumber_meta_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:932:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:932:5: warning: (near initialization for ‘dn_dnumber_meta_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:932:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:932:5: error: (near initialization for ‘dn_dnumber_meta_lib[17]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:932:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:932:5: warning: (near initialization for ‘dn_dnumber_meta_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:933:5: warning: braces around scalar initializer [enabled by default]
     {"copyabs",         dn_copyabs    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:933:5: warning: (near initialization for ‘dn_dnumber_meta_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:933:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:933:5: warning: (near initialization for ‘dn_dnumber_meta_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:933:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:933:5: error: (near initialization for ‘dn_dnumber_meta_lib[18]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:933:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:933:5: warning: (near initialization for ‘dn_dnumber_meta_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:934:5: warning: braces around scalar initializer [enabled by default]
     {"copynegate",      dn_copynegate },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:934:5: warning: (near initialization for ‘dn_dnumber_meta_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:934:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:934:5: warning: (near initialization for ‘dn_dnumber_meta_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:934:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:934:5: error: (near initialization for ‘dn_dnumber_meta_lib[19]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:934:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:934:5: warning: (near initialization for ‘dn_dnumber_meta_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:935:5: warning: braces around scalar initializer [enabled by default]
     {"copysign",        dn_copysign   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:935:5: warning: (near initialization for ‘dn_dnumber_meta_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:935:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:935:5: warning: (near initialization for ‘dn_dnumber_meta_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:935:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:935:5: error: (near initialization for ‘dn_dnumber_meta_lib[20]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:935:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:935:5: warning: (near initialization for ‘dn_dnumber_meta_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:937:5: warning: braces around scalar initializer [enabled by default]
     {"add",             dn_add    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:937:5: warning: (near initialization for ‘dn_dnumber_meta_lib[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:937:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:937:5: warning: (near initialization for ‘dn_dnumber_meta_lib[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:937:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:937:5: error: (near initialization for ‘dn_dnumber_meta_lib[21]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:937:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:937:5: warning: (near initialization for ‘dn_dnumber_meta_lib[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:938:5: warning: braces around scalar initializer [enabled by default]
     {"divide",          dn_div    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:938:5: warning: (near initialization for ‘dn_dnumber_meta_lib[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:938:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:938:5: warning: (near initialization for ‘dn_dnumber_meta_lib[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:938:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:938:5: error: (near initialization for ‘dn_dnumber_meta_lib[22]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:938:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:938:5: warning: (near initialization for ‘dn_dnumber_meta_lib[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:939:5: warning: braces around scalar initializer [enabled by default]
     {"multiply",        dn_mul    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:939:5: warning: (near initialization for ‘dn_dnumber_meta_lib[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:939:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:939:5: warning: (near initialization for ‘dn_dnumber_meta_lib[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:939:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:939:5: error: (near initialization for ‘dn_dnumber_meta_lib[23]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:939:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:939:5: warning: (near initialization for ‘dn_dnumber_meta_lib[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:940:5: warning: braces around scalar initializer [enabled by default]
     {"power",           dn_pow    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:940:5: warning: (near initialization for ‘dn_dnumber_meta_lib[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:940:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:940:5: warning: (near initialization for ‘dn_dnumber_meta_lib[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:940:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:940:5: error: (near initialization for ‘dn_dnumber_meta_lib[24]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:940:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:940:5: warning: (near initialization for ‘dn_dnumber_meta_lib[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:941:5: warning: braces around scalar initializer [enabled by default]
     {"subtract",        dn_sub    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:941:5: warning: (near initialization for ‘dn_dnumber_meta_lib[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:941:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:941:5: warning: (near initialization for ‘dn_dnumber_meta_lib[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:941:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:941:5: error: (near initialization for ‘dn_dnumber_meta_lib[25]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:941:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:941:5: warning: (near initialization for ‘dn_dnumber_meta_lib[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:943:5: warning: braces around scalar initializer [enabled by default]
     {"compare",         dn_compare       },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:943:5: warning: (near initialization for ‘dn_dnumber_meta_lib[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:943:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:943:5: warning: (near initialization for ‘dn_dnumber_meta_lib[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:943:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:943:5: error: (near initialization for ‘dn_dnumber_meta_lib[26]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:943:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:943:5: warning: (near initialization for ‘dn_dnumber_meta_lib[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:944:5: warning: braces around scalar initializer [enabled by default]
     {"comparetotal",    dn_comparetotal  },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:944:5: warning: (near initialization for ‘dn_dnumber_meta_lib[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:944:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:944:5: warning: (near initialization for ‘dn_dnumber_meta_lib[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:944:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:944:5: error: (near initialization for ‘dn_dnumber_meta_lib[27]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:944:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:944:5: warning: (near initialization for ‘dn_dnumber_meta_lib[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:945:5: warning: braces around scalar initializer [enabled by default]
     {"divideinteger",   dn_divideinteger },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:945:5: warning: (near initialization for ‘dn_dnumber_meta_lib[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:945:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:945:5: warning: (near initialization for ‘dn_dnumber_meta_lib[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:945:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:945:5: error: (near initialization for ‘dn_dnumber_meta_lib[28]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:945:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:945:5: warning: (near initialization for ‘dn_dnumber_meta_lib[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:946:5: warning: braces around scalar initializer [enabled by default]
     {"max",             dn_max           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:946:5: warning: (near initialization for ‘dn_dnumber_meta_lib[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:946:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:946:5: warning: (near initialization for ‘dn_dnumber_meta_lib[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:946:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:946:5: error: (near initialization for ‘dn_dnumber_meta_lib[29]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:946:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:946:5: warning: (near initialization for ‘dn_dnumber_meta_lib[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:947:5: warning: braces around scalar initializer [enabled by default]
     {"min",             dn_min           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:947:5: warning: (near initialization for ‘dn_dnumber_meta_lib[30]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:947:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:947:5: warning: (near initialization for ‘dn_dnumber_meta_lib[30]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:947:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:947:5: error: (near initialization for ‘dn_dnumber_meta_lib[30]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:947:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:947:5: warning: (near initialization for ‘dn_dnumber_meta_lib[30]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:948:5: warning: braces around scalar initializer [enabled by default]
     {"quantize",        dn_quantize      },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:948:5: warning: (near initialization for ‘dn_dnumber_meta_lib[31]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:948:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:948:5: warning: (near initialization for ‘dn_dnumber_meta_lib[31]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:948:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:948:5: error: (near initialization for ‘dn_dnumber_meta_lib[31]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:948:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:948:5: warning: (near initialization for ‘dn_dnumber_meta_lib[31]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:949:5: warning: braces around scalar initializer [enabled by default]
     {"remainder",       dn_remainder     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:949:5: warning: (near initialization for ‘dn_dnumber_meta_lib[32]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:949:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:949:5: warning: (near initialization for ‘dn_dnumber_meta_lib[32]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:949:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:949:5: error: (near initialization for ‘dn_dnumber_meta_lib[32]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:949:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:949:5: warning: (near initialization for ‘dn_dnumber_meta_lib[32]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:950:5: warning: braces around scalar initializer [enabled by default]
     {"remaindernear",   dn_remaindernear },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:950:5: warning: (near initialization for ‘dn_dnumber_meta_lib[33]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:950:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:950:5: warning: (near initialization for ‘dn_dnumber_meta_lib[33]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:950:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:950:5: error: (near initialization for ‘dn_dnumber_meta_lib[33]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:950:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:950:5: warning: (near initialization for ‘dn_dnumber_meta_lib[33]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:951:5: warning: braces around scalar initializer [enabled by default]
     {"rescale",         dn_rescale       },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:951:5: warning: (near initialization for ‘dn_dnumber_meta_lib[34]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:951:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:951:5: warning: (near initialization for ‘dn_dnumber_meta_lib[34]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:951:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:951:5: error: (near initialization for ‘dn_dnumber_meta_lib[34]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:951:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:951:5: warning: (near initialization for ‘dn_dnumber_meta_lib[34]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:952:5: warning: braces around scalar initializer [enabled by default]
     {"samequantum",     dn_samequantum   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:952:5: warning: (near initialization for ‘dn_dnumber_meta_lib[35]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:952:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:952:5: warning: (near initialization for ‘dn_dnumber_meta_lib[35]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:952:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:952:5: error: (near initialization for ‘dn_dnumber_meta_lib[35]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:952:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:952:5: warning: (near initialization for ‘dn_dnumber_meta_lib[35]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:954:5: warning: braces around scalar initializer [enabled by default]
     {"land",            dn_and           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:954:5: warning: (near initialization for ‘dn_dnumber_meta_lib[36]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:954:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:954:5: warning: (near initialization for ‘dn_dnumber_meta_lib[36]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:954:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:954:5: error: (near initialization for ‘dn_dnumber_meta_lib[36]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:954:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:954:5: warning: (near initialization for ‘dn_dnumber_meta_lib[36]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:955:5: warning: braces around scalar initializer [enabled by default]
     {"comparetotalmag", dn_comparetotalmag },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:955:5: warning: (near initialization for ‘dn_dnumber_meta_lib[37]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:955:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:955:5: warning: (near initialization for ‘dn_dnumber_meta_lib[37]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:955:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:955:5: error: (near initialization for ‘dn_dnumber_meta_lib[37]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:955:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:955:5: warning: (near initialization for ‘dn_dnumber_meta_lib[37]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:956:5: warning: braces around scalar initializer [enabled by default]
     {"maxmag",          dn_maxmag        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:956:5: warning: (near initialization for ‘dn_dnumber_meta_lib[38]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:956:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:956:5: warning: (near initialization for ‘dn_dnumber_meta_lib[38]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:956:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:956:5: error: (near initialization for ‘dn_dnumber_meta_lib[38]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:956:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:956:5: warning: (near initialization for ‘dn_dnumber_meta_lib[38]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:957:5: warning: braces around scalar initializer [enabled by default]
     {"minmag",          dn_minmag        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:957:5: warning: (near initialization for ‘dn_dnumber_meta_lib[39]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:957:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:957:5: warning: (near initialization for ‘dn_dnumber_meta_lib[39]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:957:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:957:5: error: (near initialization for ‘dn_dnumber_meta_lib[39]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:957:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:957:5: warning: (near initialization for ‘dn_dnumber_meta_lib[39]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:958:5: warning: braces around scalar initializer [enabled by default]
     {"nexttoward",      dn_nexttoward    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:958:5: warning: (near initialization for ‘dn_dnumber_meta_lib[40]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:958:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:958:5: warning: (near initialization for ‘dn_dnumber_meta_lib[40]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:958:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:958:5: error: (near initialization for ‘dn_dnumber_meta_lib[40]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:958:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:958:5: warning: (near initialization for ‘dn_dnumber_meta_lib[40]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:959:5: warning: braces around scalar initializer [enabled by default]
     {"lor",             dn_or            },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:959:5: warning: (near initialization for ‘dn_dnumber_meta_lib[41]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:959:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:959:5: warning: (near initialization for ‘dn_dnumber_meta_lib[41]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:959:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:959:5: error: (near initialization for ‘dn_dnumber_meta_lib[41]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:959:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:959:5: warning: (near initialization for ‘dn_dnumber_meta_lib[41]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:960:5: warning: braces around scalar initializer [enabled by default]
     {"rotate",          dn_rotate        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:960:5: warning: (near initialization for ‘dn_dnumber_meta_lib[42]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:960:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:960:5: warning: (near initialization for ‘dn_dnumber_meta_lib[42]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:960:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:960:5: error: (near initialization for ‘dn_dnumber_meta_lib[42]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:960:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:960:5: warning: (near initialization for ‘dn_dnumber_meta_lib[42]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:961:5: warning: braces around scalar initializer [enabled by default]
     {"scaleb",          dn_scaleb        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:961:5: warning: (near initialization for ‘dn_dnumber_meta_lib[43]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:961:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:961:5: warning: (near initialization for ‘dn_dnumber_meta_lib[43]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:961:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:961:5: error: (near initialization for ‘dn_dnumber_meta_lib[43]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:961:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:961:5: warning: (near initialization for ‘dn_dnumber_meta_lib[43]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:962:5: warning: braces around scalar initializer [enabled by default]
     {"shift",           dn_shift         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:962:5: warning: (near initialization for ‘dn_dnumber_meta_lib[44]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:962:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:962:5: warning: (near initialization for ‘dn_dnumber_meta_lib[44]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:962:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:962:5: error: (near initialization for ‘dn_dnumber_meta_lib[44]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:962:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:962:5: warning: (near initialization for ‘dn_dnumber_meta_lib[44]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:963:5: warning: braces around scalar initializer [enabled by default]
     {"xor",             dn_xor           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:963:5: warning: (near initialization for ‘dn_dnumber_meta_lib[45]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:963:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:963:5: warning: (near initialization for ‘dn_dnumber_meta_lib[45]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:963:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:963:5: error: (near initialization for ‘dn_dnumber_meta_lib[45]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:963:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:963:5: warning: (near initialization for ‘dn_dnumber_meta_lib[45]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:965:5: warning: braces around scalar initializer [enabled by default]
     {"fma",             dn_fma           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:965:5: warning: (near initialization for ‘dn_dnumber_meta_lib[46]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:965:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:965:5: warning: (near initialization for ‘dn_dnumber_meta_lib[46]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:965:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:965:5: error: (near initialization for ‘dn_dnumber_meta_lib[46]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:965:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:965:5: warning: (near initialization for ‘dn_dnumber_meta_lib[46]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:967:5: warning: braces around scalar initializer [enabled by default]
     {"mod",             dn_mod           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:967:5: warning: (near initialization for ‘dn_dnumber_meta_lib[47]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:967:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:967:5: warning: (near initialization for ‘dn_dnumber_meta_lib[47]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:967:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:967:5: error: (near initialization for ‘dn_dnumber_meta_lib[47]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:967:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:967:5: warning: (near initialization for ‘dn_dnumber_meta_lib[47]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:968:5: warning: braces around scalar initializer [enabled by default]
     {"floor",           dn_floor         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:968:5: warning: (near initialization for ‘dn_dnumber_meta_lib[48]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:968:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:968:5: warning: (near initialization for ‘dn_dnumber_meta_lib[48]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:968:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:968:5: error: (near initialization for ‘dn_dnumber_meta_lib[48]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:968:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:968:5: warning: (near initialization for ‘dn_dnumber_meta_lib[48]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:970:5: warning: braces around scalar initializer [enabled by default]
     {"iszero",          dn_iszero        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:970:5: warning: (near initialization for ‘dn_dnumber_meta_lib[49]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:970:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:970:5: warning: (near initialization for ‘dn_dnumber_meta_lib[49]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:970:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:970:5: error: (near initialization for ‘dn_dnumber_meta_lib[49]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:970:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:970:5: warning: (near initialization for ‘dn_dnumber_meta_lib[49]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:971:5: warning: braces around scalar initializer [enabled by default]
     {"isnegative",      dn_isneg         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:971:5: warning: (near initialization for ‘dn_dnumber_meta_lib[50]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:971:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:971:5: warning: (near initialization for ‘dn_dnumber_meta_lib[50]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:971:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:971:5: error: (near initialization for ‘dn_dnumber_meta_lib[50]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:971:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:971:5: warning: (near initialization for ‘dn_dnumber_meta_lib[50]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:972:5: warning: braces around scalar initializer [enabled by default]
     {"isnan",           dn_isnan         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:972:5: warning: (near initialization for ‘dn_dnumber_meta_lib[51]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:972:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:972:5: warning: (near initialization for ‘dn_dnumber_meta_lib[51]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:972:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:972:5: error: (near initialization for ‘dn_dnumber_meta_lib[51]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:972:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:972:5: warning: (near initialization for ‘dn_dnumber_meta_lib[51]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:973:5: warning: braces around scalar initializer [enabled by default]
     {"isqnan",          dn_isqnan        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:973:5: warning: (near initialization for ‘dn_dnumber_meta_lib[52]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:973:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:973:5: warning: (near initialization for ‘dn_dnumber_meta_lib[52]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:973:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:973:5: error: (near initialization for ‘dn_dnumber_meta_lib[52]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:973:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:973:5: warning: (near initialization for ‘dn_dnumber_meta_lib[52]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:974:5: warning: braces around scalar initializer [enabled by default]
     {"issnan",          dn_issnan        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:974:5: warning: (near initialization for ‘dn_dnumber_meta_lib[53]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:974:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:974:5: warning: (near initialization for ‘dn_dnumber_meta_lib[53]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:974:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:974:5: error: (near initialization for ‘dn_dnumber_meta_lib[53]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:974:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:974:5: warning: (near initialization for ‘dn_dnumber_meta_lib[53]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:975:5: warning: braces around scalar initializer [enabled by default]
     {"isinfinite",      dn_isinf         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:975:5: warning: (near initialization for ‘dn_dnumber_meta_lib[54]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:975:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:975:5: warning: (near initialization for ‘dn_dnumber_meta_lib[54]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:975:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:975:5: error: (near initialization for ‘dn_dnumber_meta_lib[54]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:975:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:975:5: warning: (near initialization for ‘dn_dnumber_meta_lib[54]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:976:5: warning: braces around scalar initializer [enabled by default]
     {"isfinite",        dn_isfini        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:976:5: warning: (near initialization for ‘dn_dnumber_meta_lib[55]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:976:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:976:5: warning: (near initialization for ‘dn_dnumber_meta_lib[55]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:976:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:976:5: error: (near initialization for ‘dn_dnumber_meta_lib[55]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:976:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:976:5: warning: (near initialization for ‘dn_dnumber_meta_lib[55]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:977:5: warning: braces around scalar initializer [enabled by default]
     {"iscanonical",     dn_iscncl        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:977:5: warning: (near initialization for ‘dn_dnumber_meta_lib[56]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:977:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:977:5: warning: (near initialization for ‘dn_dnumber_meta_lib[56]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:977:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:977:5: error: (near initialization for ‘dn_dnumber_meta_lib[56]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:977:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:977:5: warning: (near initialization for ‘dn_dnumber_meta_lib[56]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:978:5: warning: braces around scalar initializer [enabled by default]
     {"isspecial",       dn_isspec        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:978:5: warning: (near initialization for ‘dn_dnumber_meta_lib[57]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:978:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:978:5: warning: (near initialization for ‘dn_dnumber_meta_lib[57]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:978:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:978:5: error: (near initialization for ‘dn_dnumber_meta_lib[57]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:978:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:978:5: warning: (near initialization for ‘dn_dnumber_meta_lib[57]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:979:5: warning: braces around scalar initializer [enabled by default]
     {"isnormal",        dn_isnorm        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:979:5: warning: (near initialization for ‘dn_dnumber_meta_lib[58]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:979:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:979:5: warning: (near initialization for ‘dn_dnumber_meta_lib[58]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:979:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:979:5: error: (near initialization for ‘dn_dnumber_meta_lib[58]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:979:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:979:5: warning: (near initialization for ‘dn_dnumber_meta_lib[58]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:980:5: warning: braces around scalar initializer [enabled by default]
     {"issubnormal",     dn_issubn        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:980:5: warning: (near initialization for ‘dn_dnumber_meta_lib[59]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:980:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:980:5: warning: (near initialization for ‘dn_dnumber_meta_lib[59]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:980:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:980:5: error: (near initialization for ‘dn_dnumber_meta_lib[59]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:980:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:980:5: warning: (near initialization for ‘dn_dnumber_meta_lib[59]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:982:5: warning: braces around scalar initializer [enabled by default]
     {"radix",           dn_radix         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:982:5: warning: (near initialization for ‘dn_dnumber_meta_lib[60]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:982:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:982:5: warning: (near initialization for ‘dn_dnumber_meta_lib[60]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:982:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:982:5: error: (near initialization for ‘dn_dnumber_meta_lib[60]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:982:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:982:5: warning: (near initialization for ‘dn_dnumber_meta_lib[60]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:983:5: warning: braces around scalar initializer [enabled by default]
     {"class",           dn_class         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:983:5: warning: (near initialization for ‘dn_dnumber_meta_lib[61]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:983:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:983:5: warning: (near initialization for ‘dn_dnumber_meta_lib[61]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:983:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:983:5: error: (near initialization for ‘dn_dnumber_meta_lib[61]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:983:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:983:5: warning: (near initialization for ‘dn_dnumber_meta_lib[61]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:984:5: warning: braces around scalar initializer [enabled by default]
     {"classtostring",   dn_classtostring },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:984:5: warning: (near initialization for ‘dn_dnumber_meta_lib[62]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:984:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:984:5: warning: (near initialization for ‘dn_dnumber_meta_lib[62]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:984:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:984:5: error: (near initialization for ‘dn_dnumber_meta_lib[62]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:984:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:984:5: warning: (near initialization for ‘dn_dnumber_meta_lib[62]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:985:5: warning: braces around scalar initializer [enabled by default]
     {"classasstring",   dn_classasstring },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:985:5: warning: (near initialization for ‘dn_dnumber_meta_lib[63]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:985:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:985:5: warning: (near initialization for ‘dn_dnumber_meta_lib[63]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:985:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:985:5: error: (near initialization for ‘dn_dnumber_meta_lib[63]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:985:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:985:5: warning: (near initialization for ‘dn_dnumber_meta_lib[63]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:987:5: warning: braces around scalar initializer [enabled by default]
     {"trim",            dn_trim          },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:987:5: warning: (near initialization for ‘dn_dnumber_meta_lib[64]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:987:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:987:5: warning: (near initialization for ‘dn_dnumber_meta_lib[64]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:987:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:987:5: error: (near initialization for ‘dn_dnumber_meta_lib[64]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:987:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:987:5: warning: (near initialization for ‘dn_dnumber_meta_lib[64]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:989:5: warning: braces around scalar initializer [enabled by default]
     {"tostring",        dn_string        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:989:5: warning: (near initialization for ‘dn_dnumber_meta_lib[65]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:989:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:989:5: warning: (near initialization for ‘dn_dnumber_meta_lib[65]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:989:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:989:5: error: (near initialization for ‘dn_dnumber_meta_lib[65]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:989:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:989:5: warning: (near initialization for ‘dn_dnumber_meta_lib[65]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:990:5: warning: braces around scalar initializer [enabled by default]
     {"toengstring",     dn_engstring     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:990:5: warning: (near initialization for ‘dn_dnumber_meta_lib[66]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:990:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:990:5: warning: (near initialization for ‘dn_dnumber_meta_lib[66]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:990:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:990:5: error: (near initialization for ‘dn_dnumber_meta_lib[66]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:990:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:990:5: warning: (near initialization for ‘dn_dnumber_meta_lib[66]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:992:5: warning: braces around scalar initializer [enabled by default]
     { "__unm",      dn_neg    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:992:5: warning: (near initialization for ‘dn_dnumber_meta_lib[67]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:992:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:992:5: warning: (near initialization for ‘dn_dnumber_meta_lib[67]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:992:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:992:5: error: (near initialization for ‘dn_dnumber_meta_lib[67]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:992:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:992:5: warning: (near initialization for ‘dn_dnumber_meta_lib[67]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:993:5: warning: braces around scalar initializer [enabled by default]
     { "__add",      dn_add    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:993:5: warning: (near initialization for ‘dn_dnumber_meta_lib[68]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:993:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:993:5: warning: (near initialization for ‘dn_dnumber_meta_lib[68]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:993:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:993:5: error: (near initialization for ‘dn_dnumber_meta_lib[68]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:993:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:993:5: warning: (near initialization for ‘dn_dnumber_meta_lib[68]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:994:5: warning: braces around scalar initializer [enabled by default]
     { "__sub",      dn_sub    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:994:5: warning: (near initialization for ‘dn_dnumber_meta_lib[69]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:994:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:994:5: warning: (near initialization for ‘dn_dnumber_meta_lib[69]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:994:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:994:5: error: (near initialization for ‘dn_dnumber_meta_lib[69]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:994:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:994:5: warning: (near initialization for ‘dn_dnumber_meta_lib[69]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:995:5: warning: braces around scalar initializer [enabled by default]
     { "__mul",      dn_mul    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:995:5: warning: (near initialization for ‘dn_dnumber_meta_lib[70]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:995:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:995:5: warning: (near initialization for ‘dn_dnumber_meta_lib[70]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:995:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:995:5: error: (near initialization for ‘dn_dnumber_meta_lib[70]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:995:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:995:5: warning: (near initialization for ‘dn_dnumber_meta_lib[70]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:996:5: warning: braces around scalar initializer [enabled by default]
     { "__div",      dn_div    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:996:5: warning: (near initialization for ‘dn_dnumber_meta_lib[71]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:996:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:996:5: warning: (near initialization for ‘dn_dnumber_meta_lib[71]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:996:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:996:5: error: (near initialization for ‘dn_dnumber_meta_lib[71]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:996:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:996:5: warning: (near initialization for ‘dn_dnumber_meta_lib[71]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:997:5: warning: braces around scalar initializer [enabled by default]
     { "__pow",      dn_pow    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:997:5: warning: (near initialization for ‘dn_dnumber_meta_lib[72]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:997:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:997:5: warning: (near initialization for ‘dn_dnumber_meta_lib[72]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:997:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:997:5: error: (near initialization for ‘dn_dnumber_meta_lib[72]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:997:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:997:5: warning: (near initialization for ‘dn_dnumber_meta_lib[72]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:998:5: warning: braces around scalar initializer [enabled by default]
     { "__mod",      dn_mod    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:998:5: warning: (near initialization for ‘dn_dnumber_meta_lib[73]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:998:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:998:5: warning: (near initialization for ‘dn_dnumber_meta_lib[73]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:998:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:998:5: error: (near initialization for ‘dn_dnumber_meta_lib[73]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:998:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:998:5: warning: (near initialization for ‘dn_dnumber_meta_lib[73]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:999:5: warning: braces around scalar initializer [enabled by default]
     { "__eq",       dn_eq     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:999:5: warning: (near initialization for ‘dn_dnumber_meta_lib[74]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:999:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:999:5: warning: (near initialization for ‘dn_dnumber_meta_lib[74]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:999:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:999:5: error: (near initialization for ‘dn_dnumber_meta_lib[74]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:999:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:999:5: warning: (near initialization for ‘dn_dnumber_meta_lib[74]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1000:5: warning: braces around scalar initializer [enabled by default]
     { "__lt",       dn_lt     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1000:5: warning: (near initialization for ‘dn_dnumber_meta_lib[75]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1000:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1000:5: warning: (near initialization for ‘dn_dnumber_meta_lib[75]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1000:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1000:5: error: (near initialization for ‘dn_dnumber_meta_lib[75]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1000:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1000:5: warning: (near initialization for ‘dn_dnumber_meta_lib[75]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1001:5: warning: braces around scalar initializer [enabled by default]
     { "__le",       dn_le     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1001:5: warning: (near initialization for ‘dn_dnumber_meta_lib[76]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1001:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1001:5: warning: (near initialization for ‘dn_dnumber_meta_lib[76]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1001:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1001:5: error: (near initialization for ‘dn_dnumber_meta_lib[76]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1001:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1001:5: warning: (near initialization for ‘dn_dnumber_meta_lib[76]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1002:5: warning: braces around scalar initializer [enabled by default]
     { "__tostring", dn_string },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1002:5: warning: (near initialization for ‘dn_dnumber_meta_lib[77]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1002:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1002:5: warning: (near initialization for ‘dn_dnumber_meta_lib[77]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1002:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1002:5: error: (near initialization for ‘dn_dnumber_meta_lib[77]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1002:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1002:5: warning: (near initialization for ‘dn_dnumber_meta_lib[77]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1003:5: warning: braces around scalar initializer [enabled by default]
     { "__concat",   dn_concat },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1003:5: warning: (near initialization for ‘dn_dnumber_meta_lib[78]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1003:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1003:5: warning: (near initialization for ‘dn_dnumber_meta_lib[78]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1003:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1003:5: error: (near initialization for ‘dn_dnumber_meta_lib[78]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1003:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1003:5: warning: (near initialization for ‘dn_dnumber_meta_lib[78]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1005:5: warning: braces around scalar initializer [enabled by default]
     { NULL,         NULL      }
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1005:5: warning: (near initialization for ‘dn_dnumber_meta_lib[79]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1005:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1005:5: warning: (near initialization for ‘dn_dnumber_meta_lib[79]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1005:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1005:5: warning: (near initialization for ‘dn_dnumber_meta_lib[79]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1008:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg dn_context_meta_lib[] =
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1010:5: warning: braces around scalar initializer [enabled by default]
     {"setdefault",       dn_ctx_set_default   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1010:5: warning: (near initialization for ‘dn_context_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1010:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1010:5: warning: (near initialization for ‘dn_context_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1010:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1010:5: error: (near initialization for ‘dn_context_meta_lib[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1010:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1010:5: warning: (near initialization for ‘dn_context_meta_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1011:5: warning: braces around scalar initializer [enabled by default]
     {"getstatus",        dn_ctx_get_status    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1011:5: warning: (near initialization for ‘dn_context_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1011:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1011:5: warning: (near initialization for ‘dn_context_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1011:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1011:5: error: (near initialization for ‘dn_context_meta_lib[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1011:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1011:5: warning: (near initialization for ‘dn_context_meta_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1012:5: warning: braces around scalar initializer [enabled by default]
     {"setstatus",        dn_ctx_set_status    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1012:5: warning: (near initialization for ‘dn_context_meta_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1012:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1012:5: warning: (near initialization for ‘dn_context_meta_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1012:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1012:5: error: (near initialization for ‘dn_context_meta_lib[2]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1012:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1012:5: warning: (near initialization for ‘dn_context_meta_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1013:5: warning: braces around scalar initializer [enabled by default]
     {"getdigits",        dn_ctx_get_digits    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1013:5: warning: (near initialization for ‘dn_context_meta_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1013:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1013:5: warning: (near initialization for ‘dn_context_meta_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1013:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1013:5: error: (near initialization for ‘dn_context_meta_lib[3]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1013:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1013:5: warning: (near initialization for ‘dn_context_meta_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1014:5: warning: braces around scalar initializer [enabled by default]
     {"setdigits",        dn_ctx_set_digits    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1014:5: warning: (near initialization for ‘dn_context_meta_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1014:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1014:5: warning: (near initialization for ‘dn_context_meta_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1014:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1014:5: error: (near initialization for ‘dn_context_meta_lib[4]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1014:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1014:5: warning: (near initialization for ‘dn_context_meta_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1015:5: warning: braces around scalar initializer [enabled by default]
     {"getemax",          dn_ctx_get_emax      },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1015:5: warning: (near initialization for ‘dn_context_meta_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1015:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1015:5: warning: (near initialization for ‘dn_context_meta_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1015:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1015:5: error: (near initialization for ‘dn_context_meta_lib[5]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1015:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1015:5: warning: (near initialization for ‘dn_context_meta_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1016:5: warning: braces around scalar initializer [enabled by default]
     {"setemax",          dn_ctx_set_emax      },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1016:5: warning: (near initialization for ‘dn_context_meta_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1016:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1016:5: warning: (near initialization for ‘dn_context_meta_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1016:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1016:5: error: (near initialization for ‘dn_context_meta_lib[6]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1016:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1016:5: warning: (near initialization for ‘dn_context_meta_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1017:5: warning: braces around scalar initializer [enabled by default]
     {"getemin",          dn_ctx_get_emin      },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1017:5: warning: (near initialization for ‘dn_context_meta_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1017:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1017:5: warning: (near initialization for ‘dn_context_meta_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1017:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1017:5: error: (near initialization for ‘dn_context_meta_lib[7]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1017:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1017:5: warning: (near initialization for ‘dn_context_meta_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1018:5: warning: braces around scalar initializer [enabled by default]
     {"setemin",          dn_ctx_set_emin      },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1018:5: warning: (near initialization for ‘dn_context_meta_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1018:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1018:5: warning: (near initialization for ‘dn_context_meta_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1018:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1018:5: error: (near initialization for ‘dn_context_meta_lib[8]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1018:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1018:5: warning: (near initialization for ‘dn_context_meta_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1019:5: warning: braces around scalar initializer [enabled by default]
     {"getround",         dn_ctx_get_round     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1019:5: warning: (near initialization for ‘dn_context_meta_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1019:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1019:5: warning: (near initialization for ‘dn_context_meta_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1019:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1019:5: error: (near initialization for ‘dn_context_meta_lib[9]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1019:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1019:5: warning: (near initialization for ‘dn_context_meta_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1020:5: warning: braces around scalar initializer [enabled by default]
     {"setround",         dn_ctx_set_round     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1020:5: warning: (near initialization for ‘dn_context_meta_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1020:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1020:5: warning: (near initialization for ‘dn_context_meta_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1020:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1020:5: error: (near initialization for ‘dn_context_meta_lib[10]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1020:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1020:5: warning: (near initialization for ‘dn_context_meta_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1021:5: warning: braces around scalar initializer [enabled by default]
     {"gettraps",         dn_ctx_get_traps     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1021:5: warning: (near initialization for ‘dn_context_meta_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1021:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1021:5: warning: (near initialization for ‘dn_context_meta_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1021:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1021:5: error: (near initialization for ‘dn_context_meta_lib[11]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1021:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1021:5: warning: (near initialization for ‘dn_context_meta_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1022:5: warning: braces around scalar initializer [enabled by default]
     {"settraps",         dn_ctx_set_traps     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1022:5: warning: (near initialization for ‘dn_context_meta_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1022:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1022:5: warning: (near initialization for ‘dn_context_meta_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1022:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1022:5: error: (near initialization for ‘dn_context_meta_lib[12]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1022:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1022:5: warning: (near initialization for ‘dn_context_meta_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1023:5: warning: braces around scalar initializer [enabled by default]
     {"getclamp",         dn_ctx_get_clamp     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1023:5: warning: (near initialization for ‘dn_context_meta_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1023:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1023:5: warning: (near initialization for ‘dn_context_meta_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1023:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1023:5: error: (near initialization for ‘dn_context_meta_lib[13]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1023:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1023:5: warning: (near initialization for ‘dn_context_meta_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1024:5: warning: braces around scalar initializer [enabled by default]
     {"setclamp",         dn_ctx_set_clamp     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1024:5: warning: (near initialization for ‘dn_context_meta_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1024:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1024:5: warning: (near initialization for ‘dn_context_meta_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1024:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1024:5: error: (near initialization for ‘dn_context_meta_lib[14]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1024:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1024:5: warning: (near initialization for ‘dn_context_meta_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1029:5: warning: braces around scalar initializer [enabled by default]
     {"getstatusstring",  dn_ctx_get_status_s  },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1029:5: warning: (near initialization for ‘dn_context_meta_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1029:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1029:5: warning: (near initialization for ‘dn_context_meta_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1029:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1029:5: error: (near initialization for ‘dn_context_meta_lib[15]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1029:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1029:5: warning: (near initialization for ‘dn_context_meta_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1030:5: warning: braces around scalar initializer [enabled by default]
     {"setstatusstring",  dn_ctx_set_status_s  },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1030:5: warning: (near initialization for ‘dn_context_meta_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1030:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1030:5: warning: (near initialization for ‘dn_context_meta_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1030:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1030:5: error: (near initialization for ‘dn_context_meta_lib[16]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1030:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1030:5: warning: (near initialization for ‘dn_context_meta_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1031:5: warning: braces around scalar initializer [enabled by default]
     {"duplicate",        dn_ctx_dup           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1031:5: warning: (near initialization for ‘dn_context_meta_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1031:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1031:5: warning: (near initialization for ‘dn_context_meta_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1031:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1031:5: error: (near initialization for ‘dn_context_meta_lib[17]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1031:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1031:5: warning: (near initialization for ‘dn_context_meta_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1032:5: warning: braces around scalar initializer [enabled by default]
     {"setcontext",       dn_set_context       },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1032:5: warning: (near initialization for ‘dn_context_meta_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1032:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1032:5: warning: (near initialization for ‘dn_context_meta_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1032:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1032:5: error: (near initialization for ‘dn_context_meta_lib[18]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1032:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1032:5: warning: (near initialization for ‘dn_context_meta_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1033:5: warning: braces around scalar initializer [enabled by default]
     {"__tostring",       dn_ctx_tostring      },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1033:5: warning: (near initialization for ‘dn_context_meta_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1033:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1033:5: warning: (near initialization for ‘dn_context_meta_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1033:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1033:5: error: (near initialization for ‘dn_context_meta_lib[19]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1033:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1033:5: warning: (near initialization for ‘dn_context_meta_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1035:5: warning: braces around scalar initializer [enabled by default]
     {NULL, NULL}
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1035:5: warning: (near initialization for ‘dn_context_meta_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1035:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1035:5: warning: (near initialization for ‘dn_context_meta_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1035:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1035:5: warning: (near initialization for ‘dn_context_meta_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1038:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg dn_lib[] =
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1040:5: warning: braces around scalar initializer [enabled by default]
     {"eq",              dn_eq     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1040:5: warning: (near initialization for ‘dn_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1040:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1040:5: warning: (near initialization for ‘dn_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1040:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1040:5: error: (near initialization for ‘dn_lib[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1040:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1040:5: warning: (near initialization for ‘dn_lib[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1041:5: warning: braces around scalar initializer [enabled by default]
     {"lt",              dn_lt     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1041:5: warning: (near initialization for ‘dn_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1041:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1041:5: warning: (near initialization for ‘dn_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1041:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1041:5: error: (near initialization for ‘dn_lib[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1041:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1041:5: warning: (near initialization for ‘dn_lib[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1042:5: warning: braces around scalar initializer [enabled by default]
     {"le",              dn_le     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1042:5: warning: (near initialization for ‘dn_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1042:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1042:5: warning: (near initialization for ‘dn_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1042:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1042:5: error: (near initialization for ‘dn_lib[2]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1042:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1042:5: warning: (near initialization for ‘dn_lib[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1044:5: warning: braces around scalar initializer [enabled by default]
     {"exp",             dn_exp    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1044:5: warning: (near initialization for ‘dn_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1044:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1044:5: warning: (near initialization for ‘dn_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1044:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1044:5: error: (near initialization for ‘dn_lib[3]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1044:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1044:5: warning: (near initialization for ‘dn_lib[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1045:5: warning: braces around scalar initializer [enabled by default]
     {"ln",              dn_ln     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1045:5: warning: (near initialization for ‘dn_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1045:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1045:5: warning: (near initialization for ‘dn_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1045:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1045:5: error: (near initialization for ‘dn_lib[4]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1045:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1045:5: warning: (near initialization for ‘dn_lib[4]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1046:5: warning: braces around scalar initializer [enabled by default]
     {"log10",           dn_log10  },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1046:5: warning: (near initialization for ‘dn_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1046:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1046:5: warning: (near initialization for ‘dn_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1046:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1046:5: error: (near initialization for ‘dn_lib[5]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1046:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1046:5: warning: (near initialization for ‘dn_lib[5]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1047:5: warning: braces around scalar initializer [enabled by default]
     {"abs",             dn_abs    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1047:5: warning: (near initialization for ‘dn_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1047:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1047:5: warning: (near initialization for ‘dn_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1047:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1047:5: error: (near initialization for ‘dn_lib[6]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1047:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1047:5: warning: (near initialization for ‘dn_lib[6]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1048:5: warning: braces around scalar initializer [enabled by default]
     {"minus",           dn_neg    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1048:5: warning: (near initialization for ‘dn_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1048:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1048:5: warning: (near initialization for ‘dn_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1048:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1048:5: error: (near initialization for ‘dn_lib[7]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1048:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1048:5: warning: (near initialization for ‘dn_lib[7]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1049:5: warning: braces around scalar initializer [enabled by default]
     {"normalize",       dn_norm   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1049:5: warning: (near initialization for ‘dn_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1049:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1049:5: warning: (near initialization for ‘dn_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1049:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1049:5: error: (near initialization for ‘dn_lib[8]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1049:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1049:5: warning: (near initialization for ‘dn_lib[8]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1050:5: warning: braces around scalar initializer [enabled by default]
     {"plus",            dn_plus   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1050:5: warning: (near initialization for ‘dn_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1050:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1050:5: warning: (near initialization for ‘dn_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1050:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1050:5: error: (near initialization for ‘dn_lib[9]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1050:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1050:5: warning: (near initialization for ‘dn_lib[9]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1051:5: warning: braces around scalar initializer [enabled by default]
     {"squareroot",      dn_sqrt   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1051:5: warning: (near initialization for ‘dn_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1051:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1051:5: warning: (near initialization for ‘dn_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1051:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1051:5: error: (near initialization for ‘dn_lib[10]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1051:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1051:5: warning: (near initialization for ‘dn_lib[10]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1052:5: warning: braces around scalar initializer [enabled by default]
     {"tointegralvalue", dn_intval },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1052:5: warning: (near initialization for ‘dn_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1052:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1052:5: warning: (near initialization for ‘dn_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1052:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1052:5: error: (near initialization for ‘dn_lib[11]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1052:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1052:5: warning: (near initialization for ‘dn_lib[11]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1053:5: warning: braces around scalar initializer [enabled by default]
     {"invert",          dn_invert },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1053:5: warning: (near initialization for ‘dn_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1053:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1053:5: warning: (near initialization for ‘dn_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1053:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1053:5: error: (near initialization for ‘dn_lib[12]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1053:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1053:5: warning: (near initialization for ‘dn_lib[12]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1054:5: warning: braces around scalar initializer [enabled by default]
     {"logb",            dn_logb   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1054:5: warning: (near initialization for ‘dn_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1054:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1054:5: warning: (near initialization for ‘dn_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1054:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1054:5: error: (near initialization for ‘dn_lib[13]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1054:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1054:5: warning: (near initialization for ‘dn_lib[13]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1055:5: warning: braces around scalar initializer [enabled by default]
     {"tointegralexact", dn_intxct },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1055:5: warning: (near initialization for ‘dn_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1055:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1055:5: warning: (near initialization for ‘dn_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1055:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1055:5: error: (near initialization for ‘dn_lib[14]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1055:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1055:5: warning: (near initialization for ‘dn_lib[14]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1056:5: warning: braces around scalar initializer [enabled by default]
     {"nextminus",       dn_intnmn },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1056:5: warning: (near initialization for ‘dn_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1056:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1056:5: warning: (near initialization for ‘dn_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1056:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1056:5: error: (near initialization for ‘dn_lib[15]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1056:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1056:5: warning: (near initialization for ‘dn_lib[15]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1057:5: warning: braces around scalar initializer [enabled by default]
     {"nextplus",        dn_intnpl },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1057:5: warning: (near initialization for ‘dn_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1057:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1057:5: warning: (near initialization for ‘dn_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1057:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1057:5: error: (near initialization for ‘dn_lib[16]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1057:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1057:5: warning: (near initialization for ‘dn_lib[16]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1059:5: warning: braces around scalar initializer [enabled by default]
     {"copy",            dn_copy       },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1059:5: warning: (near initialization for ‘dn_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1059:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1059:5: warning: (near initialization for ‘dn_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1059:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1059:5: error: (near initialization for ‘dn_lib[17]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1059:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1059:5: warning: (near initialization for ‘dn_lib[17]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1060:5: warning: braces around scalar initializer [enabled by default]
     {"copyabs",         dn_copyabs    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1060:5: warning: (near initialization for ‘dn_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1060:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1060:5: warning: (near initialization for ‘dn_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1060:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1060:5: error: (near initialization for ‘dn_lib[18]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1060:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1060:5: warning: (near initialization for ‘dn_lib[18]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1061:5: warning: braces around scalar initializer [enabled by default]
     {"copynegate",      dn_copynegate },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1061:5: warning: (near initialization for ‘dn_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1061:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1061:5: warning: (near initialization for ‘dn_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1061:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1061:5: error: (near initialization for ‘dn_lib[19]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1061:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1061:5: warning: (near initialization for ‘dn_lib[19]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1062:5: warning: braces around scalar initializer [enabled by default]
     {"copysign",        dn_copysign   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1062:5: warning: (near initialization for ‘dn_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1062:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1062:5: warning: (near initialization for ‘dn_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1062:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1062:5: error: (near initialization for ‘dn_lib[20]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1062:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1062:5: warning: (near initialization for ‘dn_lib[20]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1064:5: warning: braces around scalar initializer [enabled by default]
     {"add",             dn_add    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1064:5: warning: (near initialization for ‘dn_lib[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1064:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1064:5: warning: (near initialization for ‘dn_lib[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1064:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1064:5: error: (near initialization for ‘dn_lib[21]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1064:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1064:5: warning: (near initialization for ‘dn_lib[21]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1065:5: warning: braces around scalar initializer [enabled by default]
     {"divide",          dn_div    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1065:5: warning: (near initialization for ‘dn_lib[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1065:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1065:5: warning: (near initialization for ‘dn_lib[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1065:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1065:5: error: (near initialization for ‘dn_lib[22]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1065:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1065:5: warning: (near initialization for ‘dn_lib[22]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1066:5: warning: braces around scalar initializer [enabled by default]
     {"multiply",        dn_mul    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1066:5: warning: (near initialization for ‘dn_lib[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1066:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1066:5: warning: (near initialization for ‘dn_lib[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1066:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1066:5: error: (near initialization for ‘dn_lib[23]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1066:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1066:5: warning: (near initialization for ‘dn_lib[23]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1067:5: warning: braces around scalar initializer [enabled by default]
     {"power",           dn_pow    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1067:5: warning: (near initialization for ‘dn_lib[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1067:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1067:5: warning: (near initialization for ‘dn_lib[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1067:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1067:5: error: (near initialization for ‘dn_lib[24]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1067:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1067:5: warning: (near initialization for ‘dn_lib[24]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1068:5: warning: braces around scalar initializer [enabled by default]
     {"subtract",        dn_sub    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1068:5: warning: (near initialization for ‘dn_lib[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1068:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1068:5: warning: (near initialization for ‘dn_lib[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1068:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1068:5: error: (near initialization for ‘dn_lib[25]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1068:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1068:5: warning: (near initialization for ‘dn_lib[25]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1070:5: warning: braces around scalar initializer [enabled by default]
     {"compare",         dn_compare       },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1070:5: warning: (near initialization for ‘dn_lib[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1070:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1070:5: warning: (near initialization for ‘dn_lib[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1070:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1070:5: error: (near initialization for ‘dn_lib[26]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1070:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1070:5: warning: (near initialization for ‘dn_lib[26]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1071:5: warning: braces around scalar initializer [enabled by default]
     {"comparetotal",    dn_comparetotal  },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1071:5: warning: (near initialization for ‘dn_lib[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1071:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1071:5: warning: (near initialization for ‘dn_lib[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1071:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1071:5: error: (near initialization for ‘dn_lib[27]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1071:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1071:5: warning: (near initialization for ‘dn_lib[27]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1072:5: warning: braces around scalar initializer [enabled by default]
     {"divideinteger",   dn_divideinteger },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1072:5: warning: (near initialization for ‘dn_lib[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1072:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1072:5: warning: (near initialization for ‘dn_lib[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1072:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1072:5: error: (near initialization for ‘dn_lib[28]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1072:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1072:5: warning: (near initialization for ‘dn_lib[28]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1073:5: warning: braces around scalar initializer [enabled by default]
     {"max",             dn_max           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1073:5: warning: (near initialization for ‘dn_lib[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1073:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1073:5: warning: (near initialization for ‘dn_lib[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1073:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1073:5: error: (near initialization for ‘dn_lib[29]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1073:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1073:5: warning: (near initialization for ‘dn_lib[29]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1074:5: warning: braces around scalar initializer [enabled by default]
     {"min",             dn_min           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1074:5: warning: (near initialization for ‘dn_lib[30]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1074:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1074:5: warning: (near initialization for ‘dn_lib[30]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1074:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1074:5: error: (near initialization for ‘dn_lib[30]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1074:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1074:5: warning: (near initialization for ‘dn_lib[30]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1075:5: warning: braces around scalar initializer [enabled by default]
     {"quantize",        dn_quantize      },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1075:5: warning: (near initialization for ‘dn_lib[31]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1075:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1075:5: warning: (near initialization for ‘dn_lib[31]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1075:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1075:5: error: (near initialization for ‘dn_lib[31]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1075:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1075:5: warning: (near initialization for ‘dn_lib[31]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1076:5: warning: braces around scalar initializer [enabled by default]
     {"remainder",       dn_remainder     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1076:5: warning: (near initialization for ‘dn_lib[32]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1076:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1076:5: warning: (near initialization for ‘dn_lib[32]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1076:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1076:5: error: (near initialization for ‘dn_lib[32]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1076:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1076:5: warning: (near initialization for ‘dn_lib[32]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1077:5: warning: braces around scalar initializer [enabled by default]
     {"remaindernear",   dn_remaindernear },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1077:5: warning: (near initialization for ‘dn_lib[33]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1077:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1077:5: warning: (near initialization for ‘dn_lib[33]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1077:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1077:5: error: (near initialization for ‘dn_lib[33]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1077:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1077:5: warning: (near initialization for ‘dn_lib[33]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1078:5: warning: braces around scalar initializer [enabled by default]
     {"rescale",         dn_rescale       },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1078:5: warning: (near initialization for ‘dn_lib[34]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1078:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1078:5: warning: (near initialization for ‘dn_lib[34]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1078:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1078:5: error: (near initialization for ‘dn_lib[34]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1078:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1078:5: warning: (near initialization for ‘dn_lib[34]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1079:5: warning: braces around scalar initializer [enabled by default]
     {"samequantum",     dn_samequantum   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1079:5: warning: (near initialization for ‘dn_lib[35]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1079:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1079:5: warning: (near initialization for ‘dn_lib[35]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1079:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1079:5: error: (near initialization for ‘dn_lib[35]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1079:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1079:5: warning: (near initialization for ‘dn_lib[35]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1081:5: warning: braces around scalar initializer [enabled by default]
     {"land",            dn_and           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1081:5: warning: (near initialization for ‘dn_lib[36]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1081:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1081:5: warning: (near initialization for ‘dn_lib[36]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1081:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1081:5: error: (near initialization for ‘dn_lib[36]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1081:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1081:5: warning: (near initialization for ‘dn_lib[36]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1082:5: warning: braces around scalar initializer [enabled by default]
     {"comparetotalmag", dn_comparetotalmag },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1082:5: warning: (near initialization for ‘dn_lib[37]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1082:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1082:5: warning: (near initialization for ‘dn_lib[37]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1082:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1082:5: error: (near initialization for ‘dn_lib[37]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1082:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1082:5: warning: (near initialization for ‘dn_lib[37]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1083:5: warning: braces around scalar initializer [enabled by default]
     {"maxmag",          dn_maxmag        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1083:5: warning: (near initialization for ‘dn_lib[38]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1083:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1083:5: warning: (near initialization for ‘dn_lib[38]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1083:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1083:5: error: (near initialization for ‘dn_lib[38]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1083:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1083:5: warning: (near initialization for ‘dn_lib[38]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1084:5: warning: braces around scalar initializer [enabled by default]
     {"minmag",          dn_minmag        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1084:5: warning: (near initialization for ‘dn_lib[39]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1084:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1084:5: warning: (near initialization for ‘dn_lib[39]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1084:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1084:5: error: (near initialization for ‘dn_lib[39]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1084:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1084:5: warning: (near initialization for ‘dn_lib[39]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1085:5: warning: braces around scalar initializer [enabled by default]
     {"nexttoward",      dn_nexttoward    },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1085:5: warning: (near initialization for ‘dn_lib[40]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1085:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1085:5: warning: (near initialization for ‘dn_lib[40]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1085:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1085:5: error: (near initialization for ‘dn_lib[40]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1085:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1085:5: warning: (near initialization for ‘dn_lib[40]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1086:5: warning: braces around scalar initializer [enabled by default]
     {"lor",             dn_or            },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1086:5: warning: (near initialization for ‘dn_lib[41]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1086:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1086:5: warning: (near initialization for ‘dn_lib[41]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1086:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1086:5: error: (near initialization for ‘dn_lib[41]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1086:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1086:5: warning: (near initialization for ‘dn_lib[41]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1087:5: warning: braces around scalar initializer [enabled by default]
     {"rotate",          dn_rotate        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1087:5: warning: (near initialization for ‘dn_lib[42]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1087:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1087:5: warning: (near initialization for ‘dn_lib[42]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1087:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1087:5: error: (near initialization for ‘dn_lib[42]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1087:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1087:5: warning: (near initialization for ‘dn_lib[42]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1088:5: warning: braces around scalar initializer [enabled by default]
     {"scaleb",          dn_scaleb        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1088:5: warning: (near initialization for ‘dn_lib[43]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1088:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1088:5: warning: (near initialization for ‘dn_lib[43]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1088:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1088:5: error: (near initialization for ‘dn_lib[43]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1088:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1088:5: warning: (near initialization for ‘dn_lib[43]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1089:5: warning: braces around scalar initializer [enabled by default]
     {"shift",           dn_shift         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1089:5: warning: (near initialization for ‘dn_lib[44]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1089:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1089:5: warning: (near initialization for ‘dn_lib[44]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1089:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1089:5: error: (near initialization for ‘dn_lib[44]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1089:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1089:5: warning: (near initialization for ‘dn_lib[44]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1090:5: warning: braces around scalar initializer [enabled by default]
     {"xor",             dn_xor           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1090:5: warning: (near initialization for ‘dn_lib[45]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1090:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1090:5: warning: (near initialization for ‘dn_lib[45]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1090:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1090:5: error: (near initialization for ‘dn_lib[45]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1090:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1090:5: warning: (near initialization for ‘dn_lib[45]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1092:5: warning: braces around scalar initializer [enabled by default]
     {"fma",             dn_fma           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1092:5: warning: (near initialization for ‘dn_lib[46]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1092:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1092:5: warning: (near initialization for ‘dn_lib[46]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1092:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1092:5: error: (near initialization for ‘dn_lib[46]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1092:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1092:5: warning: (near initialization for ‘dn_lib[46]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1094:5: warning: braces around scalar initializer [enabled by default]
     {"mod",             dn_mod           },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1094:5: warning: (near initialization for ‘dn_lib[47]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1094:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1094:5: warning: (near initialization for ‘dn_lib[47]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1094:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1094:5: error: (near initialization for ‘dn_lib[47]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1094:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1094:5: warning: (near initialization for ‘dn_lib[47]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1095:5: warning: braces around scalar initializer [enabled by default]
     {"floor",           dn_floor         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1095:5: warning: (near initialization for ‘dn_lib[48]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1095:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1095:5: warning: (near initialization for ‘dn_lib[48]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1095:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1095:5: error: (near initialization for ‘dn_lib[48]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1095:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1095:5: warning: (near initialization for ‘dn_lib[48]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1097:5: warning: braces around scalar initializer [enabled by default]
     {"iszero",          dn_iszero        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1097:5: warning: (near initialization for ‘dn_lib[49]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1097:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1097:5: warning: (near initialization for ‘dn_lib[49]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1097:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1097:5: error: (near initialization for ‘dn_lib[49]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1097:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1097:5: warning: (near initialization for ‘dn_lib[49]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1098:5: warning: braces around scalar initializer [enabled by default]
     {"isnegative",      dn_isneg         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1098:5: warning: (near initialization for ‘dn_lib[50]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1098:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1098:5: warning: (near initialization for ‘dn_lib[50]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1098:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1098:5: error: (near initialization for ‘dn_lib[50]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1098:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1098:5: warning: (near initialization for ‘dn_lib[50]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1099:5: warning: braces around scalar initializer [enabled by default]
     {"isnan",           dn_isnan         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1099:5: warning: (near initialization for ‘dn_lib[51]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1099:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1099:5: warning: (near initialization for ‘dn_lib[51]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1099:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1099:5: error: (near initialization for ‘dn_lib[51]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1099:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1099:5: warning: (near initialization for ‘dn_lib[51]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1100:5: warning: braces around scalar initializer [enabled by default]
     {"isqnan",          dn_isqnan        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1100:5: warning: (near initialization for ‘dn_lib[52]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1100:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1100:5: warning: (near initialization for ‘dn_lib[52]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1100:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1100:5: error: (near initialization for ‘dn_lib[52]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1100:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1100:5: warning: (near initialization for ‘dn_lib[52]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1101:5: warning: braces around scalar initializer [enabled by default]
     {"issnan",          dn_issnan        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1101:5: warning: (near initialization for ‘dn_lib[53]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1101:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1101:5: warning: (near initialization for ‘dn_lib[53]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1101:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1101:5: error: (near initialization for ‘dn_lib[53]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1101:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1101:5: warning: (near initialization for ‘dn_lib[53]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1102:5: warning: braces around scalar initializer [enabled by default]
     {"isinfinite",      dn_isinf         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1102:5: warning: (near initialization for ‘dn_lib[54]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1102:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1102:5: warning: (near initialization for ‘dn_lib[54]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1102:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1102:5: error: (near initialization for ‘dn_lib[54]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1102:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1102:5: warning: (near initialization for ‘dn_lib[54]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1103:5: warning: braces around scalar initializer [enabled by default]
     {"isfinite",        dn_isfini        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1103:5: warning: (near initialization for ‘dn_lib[55]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1103:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1103:5: warning: (near initialization for ‘dn_lib[55]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1103:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1103:5: error: (near initialization for ‘dn_lib[55]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1103:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1103:5: warning: (near initialization for ‘dn_lib[55]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1104:5: warning: braces around scalar initializer [enabled by default]
     {"iscanonical",     dn_iscncl        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1104:5: warning: (near initialization for ‘dn_lib[56]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1104:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1104:5: warning: (near initialization for ‘dn_lib[56]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1104:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1104:5: error: (near initialization for ‘dn_lib[56]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1104:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1104:5: warning: (near initialization for ‘dn_lib[56]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1105:5: warning: braces around scalar initializer [enabled by default]
     {"isspecial",       dn_isspec        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1105:5: warning: (near initialization for ‘dn_lib[57]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1105:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1105:5: warning: (near initialization for ‘dn_lib[57]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1105:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1105:5: error: (near initialization for ‘dn_lib[57]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1105:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1105:5: warning: (near initialization for ‘dn_lib[57]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1106:5: warning: braces around scalar initializer [enabled by default]
     {"isnormal",        dn_isnorm        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1106:5: warning: (near initialization for ‘dn_lib[58]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1106:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1106:5: warning: (near initialization for ‘dn_lib[58]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1106:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1106:5: error: (near initialization for ‘dn_lib[58]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1106:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1106:5: warning: (near initialization for ‘dn_lib[58]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1107:5: warning: braces around scalar initializer [enabled by default]
     {"issubnormal",     dn_issubn        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1107:5: warning: (near initialization for ‘dn_lib[59]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1107:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1107:5: warning: (near initialization for ‘dn_lib[59]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1107:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1107:5: error: (near initialization for ‘dn_lib[59]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1107:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1107:5: warning: (near initialization for ‘dn_lib[59]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1109:5: warning: braces around scalar initializer [enabled by default]
     {"radix",           dn_radix         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1109:5: warning: (near initialization for ‘dn_lib[60]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1109:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1109:5: warning: (near initialization for ‘dn_lib[60]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1109:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1109:5: error: (near initialization for ‘dn_lib[60]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1109:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1109:5: warning: (near initialization for ‘dn_lib[60]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1110:5: warning: braces around scalar initializer [enabled by default]
     {"class",           dn_class         },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1110:5: warning: (near initialization for ‘dn_lib[61]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1110:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1110:5: warning: (near initialization for ‘dn_lib[61]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1110:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1110:5: error: (near initialization for ‘dn_lib[61]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1110:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1110:5: warning: (near initialization for ‘dn_lib[61]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1111:5: warning: braces around scalar initializer [enabled by default]
     {"classtostring",   dn_classtostring },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1111:5: warning: (near initialization for ‘dn_lib[62]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1111:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1111:5: warning: (near initialization for ‘dn_lib[62]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1111:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1111:5: error: (near initialization for ‘dn_lib[62]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1111:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1111:5: warning: (near initialization for ‘dn_lib[62]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1112:5: warning: braces around scalar initializer [enabled by default]
     {"classasstring",   dn_classasstring },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1112:5: warning: (near initialization for ‘dn_lib[63]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1112:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1112:5: warning: (near initialization for ‘dn_lib[63]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1112:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1112:5: error: (near initialization for ‘dn_lib[63]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1112:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1112:5: warning: (near initialization for ‘dn_lib[63]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1114:5: warning: braces around scalar initializer [enabled by default]
     {"trim",            dn_trim          },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1114:5: warning: (near initialization for ‘dn_lib[64]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1114:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1114:5: warning: (near initialization for ‘dn_lib[64]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1114:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1114:5: error: (near initialization for ‘dn_lib[64]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1114:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1114:5: warning: (near initialization for ‘dn_lib[64]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1116:5: warning: braces around scalar initializer [enabled by default]
     {"getcontext",      dn_get_context   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1116:5: warning: (near initialization for ‘dn_lib[65]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1116:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1116:5: warning: (near initialization for ‘dn_lib[65]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1116:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1116:5: error: (near initialization for ‘dn_lib[65]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1116:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1116:5: warning: (near initialization for ‘dn_lib[65]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1117:5: warning: braces around scalar initializer [enabled by default]
     {"setcontext",      dn_set_context   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1117:5: warning: (near initialization for ‘dn_lib[66]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1117:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1117:5: warning: (near initialization for ‘dn_lib[66]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1117:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1117:5: error: (near initialization for ‘dn_lib[66]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1117:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1117:5: warning: (near initialization for ‘dn_lib[66]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1118:5: warning: braces around scalar initializer [enabled by default]
     {"tonumber",        dn_todecnumber   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1118:5: warning: (near initialization for ‘dn_lib[67]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1118:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1118:5: warning: (near initialization for ‘dn_lib[67]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1118:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1118:5: error: (near initialization for ‘dn_lib[67]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1118:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1118:5: warning: (near initialization for ‘dn_lib[67]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1119:5: warning: braces around scalar initializer [enabled by default]
     {"tostring",        dn_string        },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1119:5: warning: (near initialization for ‘dn_lib[68]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1119:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1119:5: warning: (near initialization for ‘dn_lib[68]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1119:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1119:5: error: (near initialization for ‘dn_lib[68]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1119:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1119:5: warning: (near initialization for ‘dn_lib[68]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1120:5: warning: braces around scalar initializer [enabled by default]
     {"toengstring",     dn_engstring     },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1120:5: warning: (near initialization for ‘dn_lib[69]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1120:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1120:5: warning: (near initialization for ‘dn_lib[69]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1120:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1120:5: error: (near initialization for ‘dn_lib[69]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1120:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1120:5: warning: (near initialization for ‘dn_lib[69]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1122:5: warning: braces around scalar initializer [enabled by default]
     {"randomstate",     dn_randomstate   },
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1122:5: warning: (near initialization for ‘dn_lib[70]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1122:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1122:5: warning: (near initialization for ‘dn_lib[70]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1122:5: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1122:5: error: (near initialization for ‘dn_lib[70]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1122:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1122:5: warning: (near initialization for ‘dn_lib[70]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1127:5: warning: braces around scalar initializer [enabled by default]
     {NULL, NULL}
     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1127:5: warning: (near initialization for ‘dn_lib[71]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1127:5: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1127:5: warning: (near initialization for ‘dn_lib[71]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1127:5: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1127:5: warning: (near initialization for ‘dn_lib[71]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1130:1: error: unknown type name ‘luaL_reg’
 static void mkmeta (lua_State *L, const char *uname, const char *tname, const luaL_reg *reg)
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c: In function ‘mkmeta’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1134:5: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
     luaL_register (L, NULL, reg); /* register metatable functions */
     ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:30:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lauxlib.h:202:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c: In function ‘luaopen_ldecNumber’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1155:21: error: ‘LUA_ENVIRONINDEX’ undeclared (first use in this function)
     lua_replace (L, LUA_ENVIRONINDEX); /* the new c function environment */
                     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1155:5: warning: passing argument 2 of ‘lua_replace’ makes integer from pointer without a cast [enabled by default]
     lua_replace (L, LUA_ENVIRONINDEX); /* the new c function environment */
     ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:29:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lua.h:150:16: note: expected ‘int’ but argument is of type ‘const int *’
 LUA_API void  (lua_replace) (lua_State *L, int idx);
                ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:1157:5: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
     luaL_register (L, DN_NAME, dn_lib);
     ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/ldecnumber 2.1-1/ldecNumber.c:30:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/include/lauxlib.h:202:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
make[2]: *** [CMakeFiles/ldecNumber.dir/ldecNumber.c.o] Error 1
make[1]: *** [CMakeFiles/ldecNumber.dir/all] Error 2
make: *** [all] Error 2

