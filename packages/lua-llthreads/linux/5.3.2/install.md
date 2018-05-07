# Report for 'install lua 5.3.2 lua-llthreads'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- lua-llthreads 1.2-1

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **lua-llthreads 1.2-1**
    - **remote:** git://github.com/LuaDist-testing/lua-llthreads.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1

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

### lua-llthreads 1.2-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/lua-llthreads-1.2-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1-build'
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
- **Error:** Error building package 'lua-llthreads 1.2-1': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1-build'
stdout:
Scanning dependencies of target llthreads
[ 50%] Building C object CMakeFiles/llthreads.dir/src/pre_generated-llthreads.nobj.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:171:2: error: unknown type name ‘luaL_reg’
  const luaL_reg  *pub_funcs;
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:172:2: error: unknown type name ‘luaL_reg’
  const luaL_reg  *methods;
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:173:2: error: unknown type name ‘luaL_reg’
  const luaL_reg  *metas;
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c: In function ‘obj_type_register_package’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:553:2: error: unknown type name ‘luaL_reg’
  const luaL_reg *reg_list = type_reg->pub_funcs;
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:556:36: error: request for member ‘name’ in something not a structure or union
  if(reg_list != NULL && reg_list[0].name != NULL) {
                                    ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:558:3: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
   luaL_register(L, NULL, reg_list);
   ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:10:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lauxlib.h:199:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c: In function ‘obj_type_register’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:567:2: error: unknown type name ‘luaL_reg’
  const luaL_reg *reg_list;
  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:578:36: error: request for member ‘name’ in something not a structure or union
  if(reg_list != NULL && reg_list[0].name != NULL) {
                                    ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:580:3: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
   luaL_register(L, NULL, reg_list); /* fill public API table. */
   ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:10:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lauxlib.h:199:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:9:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:585:35: error: request for member ‘func’ in something not a structure or union
   lua_pushcfunction(L, reg_list[0].func); /* push first constructor function. */
                                   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lua.h:350:53: note: in definition of macro ‘lua_pushcfunction’
 #define lua_pushcfunction(L,f) lua_pushcclosure(L, (f), 0)
                                                     ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:610:2: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
  luaL_register(L, NULL, type_reg->methods); /* fill methods table. */
  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:10:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lauxlib.h:199:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int * const’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:632:2: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
  luaL_register(L, NULL, type_reg->metas); /* fill metatable */
  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:10:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lauxlib.h:199:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int * const’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c: In function ‘traceback’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:782:19: error: ‘LUA_GLOBALSINDEX’ undeclared (first use in this function)
   lua_getfield(L, LUA_GLOBALSINDEX, "debug");
                   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:782:19: note: each undeclared identifier is reported only once for each function it appears in
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c: At top level:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1226:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg obj_Lua_LLThread_pub_funcs[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1227:3: warning: braces around scalar initializer [enabled by default]
   {NULL, NULL}
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1227:3: warning: (near initialization for ‘obj_Lua_LLThread_pub_funcs[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1227:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1227:3: warning: (near initialization for ‘obj_Lua_LLThread_pub_funcs[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1227:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1227:3: warning: (near initialization for ‘obj_Lua_LLThread_pub_funcs[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1230:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg obj_Lua_LLThread_methods[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1231:3: warning: braces around scalar initializer [enabled by default]
   {"start", Lua_LLThread__start__meth},
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1231:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1231:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1231:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1231:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1231:3: error: (near initialization for ‘obj_Lua_LLThread_methods[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1231:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1231:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1232:3: warning: braces around scalar initializer [enabled by default]
   {"join", Lua_LLThread__join__meth},
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1232:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1232:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1232:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1232:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1232:3: error: (near initialization for ‘obj_Lua_LLThread_methods[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1232:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1232:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1233:3: warning: braces around scalar initializer [enabled by default]
   {NULL, NULL}
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1233:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1233:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1233:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1233:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1233:3: warning: (near initialization for ‘obj_Lua_LLThread_methods[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1236:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg obj_Lua_LLThread_metas[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1237:3: warning: braces around scalar initializer [enabled by default]
   {"__gc", Lua_LLThread__delete__meth},
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1237:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1237:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1237:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1237:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1237:3: error: (near initialization for ‘obj_Lua_LLThread_metas[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1237:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1237:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1238:3: warning: braces around scalar initializer [enabled by default]
   {"__tostring", obj_udata_default_tostring},
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1238:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1238:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1238:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1238:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1238:3: error: (near initialization for ‘obj_Lua_LLThread_metas[1]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1238:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1238:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1239:3: warning: braces around scalar initializer [enabled by default]
   {"__eq", obj_udata_default_equal},
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1239:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1239:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1239:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1239:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1239:3: error: (near initialization for ‘obj_Lua_LLThread_metas[2]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1239:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1239:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[2]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1240:3: warning: braces around scalar initializer [enabled by default]
   {NULL, NULL}
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1240:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1240:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1240:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1240:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1240:3: warning: (near initialization for ‘obj_Lua_LLThread_metas[3]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1255:1: error: unknown type name ‘luaL_reg’
 static const luaL_reg llthreads_function[] = {
 ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1256:3: warning: braces around scalar initializer [enabled by default]
   {"new", llthreads__new__func},
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1256:3: warning: (near initialization for ‘llthreads_function[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1256:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1256:3: warning: (near initialization for ‘llthreads_function[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1256:3: error: initializer element is not computable at load time
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1256:3: error: (near initialization for ‘llthreads_function[0]’)
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1256:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1256:3: warning: (near initialization for ‘llthreads_function[0]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1257:3: warning: braces around scalar initializer [enabled by default]
   {NULL, NULL}
   ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1257:3: warning: (near initialization for ‘llthreads_function[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1257:3: warning: initialization makes integer from pointer without a cast [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1257:3: warning: (near initialization for ‘llthreads_function[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1257:3: warning: excess elements in scalar initializer [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1257:3: warning: (near initialization for ‘llthreads_function[1]’) [enabled by default]
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c: In function ‘luaopen_llthreads’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:1317:2: warning: passing argument 3 of ‘luaL_openlib’ from incompatible pointer type [enabled by default]
  luaL_register(L, "llthreads", llthreads_function);
  ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua-llthreads 1.2-1/src/pre_generated-llthreads.nobj.c:10:0:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/include/lauxlib.h:199:18: note: expected ‘const struct luaL_Reg *’ but argument is of type ‘const int *’
 LUALIB_API void (luaL_openlib) (lua_State *L, const char *libname,
                  ^
make[2]: *** [CMakeFiles/llthreads.dir/src/pre_generated-llthreads.nobj.c.o] Error 1
make[1]: *** [CMakeFiles/llthreads.dir/all] Error 2
make: *** [all] Error 2

