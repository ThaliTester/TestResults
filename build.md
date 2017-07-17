#### Test (Success) 130589065 Build Logs


```


```

```
Already up-to-date.

From http://github.com/thaliproject/testdummy
   7612ee4..91e8744  ci_test    -> origin/ci_test

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Already up-to-date.

Already on 'master'
Already on 'master'
Note: checking out '91e8744'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 91e8744... update

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

Total time: 18.59 secs

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

Total time: 27.995 secs
Built the following apk(s): 
	/Users/thali/Github/testBuild/platforms/android/build/outputs/apk/android-release-unsigned.apk
copying Android build for CI

Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.

```

```
 updating: META-INF/MANIFEST.MF
   adding: META-INF/ALIAS_NA.SF
   adding: META-INF/ALIAS_NA.RSA
  signing: AndroidManifest.xml
  signing: assets/www/cordova-js-src/android/nativeapiprovider.js
  signing: assets/www/cordova-js-src/android/promptbasednativeapi.js
  signing: assets/www/cordova-js-src/exec.js
  signing: assets/www/cordova-js-src/platform.js
  signing: assets/www/cordova-js-src/plugin/android/app.js
  signing: assets/www/cordova.js
  signing: assets/www/cordova_plugins.js
  signing: assets/www/index.html
  signing: assets/www/jxcore/TestingEnvironment/log.js
  signing: assets/www/jxcore/app.js
  signing: classes.dex
  signing: res/drawable-land-hdpi-v4/screen.png
  signing: res/drawable-land-ldpi-v4/screen.png
  signing: res/drawable-land-mdpi-v4/screen.png
  signing: res/drawable-land-xhdpi-v4/screen.png
  signing: res/drawable-port-hdpi-v4/screen.png
  signing: res/drawable-port-ldpi-v4/screen.png
  signing: res/drawable-port-mdpi-v4/screen.png
  signing: res/drawable-port-xhdpi-v4/screen.png
  signing: res/mipmap-hdpi-v4/icon.png
  signing: res/mipmap-ldpi-v4/icon.png
  signing: res/mipmap-mdpi-v4/icon.png
  signing: res/mipmap-xhdpi-v4/icon.png
  signing: res/xml/config.xml
  signing: resources.arsc
jar signed.

Warning: 
No -tsa or -tsacert is provided and this jar is not timestamped. Without a timestamp, users may not be able to validate this jar after the signer certificate's expiration date (2043-01-05) or after any future revocation date.
Verifying alignment of android.apk (4)...
      50 META-INF/MANIFEST.MF (OK - compressed)
    1087 META-INF/ALIAS_NA.SF (OK - compressed)
    2180 META-INF/ALIAS_NA.RSA (OK - compressed)
    3269 AndroidManifest.xml (OK - compressed)
    4360 assets/www/cordova-js-src/android/nativeapiprovider.js (OK - compressed)
    5147 assets/www/cordova-js-src/android/promptbasednativeapi.js (OK - compressed)
    5981 assets/www/cordova-js-src/exec.js (OK - compressed)
    9764 assets/www/cordova-js-src/platform.js (OK - compressed)
   11646 assets/www/cordova-js-src/plugin/android/app.js (OK - compressed)
   13186 assets/www/cordova.js (OK - compressed)
   30742 assets/www/cordova_plugins.js (OK - compressed)
   30978 assets/www/index.html (OK - compressed)
   32190 assets/www/jxcore/TestingEnvironment/log.js (OK - compressed)
   32503 assets/www/jxcore/app.js (OK - compressed)
   33302 classes.dex (OK - compressed)
   87740 res/drawable-land-hdpi-v4/screen.png (OK)
  303832 res/drawable-land-ldpi-v4/screen.png (OK)
  345448 res/drawable-land-mdpi-v4/screen.png (OK)
  436016 res/drawable-land-xhdpi-v4/screen.png (OK)
  924560 res/drawable-port-hdpi-v4/screen.png (OK)
 1144976 res/drawable-port-ldpi-v4/screen.png (OK)
 1186116 res/drawable-port-mdpi-v4/screen.png (OK)
 1278624 res/drawable-port-xhdpi-v4/screen.png (OK)
 1779696 res/mipmap-hdpi-v4/icon.png (OK)
 1784980 res/mipmap-ldpi-v4/icon.png (OK)
 1787276 res/mipmap-mdpi-v4/icon.png (OK)
 1790548 res/mipmap-xhdpi-v4/icon.png (OK)
 1797399 res/xml/config.xml (OK - compressed)
 1798336 resources.arsc (OK)
Verification succesful


```

```


```
