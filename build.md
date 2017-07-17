#### Test (Fail) 130589065 Build Logs


```


```

```
Already up-to-date.

From http://github.com/thaliproject/testdummy
   4cd4c67..7612ee4  ci_test    -> origin/ci_test

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Already up-to-date.

Already on 'master'
Already on 'master'
Note: checking out '7612ee4'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 7612ee4... updated

```

```
Adding android project...
Creating Cordova project for the Android platform:
	Path: platforms/android
	Package: com.example.hello
	Name: HelloWorld
	Activity: MainActivity
	Android target: android-24
Subproject Path: CordovaLib
Android project created with cordova-android@6.0.0
Discovered plugin "cordova-plugin-whitelist" in config.xml. Adding it to the project
Fetching plugin "cordova-plugin-whitelist@1" via npm
Installing "cordova-plugin-whitelist" for android
ANDROID_HOME=/Users/thali/Library/Android/sdk
JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
Subproject Path: CordovaLib
Starting a new Gradle Daemon for this build (subsequent builds will be faster).
Incremental java compilation is an incubating feature.
:clean
:CordovaLib:clean

BUILD SUCCESSFUL

Total time: 21.813 secs

               This plugin is only applicable for versions of cordova-android greater than 4.0. If you have a previous platform version, you do *not* need this plugin since the whitelist will be built in.
          
ANDROID_HOME=/Users/thali/Library/Android/sdk
JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
Subproject Path: CordovaLib
Incremental java compilation is an incubating feature.
:preBuild UP-TO-DATE
:preReleaseBuild UP-TO-DATE
:checkReleaseManifest
:CordovaLib:preBuild UP-TO-DATE
:CordovaLib:preReleaseBuild UP-TO-DATE
:CordovaLib:checkReleaseManifest
:CordovaLib:prepareReleaseDependencies
:CordovaLib:compileReleaseAidl
:CordovaLib:compileReleaseNdk UP-TO-DATE
:CordovaLib:compileLint
:CordovaLib:copyReleaseLint UP-TO-DATE
:CordovaLib:mergeReleaseShaders
:CordovaLib:compileReleaseShaders
:CordovaLib:generateReleaseAssets
:CordovaLib:mergeReleaseAssets
:CordovaLib:mergeReleaseProguardFiles
:CordovaLib:packageReleaseRenderscript UP-TO-DATE
:CordovaLib:compileReleaseRenderscript
:CordovaLib:generateReleaseResValues
:CordovaLib:generateReleaseResources
:CordovaLib:packageReleaseResources
:CordovaLib:processReleaseManifest
:CordovaLib:generateReleaseBuildConfig
:CordovaLib:processReleaseResources
:CordovaLib:generateReleaseSources
:CordovaLib:incrementalReleaseJavaCompilationSafeguard
:CordovaLib:compileReleaseJavaWithJavac
:CordovaLib:compileReleaseJavaWithJavac - is not incremental (e.g. outputs have changed, no previous execution, etc.).
:CordovaLib:processReleaseJavaRes UP-TO-DATE
:CordovaLib:transformResourcesWithMergeJavaResForRelease
:CordovaLib:transformClassesAndResourcesWithSyncLibJarsForRelease
:CordovaLib:mergeReleaseJniLibFolders
:CordovaLib:transformNative_libsWithMergeJniLibsForRelease
:CordovaLib:transformNative_libsWithSyncJniLibsForRelease
:CordovaLib:bundleRelease
:prepareAndroidCordovaLibUnspecifiedReleaseLibrary
:prepareReleaseDependencies
:compileReleaseAidl
:compileReleaseRenderscript
:generateReleaseBuildConfig
:generateReleaseResValues
:generateReleaseResources
:mergeReleaseResources
:processReleaseManifest
:processReleaseResources
:generateReleaseSources
:incrementalReleaseJavaCompilationSafeguard
:compileReleaseJavaWithJavac
:compileReleaseJavaWithJavac - is not incremental (e.g. outputs have changed, no previous execution, etc.).
:compileReleaseNdk UP-TO-DATE
:compileReleaseSources
:lintVitalRelease
:mergeReleaseShaders
:compileReleaseShaders
:generateReleaseAssets
:mergeReleaseAssets
:transformClassesWithDexForRelease
:mergeReleaseJniLibFolders
:transformNative_libsWithMergeJniLibsForRelease
:processReleaseJavaRes UP-TO-DATE
:transformResourcesWithMergeJavaResForRelease
:packageRelease
:assembleRelease
:cdvBuildRelease

BUILD SUCCESSFUL

Total time: 23.829 secs
Built the following apk(s): 
	/Users/thali/Github/testBuild/platforms/android/build/outputs/apk/android-release-unsigned.apk
copying Android build for CI
./build_droid.sh CI FAILED - build.sh failure[0m

Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
cp: ../testdummy/platforms/android/build/outputs/apk/android-release-unsigned.apk: No such file or directory

```

Error: Command failed: Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
cp: ../testdummy/platforms/android/build/outputs/apk/android-release-unsigned.apk: No such file or directory
