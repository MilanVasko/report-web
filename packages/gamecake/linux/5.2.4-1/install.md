# Report for 'install lua 5.2.4-1 gamecake'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.2.4-1
- bit32 5.3.0-1
- gamecake 18-006

## 3. Fetching packages

- **lua 5.2.4-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/lua 5.2.4-1
- **bit32 5.3.0-1**
    - **remote:** git://github.com/LuaDist-testing/bit32.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/bit32 5.3.0-1
- **gamecake 18-006**
    - **remote:** git://github.com/LuaDist-testing/gamecake.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006

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

### bit32 5.3.0-1
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/bit32 5.3.0-1/bit32-5.3.0-1.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/bit32 5.3.0-1'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/bit32 5.3.0-1-build'
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
- Executing 'cd "/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/bit32 5.3.0-1-build" && cmake -P cmake_install.cmake'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/bit32 5.3.0-1'
- Removing '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/bit32 5.3.0-1-build'

- *hint:* If you wish to keep these directories, set the debug flag
- Updating local manifest at '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/share/luadist2/manifest-file'

### gamecake 18-006
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/gamecake-18-006.rockspec'
- Generated CMake file in '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006'
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006-build'
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
- **Error:** Error building package 'gamecake 18-006': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006-build'
stdout:
Scanning dependencies of target wetgenes.pack.core
[  7%] Building C object CMakeFiles/wetgenes.pack.core.dir/lua_pack/code/lua_pack.c.o
[ 15%] Building C object CMakeFiles/wetgenes.pack.core.dir/lib_hacks/code/hacks.c.o
[ 23%] Linking C shared module core.so
[ 23%] Built target wetgenes.pack.core
Scanning dependencies of target wetgenes.tardis.core
[ 30%] Building C object CMakeFiles/wetgenes.tardis.core.dir/lua_tardis/code/lua_tardis.c.o
[ 38%] Building C object CMakeFiles/wetgenes.tardis.core.dir/lib_hacks/code/hacks.c.o
[ 46%] Linking C shared module core.so
[ 46%] Built target wetgenes.tardis.core
Scanning dependencies of target wetgenes.grd.core
[ 53%] Building C object CMakeFiles/wetgenes.grd.core.dir/lua_grd/code/lua_grd.c.o

stderr:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c: In function ‘string_to_id’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:128:18: warning: multi-character character constant [-Wmultichar]
  const u32 test4='abcd'; // lets play find the ace
                  ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c: In function ‘lua_pack_field_size’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:276:8: warning: multi-character character constant [-Wmultichar]
   case 's8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:277:8: warning: multi-character character constant [-Wmultichar]
   case '-s8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:278:8: warning: multi-character character constant [-Wmultichar]
   case '+s8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:279:8: warning: multi-character character constant [-Wmultichar]
   case 'u8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:280:8: warning: multi-character character constant [-Wmultichar]
   case '-u8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:281:8: warning: multi-character character constant [-Wmultichar]
   case '+u8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:284:8: warning: multi-character character constant [-Wmultichar]
   case 's16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:285:8: warning: multi-character character constant [-Wmultichar]
   case '-s16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:286:8: warning: multi-character character constant [-Wmultichar]
   case '+s16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:287:8: warning: multi-character character constant [-Wmultichar]
   case 'u16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:288:8: warning: multi-character character constant [-Wmultichar]
   case '-u16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:289:8: warning: multi-character character constant [-Wmultichar]
   case '+u16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:292:8: warning: multi-character character constant [-Wmultichar]
   case 'f32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:293:8: warning: multi-character character constant [-Wmultichar]
   case '-f32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:294:8: warning: multi-character character constant [-Wmultichar]
   case '+f32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:295:8: warning: multi-character character constant [-Wmultichar]
   case 's32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:296:8: warning: multi-character character constant [-Wmultichar]
   case '-s32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:297:8: warning: multi-character character constant [-Wmultichar]
   case '+s32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:298:8: warning: multi-character character constant [-Wmultichar]
   case 'u32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:299:8: warning: multi-character character constant [-Wmultichar]
   case '-u32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:300:8: warning: multi-character character constant [-Wmultichar]
   case '+u32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c: In function ‘lua_pack_get_field’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:316:8: warning: multi-character character constant [-Wmultichar]
   case 's8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:317:8: warning: multi-character character constant [-Wmultichar]
   case '-s8' : return (double) lua_pack_read_s8 ( p, 1 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:318:8: warning: multi-character character constant [-Wmultichar]
   case '+s8' : return (double) lua_pack_read_s8 ( p, 0 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:320:8: warning: multi-character character constant [-Wmultichar]
   case 'u8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:321:8: warning: multi-character character constant [-Wmultichar]
   case '-u8' : return (double) lua_pack_read_u8 ( p, 1 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:322:8: warning: multi-character character constant [-Wmultichar]
   case '+u8' : return (double) lua_pack_read_u8 ( p, 0 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:324:8: warning: multi-character character constant [-Wmultichar]
   case 's16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:325:8: warning: multi-character character constant [-Wmultichar]
   case '-s16' : return (double) lua_pack_read_s16 ( p, 1 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:326:8: warning: multi-character character constant [-Wmultichar]
   case '+s16' : return (double) lua_pack_read_s16 ( p, 0 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:328:8: warning: multi-character character constant [-Wmultichar]
   case 'u16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:329:8: warning: multi-character character constant [-Wmultichar]
   case '-u16' : return (double) lua_pack_read_u16 ( p, 1 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:330:8: warning: multi-character character constant [-Wmultichar]
   case '+u16' : return (double) lua_pack_read_u16 ( p, 0 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:332:8: warning: multi-character character constant [-Wmultichar]
   case 'f32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:333:8: warning: multi-character character constant [-Wmultichar]
   case '-f32' : return (double) lua_pack_read_f32 ( p, 1 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:334:8: warning: multi-character character constant [-Wmultichar]
   case '+f32' : return (double) lua_pack_read_f32 ( p, 0 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:336:8: warning: multi-character character constant [-Wmultichar]
   case 's32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:337:8: warning: multi-character character constant [-Wmultichar]
   case '-s32' : return (double) lua_pack_read_s32 ( p, 1 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:338:8: warning: multi-character character constant [-Wmultichar]
   case '+s32' : return (double) lua_pack_read_s32 ( p, 0 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:340:8: warning: multi-character character constant [-Wmultichar]
   case 'u32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:341:8: warning: multi-character character constant [-Wmultichar]
   case '-u32' : return (double) lua_pack_read_u32 ( p, 1 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:342:8: warning: multi-character character constant [-Wmultichar]
   case '+u32' : return (double) lua_pack_read_u32 ( p, 0 );
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c: In function ‘lua_pack_set_field’:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:357:8: warning: multi-character character constant [-Wmultichar]
   case 's8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:358:8: warning: multi-character character constant [-Wmultichar]
   case '-s8' : lua_pack_write_s8 ( (s8)d,p, 1 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:359:8: warning: multi-character character constant [-Wmultichar]
   case '+s8' : lua_pack_write_s8 ( (s8)d,p, 0 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:361:8: warning: multi-character character constant [-Wmultichar]
   case 'u8' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:362:8: warning: multi-character character constant [-Wmultichar]
   case '-u8' : lua_pack_write_u8 ( (u8)d,p, 1 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:363:8: warning: multi-character character constant [-Wmultichar]
   case '+u8' : lua_pack_write_u8 ( (u8)d,p, 0 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:365:8: warning: multi-character character constant [-Wmultichar]
   case 's16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:366:8: warning: multi-character character constant [-Wmultichar]
   case '-s16' : lua_pack_write_s16 ( (s16)d,p, 1 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:367:8: warning: multi-character character constant [-Wmultichar]
   case '+s16' : lua_pack_write_s16 ( (s16)d,p, 0 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:369:8: warning: multi-character character constant [-Wmultichar]
   case 'u16' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:370:8: warning: multi-character character constant [-Wmultichar]
   case '-u16' : lua_pack_write_u16 ( (u16)d,p, 1 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:371:8: warning: multi-character character constant [-Wmultichar]
   case '+u16' : lua_pack_write_u16 ( (u16)d,p, 0 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:373:8: warning: multi-character character constant [-Wmultichar]
   case 'f32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:374:8: warning: multi-character character constant [-Wmultichar]
   case '-f32' : lua_pack_write_f32 ( (f32)d,p, 1 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:375:8: warning: multi-character character constant [-Wmultichar]
   case '+f32' : lua_pack_write_f32 ( (f32)d,p, 0 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:377:8: warning: multi-character character constant [-Wmultichar]
   case 's32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:378:8: warning: multi-character character constant [-Wmultichar]
   case '-s32' : lua_pack_write_s32 ( (s32)d,p, 1 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:379:8: warning: multi-character character constant [-Wmultichar]
   case '+s32' : lua_pack_write_s32 ( (s32)d,p, 0 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:381:8: warning: multi-character character constant [-Wmultichar]
   case 'u32' :
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:382:8: warning: multi-character character constant [-Wmultichar]
   case '-u32' : lua_pack_write_u32 ( (u32)d,p, 1 ); break;
        ^
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_pack/code/lua_pack.c:383:8: warning: multi-character character constant [-Wmultichar]
   case '+u32' : lua_pack_write_u32 ( (u32)d,p, 0 ); break;
        ^
In file included from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_grd/all.h:73:0,
                 from /home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_grd/code/lua_grd.c:6:
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.2.4-1/tmp/gamecake 18-006/lua_grd/code/grd_gif.h:8:21: fatal error: gif_lib.h: No such file or directory
 #include "gif_lib.h"
                     ^
compilation terminated.
make[2]: *** [CMakeFiles/wetgenes.grd.core.dir/lua_grd/code/lua_grd.c.o] Error 1
make[1]: *** [CMakeFiles/wetgenes.grd.core.dir/all] Error 2
make: *** [all] Error 2

