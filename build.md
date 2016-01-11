#### Test (Fail) 50242285 Build Logs


```


```

```
Updating 42a63d7..a861e70
Fast-forward
 io.jxcore.node/Changelog.md                        |   11 +-
 io.jxcore.node/app/jxcore_cordova.js               |  185 +++---
 io.jxcore.node/bin/libcares.a                      |  Bin 986968 -> 986968 bytes
 io.jxcore.node/bin/libchrome_zlib.a                |  Bin 1037688 -> 1037688 bytes
 io.jxcore.node/bin/libhttp_parser.a                |  Bin 152752 -> 152752 bytes
 io.jxcore.node/bin/libjx.a                         |  Bin 17168632 -> 17175656 bytes
 io.jxcore.node/bin/libleveldb.a                    |  Bin 3779528 -> 3779528 bytes
 io.jxcore.node/bin/libleveldown.a                  |  Bin 1421408 -> 1421408 bytes
 io.jxcore.node/bin/libmozjs.a                      |  Bin 89886200 -> 89886200 bytes
 io.jxcore.node/bin/libopenssl.a                    |  Bin 28254288 -> 28254288 bytes
 io.jxcore.node/bin/libsnappy.a                     |  Bin 202688 -> 202688 bytes
 io.jxcore.node/bin/libsqlite3.a                    |  Bin 7875216 -> 7875216 bytes
 io.jxcore.node/bin/libuv.a                         |  Bin 1499736 -> 1499736 bytes
 .../src/android/java/io/jxcore/node/JXMobile.java  |   35 +-
 .../src/android/java/io/jxcore/node/jxcore.java    |   71 +-
 .../src/android/libs/armeabi-v7a/libjxcore.so      |  Bin 11401700 -> 10914340 bytes
 .../src/android/libs/armeabi/libjxcore.so          |  Bin 11405788 -> 10922524 bytes
 io.jxcore.node/src/android/libs/x86/libjxcore.so   |  Bin 13849508 -> 13119972 bytes
 plugins/fetch.json                                 |    6 +-
 plugins/io.jxcore.node/Changelog.md                |   28 -
 plugins/io.jxcore.node/LICENSE                     |   58 --
 plugins/io.jxcore.node/README.md                   |  255 --------
 plugins/io.jxcore.node/app/jxcore/app.js           |   46 --
 plugins/io.jxcore.node/app/jxcore_cordova.js       |  506 --------------
 plugins/io.jxcore.node/bin/jx.h                    |  109 ----
 plugins/io.jxcore.node/bin/jx_result.h             |  215 ------
 plugins/io.jxcore.node/bin/libcares.a              |  Bin 986968 -> 0 bytes
 plugins/io.jxcore.node/bin/libchrome_zlib.a        |  Bin 1037688 -> 0 bytes
 plugins/io.jxcore.node/bin/libhttp_parser.a        |  Bin 152752 -> 0 bytes
 plugins/io.jxcore.node/bin/libjx.a                 |  Bin 19736976 -> 0 bytes
 plugins/io.jxcore.node/bin/libleveldb.a            |  Bin 3779528 -> 0 bytes
 plugins/io.jxcore.node/bin/libleveldown.a          |  Bin 1421368 -> 0 bytes
 plugins/io.jxcore.node/bin/libmozjs.a              |  Bin 89886200 -> 0 bytes
 plugins/io.jxcore.node/bin/libopenssl.a            |  Bin 28254288 -> 0 bytes
 plugins/io.jxcore.node/bin/libsnappy.a             |  Bin 202688 -> 0 bytes
 plugins/io.jxcore.node/bin/libsqlite3.a            |  Bin 7326208 -> 0 bytes
 plugins/io.jxcore.node/bin/libuv.a                 |  Bin 1496048 -> 0 bytes
 plugins/io.jxcore.node/install_and_run.bat         |   76 ---
 plugins/io.jxcore.node/install_and_run.md          |   69 --
 plugins/io.jxcore.node/install_and_run.sh          |   55 --
 plugins/io.jxcore.node/package.json                |   31 -
 plugins/io.jxcore.node/plugin.xml                  |   80 ---
 plugins/io.jxcore.node/sample/www/index.html       |   81 ---
 plugins/io.jxcore.node/sample/www/jxcore/app.js    |   55 --
 .../www/jxcore/node_modules/json-nice/index.js     |   98 ---
 .../www/jxcore/node_modules/json-nice/package.json |   45 --
 .../io.jxcore.node/src/android/AndroidManifest.xml |   31 -
 .../src/android/bin/AndroidManifest.xml            |   31 -
 .../io.jxcore.node/src/android/build_default.sh    |   36 -
 .../io.jxcore.node/src/android/build_leveldown.sh  |   36 -
 .../android/gen/io/jxcore/node/BuildConfig.java    |    6 -
 .../android/java/io/jxcore/node/FileManager.java   |   59 --
 .../src/android/java/io/jxcore/node/JXMobile.java  |  111 ----
 .../java/io/jxcore/node/JXcoreExtension.java       |   84 ---
 .../src/android/java/io/jxcore/node/jxcore.java    |  394 -----------
 plugins/io.jxcore.node/src/android/jni/Android.mk  |  116 ----
 .../src/android/jni/Android.mk.default             |   89 ---
 .../src/android/jni/Android.mk.level               |  116 ----
 .../io.jxcore.node/src/android/jni/Application.mk  |    4 -
 .../io.jxcore.node/src/android/jni/JniHelper.cpp   |  239 -------
 plugins/io.jxcore.node/src/android/jni/JniHelper.h |   45 --
 plugins/io.jxcore.node/src/android/jni/jxcore.cpp  |  577 ----------------
 .../io.jxcore.node/src/android/jni/jxcore_droid.h  |   55 --
 .../src/android/libs/armeabi-v7a/libjxcore.so      |  Bin 11233376 -> 0 bytes
 .../src/android/libs/armeabi/libjxcore.so          |  Bin 11237464 -> 0 bytes
 .../src/android/libs/x86/libjxcore.so              |  Bin 13434916 -> 0 bytes
 .../io.jxcore.node/src/android/project.properties  |   14 -
 plugins/io.jxcore.node/src/ios/CDVJXcore.h         |   24 -
 plugins/io.jxcore.node/src/ios/CDVJXcore.m         |  162 -----
 plugins/io.jxcore.node/src/ios/JXMobile.h          |   11 -
 plugins/io.jxcore.node/src/ios/JXMobile.m          |   59 --
 plugins/io.jxcore.node/src/ios/JXcore.h            |   72 --
 plugins/io.jxcore.node/src/ios/JXcore.m            |  690 --------------------
 plugins/io.jxcore.node/src/ios/JXcoreExtension.h   |   11 -
 plugins/io.jxcore.node/src/ios/JXcoreExtension.m   |   57 --
 plugins/io.jxcore.node/src/ios/Reachability.h      |  100 ---
 plugins/io.jxcore.node/src/ios/Reachability.m      |  288 --------
 plugins/io.jxcore.node/www/jxcore.js               |  176 -----
 78 files changed, 154 insertions(+), 5654 deletions(-)
 delete mode 100644 plugins/io.jxcore.node/Changelog.md
 delete mode 100644 plugins/io.jxcore.node/LICENSE
 delete mode 100644 plugins/io.jxcore.node/README.md
 delete mode 100644 plugins/io.jxcore.node/app/jxcore/app.js
 delete mode 100644 plugins/io.jxcore.node/app/jxcore_cordova.js
 delete mode 100644 plugins/io.jxcore.node/bin/jx.h
 delete mode 100644 plugins/io.jxcore.node/bin/jx_result.h
 delete mode 100644 plugins/io.jxcore.node/bin/libcares.a
 delete mode 100644 plugins/io.jxcore.node/bin/libchrome_zlib.a
 delete mode 100644 plugins/io.jxcore.node/bin/libhttp_parser.a
 delete mode 100644 plugins/io.jxcore.node/bin/libjx.a
 delete mode 100644 plugins/io.jxcore.node/bin/libleveldb.a
 delete mode 100644 plugins/io.jxcore.node/bin/libleveldown.a
 delete mode 100644 plugins/io.jxcore.node/bin/libmozjs.a
 delete mode 100644 plugins/io.jxcore.node/bin/libopenssl.a
 delete mode 100644 plugins/io.jxcore.node/bin/libsnappy.a
 delete mode 100644 plugins/io.jxcore.node/bin/libsqlite3.a
 delete mode 100644 plugins/io.jxcore.node/bin/libuv.a
 delete mode 100644 plugins/io.jxcore.node/install_and_run.bat
 delete mode 100644 plugins/io.jxcore.node/install_and_run.md
 delete mode 100644 plugins/io.jxcore.node/install_and_run.sh
 delete mode 100644 plugins/io.jxcore.node/package.json
 delete mode 100644 plugins/io.jxcore.node/plugin.xml
 delete mode 100644 plugins/io.jxcore.node/sample/www/index.html
 delete mode 100644 plugins/io.jxcore.node/sample/www/jxcore/app.js
 delete mode 100644 plugins/io.jxcore.node/sample/www/jxcore/node_modules/json-nice/index.js
 delete mode 100644 plugins/io.jxcore.node/sample/www/jxcore/node_modules/json-nice/package.json
 delete mode 100644 plugins/io.jxcore.node/src/android/AndroidManifest.xml
 delete mode 100644 plugins/io.jxcore.node/src/android/bin/AndroidManifest.xml
 delete mode 100644 plugins/io.jxcore.node/src/android/build_default.sh
 delete mode 100644 plugins/io.jxcore.node/src/android/build_leveldown.sh
 delete mode 100644 plugins/io.jxcore.node/src/android/gen/io/jxcore/node/BuildConfig.java
 delete mode 100644 plugins/io.jxcore.node/src/android/java/io/jxcore/node/FileManager.java
 delete mode 100644 plugins/io.jxcore.node/src/android/java/io/jxcore/node/JXMobile.java
 delete mode 100644 plugins/io.jxcore.node/src/android/java/io/jxcore/node/JXcoreExtension.java
 delete mode 100644 plugins/io.jxcore.node/src/android/java/io/jxcore/node/jxcore.java
 delete mode 100644 plugins/io.jxcore.node/src/android/jni/Android.mk
 delete mode 100644 plugins/io.jxcore.node/src/android/jni/Android.mk.default
 delete mode 100644 plugins/io.jxcore.node/src/android/jni/Android.mk.level
 delete mode 100644 plugins/io.jxcore.node/src/android/jni/Application.mk
 delete mode 100644 plugins/io.jxcore.node/src/android/jni/JniHelper.cpp
 delete mode 100644 plugins/io.jxcore.node/src/android/jni/JniHelper.h
 delete mode 100644 plugins/io.jxcore.node/src/android/jni/jxcore.cpp
 delete mode 100644 plugins/io.jxcore.node/src/android/jni/jxcore_droid.h
 delete mode 100644 plugins/io.jxcore.node/src/android/libs/armeabi-v7a/libjxcore.so
 delete mode 100644 plugins/io.jxcore.node/src/android/libs/armeabi/libjxcore.so
 delete mode 100644 plugins/io.jxcore.node/src/android/libs/x86/libjxcore.so
 delete mode 100644 plugins/io.jxcore.node/src/android/project.properties
 delete mode 100644 plugins/io.jxcore.node/src/ios/CDVJXcore.h
 delete mode 100644 plugins/io.jxcore.node/src/ios/CDVJXcore.m
 delete mode 100644 plugins/io.jxcore.node/src/ios/JXMobile.h
 delete mode 100644 plugins/io.jxcore.node/src/ios/JXMobile.m
 delete mode 100644 plugins/io.jxcore.node/src/ios/JXcore.h
 delete mode 100644 plugins/io.jxcore.node/src/ios/JXcore.m
 delete mode 100644 plugins/io.jxcore.node/src/ios/JXcoreExtension.h
 delete mode 100644 plugins/io.jxcore.node/src/ios/JXcoreExtension.m
 delete mode 100644 plugins/io.jxcore.node/src/ios/Reachability.h
 delete mode 100644 plugins/io.jxcore.node/src/ios/Reachability.m
 delete mode 100644 plugins/io.jxcore.node/www/jxcore.js

From https://github.com/thaliproject/TestDummy
   42a63d7..a861e70  test_ogz   -> origin/test_ogz

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Merge made by the 'recursive' strategy.
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

Switched to branch 'master'
Already on 'master'
Note: checking out 'a861e70'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at a861e70... update jxcore-cordova

```

```
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

Plugin "io.jxcore.node" is not present in the project. See `cordova plugin list`.

```

Error: Command failed: Plugin "io.jxcore.node" is not present in the project. See `cordova plugin list`.
