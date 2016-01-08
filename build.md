#### Test (Fail) 50242285 Build Logs


```


```

```
Updating e17d765..4fb584b
Fast-forward
 io.jxcore.node/plugin.xml                          |    3 +-
 .../android/java/io/jxcore/node/CoreRunnable.java  |   58 ++++++++++++++++++++
 2 files changed, 60 insertions(+), 1 deletion(-)
 create mode 100644 io.jxcore.node/src/android/java/io/jxcore/node/CoreRunnable.java

From https://github.com/thaliproject/TestDummy
   e17d765..4fb584b  test_ogz   -> origin/test_ogz

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Merge made by the 'recursive' strategy.
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

Switched to branch 'master'
Already on 'master'
Note: checking out '4fb584b'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 4fb584b... update to 0.1.0

```

```
Removing "io.jxcore.node"
Adding android project...
Creating Cordova project for the Android platform:
	Path: platforms/android
	Package: com.example.hello
	Name: HelloWorld
	Activity: MainActivity
	Android target: android-22
Copying template files...
Android project created with cordova-android@4.1.1
Discovered plugin "cordova-plugin-whitelist" in config.xml. Installing to the project
Fetching plugin "cordova-plugin-whitelist@1" via npm
Installing "cordova-plugin-whitelist" for android

This plugin is only applicable for versions of cordova-android greater than 4.0. If you have a previous platform version, you do *not* need this plugin since the whitelist will be built in.
	
Installing "io.jxcore.node" for android
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

Error during processing of action! Attempting to revert...
Failed to install 'io.jxcore.node':Error: Uh oh!
"/Users/thali/Github/testBuild/plugins/io.jxcore.node/src/android/java/io/jxcore/node/CoreRunnable.java.java" not found!
    at Object.module.exports.common.copyFile (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/common.js:38:40)
    at Object.module.exports.common.copyNewFile (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/common.js:69:16)
    at Object.module.exports.source-file.install (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/android.js:78:20)
    at installWrapper (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/platforms/platforms.js:77:32)
    at Object.ActionStack.process (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/util/action-stack.js:68:25)
    at handleInstall (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/install.js:576:20)
    at /usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/install.js:363:28
    at _fulfilled (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:787:54)
    at self.promiseDispatch.done (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:816:30)
    at Promise.promise.promiseDispatch (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:749:13)
Error: Uh oh!
"/Users/thali/Github/testBuild/plugins/io.jxcore.node/src/android/java/io/jxcore/node/CoreRunnable.java.java" not found!
    at Object.module.exports.common.copyFile (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/common.js:38:40)
    at Object.module.exports.common.copyNewFile (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/common.js:69:16)
    at Object.module.exports.source-file.install (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/android.js:78:20)
    at installWrapper (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/platforms/platforms.js:77:32)
    at Object.ActionStack.process (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/util/action-stack.js:68:25)
    at handleInstall (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/install.js:576:20)
    at /usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/install.js:363:28
    at _fulfilled (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:787:54)
    at self.promiseDispatch.done (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:816:30)
    at Promise.promise.promiseDispatch (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:749:13)

```

Error: Command failed: Error during processing of action! Attempting to revert...
Failed to install 'io.jxcore.node':Error: Uh oh!
"/Users/thali/Github/testBuild/plugins/io.jxcore.node/src/android/java/io/jxcore/node/CoreRunnable.java.java" not found!
    at Object.module.exports.common.copyFile (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/common.js:38:40)
    at Object.module.exports.common.copyNewFile (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/common.js:69:16)
    at Object.module.exports.source-file.install (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/android.js:78:20)
    at installWrapper (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/platforms/platforms.js:77:32)
    at Object.ActionStack.process (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/util/action-stack.js:68:25)
    at handleInstall (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/install.js:576:20)
    at /usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/install.js:363:28
    at _fulfilled (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:787:54)
    at self.promiseDispatch.done (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:816:30)
    at Promise.promise.promiseDispatch (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:749:13)
Error: Uh oh!
"/Users/thali/Github/testBuild/plugins/io.jxcore.node/src/android/java/io/jxcore/node/CoreRunnable.java.java" not found!
    at Object.module.exports.common.copyFile (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/common.js:38:40)
    at Object.module.exports.common.copyNewFile (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/common.js:69:16)
    at Object.module.exports.source-file.install (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/platforms/android.js:78:20)
    at installWrapper (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/platforms/platforms.js:77:32)
    at Object.ActionStack.process (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/util/action-stack.js:68:25)
    at handleInstall (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/install.js:576:20)
    at /usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/plugman/install.js:363:28
    at _fulfilled (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:787:54)
    at self.promiseDispatch.done (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:816:30)
    at Promise.promise.promiseDispatch (/usr/local/lib/node_modules/cordova/node_modules/q/q.js:749:13)
