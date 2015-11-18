#### Test (Fail) 50242285 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/TestDummy
   b143d21..b70c9f6  test_ogz   -> origin/test_ogz

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Branch test_ogz set up to track remote branch test_ogz from origin.
Merge made by the 'recursive' strategy.
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

Already on 'master'
Already on 'master'
Switched to a new branch 'test_ogz'

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
Installing "io.jxcore.node" for android
Running command: /Users/thali/Github/testBuild/platforms/android/cordova/build --release --device
ANDROID_HOME=/Users/thali/Library/Android/sdk
JAVA_HOME=/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home
Running: /Users/thali/Github/testBuild/platforms/android/gradlew cdvBuildRelease -b /Users/thali/Github/testBuild/platforms/android/build.gradle -Dorg.gradle.daemon=true

BUILD FAILED

Total time: 1 mins 21.665 secs
ERROR building one of the platforms: Error: /Users/thali/Github/testBuild/platforms/android/cordova/build: Command failed with exit code 8
You may not have the required environment or OS to build this project
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m


FAILURE: Build failed with an exception.

* What went wrong:
A problem occurred configuring root project 'android'.
> Could not resolve all dependencies for configuration ':classpath'.
   > Could not resolve com.android.tools.build:gradle:1.0.0+.
     Required by:
         :android:unspecified
      > Failed to list versions for com.android.tools.build:gradle.
         > Unable to load Maven meta-data from https://repo1.maven.org/maven2/com/android/tools/build/gradle/maven-metadata.xml.
            > Could not GET 'https://repo1.maven.org/maven2/com/android/tools/build/gradle/maven-metadata.xml'.
               > Connection to https://repo1.maven.org refused

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

node.js:813
throw ee;
      ^
Error code 1 for command: /Users/thali/Github/testBuild/platforms/android/gradlew with args: cdvBuildRelease,-b,/Users/thali/Github/testBuild/platforms/android/build.gradle,-Dorg.gradle.daemon=true
Error: /Users/thali/Github/testBuild/platforms/android/cordova/build: Command failed with exit code 8
    at ChildProcess.whenDone (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/cordova/superspawn.js:139:23)
    at ChildProcess.emit (events.js:85:9)
    at maybeClose (child_process.js:773:12)
    at Process.ChildProcess._handle.onexit (child_process.js:839:1)

```

Error: Command failed: 
FAILURE: Build failed with an exception.

* What went wrong:
A problem occurred configuring root project 'android'.
> Could not resolve all dependencies for configuration ':classpath'.
   > Could not resolve com.android.tools.build:gradle:1.0.0+.
     Required by:
         :android:unspecified
      > Failed to list versions for com.android.tools.build:gradle.
         > Unable to load Maven meta-data from https://repo1.maven.org/maven2/com/android/tools/build/gradle/maven-metadata.xml.
            > Could not GET 'https://repo1.maven.org/maven2/com/android/tools/build/gradle/maven-metadata.xml'.
               > Connection to https://repo1.maven.org refused

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

node.js:813
throw ee;
      ^
Error code 1 for command: /Users/thali/Github/testBuild/platforms/android/gradlew with args: cdvBuildRelease,-b,/Users/thali/Github/testBuild/platforms/android/build.gradle,-Dorg.gradle.daemon=true
Error: /Users/thali/Github/testBuild/platforms/android/cordova/build: Command failed with exit code 8
    at ChildProcess.whenDone (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/cordova/superspawn.js:139:23)
    at ChildProcess.emit (events.js:85:9)
    at maybeClose (child_process.js:773:12)
    at Process.ChildProcess._handle.onexit (child_process.js:839:1)
