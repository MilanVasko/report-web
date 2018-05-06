# Report for 'install lua 5.3.2 luacoap'


## 1. Manifest retrieval

- Downloading manifest...

- **Manifest URLs**:
    - git://github.com/LuaDist-core/manifest.git
    - git://github.com/LuaDist-testing/manifest.git
- Success

## 2. Dependency solving


### Resolved dependencies:
- lua 5.3.2-1
- luacoap 0.1-0

## 3. Fetching packages

- **lua 5.3.2-1**
    - **remote:** git://github.com/LuaDist-core/lua.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/lua 5.3.2-1
- **luacoap 0.1-0**
    - **remote:** git://github.com/LuaDist-testing/luacoap.git
    - **local:** /home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luacoap 0.1-0

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

### luacoap 0.1-0
- Loaded rockspec from '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luacoap 0.1-0/luacoap-0.1-0.rockspec'
- Package 'luacoap 0.1-0': using CMakeLists.txt provided by package itself
- Building into '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luacoap 0.1-0-build'
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
- **Error:** Error building package 'luacoap 0.1-0': Could not build with CMake in directory '/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luacoap 0.1-0-build'
stdout:
Scanning dependencies of target smcp
[  9%] Creating directories for 'smcp'
[ 18%] Performing download step (git clone) for 'smcp'
[ 27%] No patch step for 'smcp'
[ 36%] No update step for 'smcp'
[ 45%] Performing configure step for 'smcp'
 *** autoreconf failed with error code 1

stderr:
Cloning into 'smcp'...
Note: checking out '0.6.5'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 08e822e... Version bump to 0.6.5.
/home/travis/build/LuaDist-testing/_luadist_install/lua 5.3.2/tmp/luacoap 0.1-0-build/smcp/bootstrap.sh: 8: cd: can't cd to /home/travis/build/LuaDist-testing/_luadist_install
5.3.2/tmp
0.1-0-build/smcp
+mkdir -p m4
+AUTOMAKE=automake --foreign autoreconf --verbose --force --install
autoreconf: 'configure.ac' or 'configure.in' is required
+die autoreconf
+echo  *** autoreconf failed with error code 1
+exit 1
make[2]: *** [smcp-prefix/src/smcp-stamp/smcp-configure] Error 1
make[1]: *** [CMakeFiles/smcp.dir/all] Error 2
make: *** [all] Error 2

