#### Test (Fail) 55634150 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/TestDummy
   e857e16..8f7ee06  test_vjrantal2 -> origin/test_vjrantal2

```

```
Your branch is up-to-date with 'origin/master'.
Branch test_ogz2 set up to track remote branch test_ogz2 from origin.
Already up-to-date.

Switched to branch 'master'
Switched to a new branch 'test_ogz2'
Note: checking out '8f7ee06'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 8f7ee06... Fail on purpose after build done.

```

```
Removing "io.jxcore.node"
jxc@1.0.10 node_modules/jxc
└── jxtools@0.0.3 (progress@1.1.8, adm-zip@0.4.7)
[36mDownloading:[39m [32mhttp://az836273.vo.msecnd.net/0.0.8/io.jxcore.node.jx
[39m
[1A[KAttempt 1 / 3
[1A[K
[1A[K[36mProgress:[39m [32mDone[39m
[32mExtracting plugin package...[39m
[32mDone.[39m
[32mRemoving plugin from project...[39m
[1A[K[32mAdding plugin to project...[39m
[32mCleaning up...[39m
[32mDone.[39m
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
Running command: /Users/thali/Github/testBuild/platforms/android/cordova/build --release --device
ANDROID_HOME=/Users/thali/Library/Android/sdk
JAVA_HOME=/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home
Running: /Users/thali/Github/testBuild/platforms/android/gradlew cdvBuildRelease -b /Users/thali/Github/testBuild/platforms/android/build.gradle -Dorg.gradle.daemon=true
:preBuild
:preReleaseBuild
:checkReleaseManifest
:CordovaLib:compileLint
:CordovaLib:copyReleaseLint UP-TO-DATE
:CordovaLib:mergeReleaseProguardFiles
:CordovaLib:preBuild
:CordovaLib:preReleaseBuild
:CordovaLib:checkReleaseManifest
:CordovaLib:prepareReleaseDependencies
:CordovaLib:compileReleaseAidl
:CordovaLib:compileReleaseRenderscript
:CordovaLib:generateReleaseBuildConfig
:CordovaLib:generateReleaseAssets UP-TO-DATE
:CordovaLib:mergeReleaseAssets
:CordovaLib:generateReleaseResValues
:CordovaLib:generateReleaseResources
:CordovaLib:packageReleaseResources
:CordovaLib:processReleaseManifest
:CordovaLib:processReleaseResources
:CordovaLib:generateReleaseSources
:CordovaLib:compileReleaseJava
:CordovaLib:processReleaseJavaRes UP-TO-DATE
:CordovaLib:packageReleaseJar
:CordovaLib:compileReleaseNdk
:CordovaLib:packageReleaseJniLibs UP-TO-DATE
:CordovaLib:packageReleaseLocalJar UP-TO-DATE
:CordovaLib:packageReleaseRenderscript UP-TO-DATE
:CordovaLib:bundleRelease
:prepareAndroidCordovaLibUnspecifiedReleaseLibrary
:prepareReleaseDependencies
:compileReleaseAidl
:compileReleaseRenderscript
:generateReleaseBuildConfig
:generateReleaseAssets UP-TO-DATE
:mergeReleaseAssets
:generateReleaseResValues
:generateReleaseResources
:mergeReleaseResources
:processReleaseManifest
:processReleaseResources
:generateReleaseSources
:compileReleaseJava
:lintVitalRelease
:compileReleaseNdk
:preDexRelease
:dexRelease
:processReleaseJavaRes UP-TO-DATE
:packageRelease
:assembleRelease
:cdvBuildRelease

BUILD SUCCESSFUL

Total time: 38.918 secs
Built the following apk(s):
    /Users/thali/Github/testBuild/platforms/android/build/outputs/apk/android-release-unsigned.apk
build aborted
 [0m

npm http GET https://registry.npmjs.org/jxc
npm http 200 https://registry.npmjs.org/jxc
npm http GET https://registry.npmjs.org/jxc/-/jxc-1.0.10.tgz
npm http 200 https://registry.npmjs.org/jxc/-/jxc-1.0.10.tgz
npm http GET https://registry.npmjs.org/adm-zip
npm http GET https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/adm-zip
npm http GET https://registry.npmjs.org/adm-zip/-/adm-zip-0.4.7.tgz
npm http 200 https://registry.npmjs.org/progress
npm http GET https://registry.npmjs.org/progress/-/progress-1.1.8.tgz
npm http 200 https://registry.npmjs.org/progress/-/progress-1.1.8.tgz
npm http 200 https://registry.npmjs.org/adm-zip/-/adm-zip-0.4.7.tgz
[31mRemoving plugin from project...[39m
warning: java/lang/Object.class(java/lang:Object.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/String.class(java/lang:String.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONArray.class(org/json:JSONArray.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/util/Log.class(android/util:Log.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONObject.class(org/json:JSONObject.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/List.class(java/util:List.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Map.class(java/util:Map.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/Context.class(android/content:Context.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/Intent.class(android/content:Intent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/View.class(android/view:View.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/WebChromeClient.class(android/webkit:WebChromeClient.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/WebChromeClient$CustomViewCallback.class(android/webkit:WebChromeClient$CustomViewCallback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/util/Base64.class(android/util:Base64.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/app/Activity.class(android/app:Activity.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/concurrent/ExecutorService.class(java/util/concurrent:ExecutorService.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/HashMap.class(java/util:HashMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Locale.class(java/util:Locale.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Bundle.class(android/os:Bundle.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ContentResolver.class(android/content:ContentResolver.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/res/AssetFileDescriptor.class(android/content/res:AssetFileDescriptor.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/res/AssetManager.class(android/content/res:AssetManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/database/Cursor.class(android/database:Cursor.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/net/Uri.class(android/net:Uri.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Looper.class(android/os:Looper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/MimeTypeMap.class(android/webkit:MimeTypeMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/ByteArrayInputStream.class(java/io:ByteArrayInputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/File.class(java/io:File.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/FileInputStream.class(java/io:FileInputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/FileNotFoundException.class(java/io:FileNotFoundException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/FileOutputStream.class(java/io:FileOutputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/IOException.class(java/io:IOException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/InputStream.class(java/io:InputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/OutputStream.class(java/io:OutputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/UnsupportedEncodingException.class(java/io:UnsupportedEncodingException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/net/HttpURLConnection.class(java/net:HttpURLConnection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/net/URL.class(java/net:URL.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/nio/channels/FileChannel.class(java/nio/channels:FileChannel.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Collection.class(java/util:Collection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/LinkedHashMap.class(java/util:LinkedHashMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONException.class(org/json:JSONException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/res/Configuration.class(android/content/res:Configuration.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Debug.class(android/os:Debug.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/KeyEvent.class(android/view:KeyEvent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Enum.class(java/lang:Enum.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/Serializable.class(java/io:Serializable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Comparable.class(java/lang:Comparable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Thread.class(java/lang:Thread.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/security/Principal.class(java/security:Principal.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/security/PrivateKey.class(java/security:PrivateKey.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/security/cert/X509Certificate.class(java/security/cert:X509Certificate.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Boolean.class(java/lang:Boolean.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/ArrayList.class(java/util:ArrayList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/LinkedList.class(java/util:LinkedList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/StringBuilder.class(java/lang:StringBuilder.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Deprecated.class(java/lang:Deprecated.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/regex/Matcher.class(java/util/regex:Matcher.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/regex/Pattern.class(java/util/regex:Pattern.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/xmlpull/v1/XmlPullParser.class(org/xmlpull/v1:XmlPullParser.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/xmlpull/v1/XmlPullParserException.class(org/xmlpull/v1:XmlPullParserException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/app/AlertDialog.class(android/app:AlertDialog.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/DialogInterface.class(android/content:DialogInterface.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/Color.class(android/graphics:Color.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/media/AudioManager.class(android/media:AudioManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Build.class(android/os:Build.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Menu.class(android/view:Menu.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/MenuItem.class(android/view:MenuItem.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ViewGroup.class(android/view:ViewGroup.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Window.class(android/view:Window.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/WindowManager.class(android/view:WindowManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/WebViewClient.class(android/webkit:WebViewClient.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/widget/FrameLayout.class(android/widget:FrameLayout.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater.class(android/view:LayoutInflater.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater$Factory2.class(android/view:LayoutInflater$Factory2.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater$Factory.class(android/view:LayoutInflater$Factory.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Window$Callback.class(android/view:Window$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/KeyEvent$Callback.class(android/view:KeyEvent$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Parcelable.class(android/os:Parcelable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/InputEvent.class(android/view:InputEvent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/View$OnCreateContextMenuListener.class(android/view:View$OnCreateContextMenuListener.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/drawable/Drawable.class(android/graphics/drawable:Drawable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/drawable/Drawable$Callback.class(android/graphics/drawable:Drawable$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/accessibility/AccessibilityEventSource.class(android/view/accessibility:AccessibilityEventSource.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ComponentCallbacks2.class(android/content:ComponentCallbacks2.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ComponentCallbacks.class(android/content:ComponentCallbacks.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ContextThemeWrapper.class(android/view:ContextThemeWrapper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ContextWrapper.class(android/content:ContextWrapper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/concurrent/Executors.class(java/util/concurrent:Executors.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/security/SecureRandom.class(java/security:SecureRandom.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/IllegalAccessException.class(java/lang:IllegalAccessException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/ClientCertRequest.class(android/webkit:ClientCertRequest.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/widget/EditText.class(android/widget:EditText.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/HttpAuthHandler.class(android/webkit:HttpAuthHandler.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Gravity.class(android/view:Gravity.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/reflect/Constructor.class(java/lang/reflect:Constructor.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/HashSet.class(java/util:HashSet.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Set.class(java/util:Set.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/BroadcastReceiver.class(android/content:BroadcastReceiver.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/IntentFilter.class(android/content:IntentFilter.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/telephony/TelephonyManager.class(android/telephony:TelephonyManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Integer.class(java/lang:Integer.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
100 warnings
warning: android/os/Bundle.class(android/os:Bundle.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/app/Activity.class(android/app:Activity.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater.class(android/view:LayoutInflater.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater$Factory2.class(android/view:LayoutInflater$Factory2.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater$Factory.class(android/view:LayoutInflater$Factory.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Object.class(java/lang:Object.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Window.class(android/view:Window.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Window$Callback.class(android/view:Window$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/KeyEvent.class(android/view:KeyEvent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/KeyEvent$Callback.class(android/view:KeyEvent$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Parcelable.class(android/os:Parcelable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/InputEvent.class(android/view:InputEvent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/View.class(android/view:View.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/View$OnCreateContextMenuListener.class(android/view:View$OnCreateContextMenuListener.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/drawable/Drawable.class(android/graphics/drawable:Drawable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/drawable/Drawable$Callback.class(android/graphics/drawable:Drawable$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/accessibility/AccessibilityEventSource.class(android/view/accessibility:AccessibilityEventSource.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ComponentCallbacks2.class(android/content:ComponentCallbacks2.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ComponentCallbacks.class(android/content:ComponentCallbacks.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ContextThemeWrapper.class(android/view:ContextThemeWrapper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ContextWrapper.class(android/content:ContextWrapper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/Context.class(android/content:Context.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/BufferedReader.class(java/io:BufferedReader.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/IOException.class(java/io:IOException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/InputStream.class(java/io:InputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/InputStreamReader.class(java/io:InputStreamReader.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/annotation/SuppressLint.class(android/annotation:SuppressLint.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/res/AssetManager.class(android/content/res:AssetManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/util/Log.class(android/util:Log.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/String.class(java/lang:String.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/ArrayList.class(java/util:ArrayList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Enumeration.class(java/util:Enumeration.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/HashMap.class(java/util:HashMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Map.class(java/util:Map.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/zip/ZipEntry.class(java/util/zip:ZipEntry.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/zip/ZipFile.class(java/util/zip:ZipFile.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONArray.class(org/json:JSONArray.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONException.class(org/json:JSONException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Handler.class(android/os:Handler.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Looper.class(android/os:Looper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Runnable.class(java/lang:Runnable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/Point.class(android/graphics:Point.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/provider/Settings.class(android/provider:Settings.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/provider/Settings$SettingNotFoundException.class(android/provider:Settings$SettingNotFoundException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Display.class(android/view:Display.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/WindowManager.class(android/view:WindowManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/bluetooth/BluetoothAdapter.class(android/bluetooth:BluetoothAdapter.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/net/ConnectivityManager.class(android/net:ConnectivityManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/net/NetworkInfo.class(android/net:NetworkInfo.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/net/wifi/WifiManager.class(android/net/wifi:WifiManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/xmlpull/v1/XmlPullParser.class(org/xmlpull/v1:XmlPullParser.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Boolean.class(java/lang:Boolean.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ViewDebug.class(android/view:ViewDebug.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ViewDebug$ExportedProperty.class(android/view:ViewDebug$ExportedProperty.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ViewDebug$IntToString.class(android/view:ViewDebug$IntToString.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Override.class(java/lang:Override.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/Annotation.class(java/lang/annotation:Annotation.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/Target.class(java/lang/annotation:Target.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/ElementType.class(java/lang/annotation:ElementType.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/Retention.class(java/lang/annotation:Retention.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/RetentionPolicy.class(java/lang/annotation:RetentionPolicy.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Error.class(java/lang:Error.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/pm/PackageManager.class(android/content/pm:PackageManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/pm/PackageManager$NameNotFoundException.class(android/content/pm:PackageManager$NameNotFoundException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/util/AndroidException.class(android/util:AndroidException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Exception.class(java/lang:Exception.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Throwable.class(java/lang:Throwable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/RuntimeException.class(java/lang:RuntimeException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/IntentSender.class(android/content:IntentSender.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/IntentSender$SendIntentException.class(android/content:IntentSender$SendIntentException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/FileNotFoundException.class(java/io:FileNotFoundException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/StringBuilder.class(java/lang:StringBuilder.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/AbstractStringBuilder.class(java/lang:AbstractStringBuilder.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/nio/charset/Charset.class(java/nio/charset:Charset.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/nio/charset/CharsetDecoder.class(java/nio/charset:CharsetDecoder.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/Reader.class(java/io:Reader.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/CharSequence.class(java/lang:CharSequence.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/Serializable.class(java/io:Serializable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Comparable.class(java/lang:Comparable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/StringBuffer.class(java/lang:StringBuffer.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/Closeable.class(java/io:Closeable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/AutoCloseable.class(java/lang:AutoCloseable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/UnsupportedEncodingException.class(java/io:UnsupportedEncodingException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/System.class(java/lang:System.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/List.class(java/util:List.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONObject.class(org/json:JSONObject.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Integer.class(java/lang:Integer.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Class.class(java/lang:Class.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Number.class(java/lang:Number.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Byte.class(java/lang:Byte.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Character.class(java/lang:Character.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Short.class(java/lang:Short.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Long.class(java/lang:Long.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Float.class(java/lang:Float.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Double.class(java/lang:Double.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONTokener.class(org/json:JSONTokener.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Collection.class(java/util:Collection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractMap.class(java/util:AbstractMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractList.class(java/util:AbstractList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractCollection.class(java/util:AbstractCollection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
100 warnings
./build_droid.sh: line 38: FAIL_ON_PURPOSE_SINCE_THIS_IS_ONLY_TESTING_THE_BUILD_PHASE: command not found

```

Error: Command failed: npm http GET https://registry.npmjs.org/jxc
npm http 200 https://registry.npmjs.org/jxc
npm http GET https://registry.npmjs.org/jxc/-/jxc-1.0.10.tgz
npm http 200 https://registry.npmjs.org/jxc/-/jxc-1.0.10.tgz
npm http GET https://registry.npmjs.org/adm-zip
npm http GET https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/adm-zip
npm http GET https://registry.npmjs.org/adm-zip/-/adm-zip-0.4.7.tgz
npm http 200 https://registry.npmjs.org/progress
npm http GET https://registry.npmjs.org/progress/-/progress-1.1.8.tgz
npm http 200 https://registry.npmjs.org/progress/-/progress-1.1.8.tgz
npm http 200 https://registry.npmjs.org/adm-zip/-/adm-zip-0.4.7.tgz
[31mRemoving plugin from project...[39m
warning: java/lang/Object.class(java/lang:Object.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/String.class(java/lang:String.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONArray.class(org/json:JSONArray.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/util/Log.class(android/util:Log.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONObject.class(org/json:JSONObject.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/List.class(java/util:List.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Map.class(java/util:Map.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/Context.class(android/content:Context.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/Intent.class(android/content:Intent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/View.class(android/view:View.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/WebChromeClient.class(android/webkit:WebChromeClient.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/WebChromeClient$CustomViewCallback.class(android/webkit:WebChromeClient$CustomViewCallback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/util/Base64.class(android/util:Base64.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/app/Activity.class(android/app:Activity.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/concurrent/ExecutorService.class(java/util/concurrent:ExecutorService.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/HashMap.class(java/util:HashMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Locale.class(java/util:Locale.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Bundle.class(android/os:Bundle.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ContentResolver.class(android/content:ContentResolver.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/res/AssetFileDescriptor.class(android/content/res:AssetFileDescriptor.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/res/AssetManager.class(android/content/res:AssetManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/database/Cursor.class(android/database:Cursor.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/net/Uri.class(android/net:Uri.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Looper.class(android/os:Looper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/MimeTypeMap.class(android/webkit:MimeTypeMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/ByteArrayInputStream.class(java/io:ByteArrayInputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/File.class(java/io:File.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/FileInputStream.class(java/io:FileInputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/FileNotFoundException.class(java/io:FileNotFoundException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/FileOutputStream.class(java/io:FileOutputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/IOException.class(java/io:IOException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/InputStream.class(java/io:InputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/OutputStream.class(java/io:OutputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/UnsupportedEncodingException.class(java/io:UnsupportedEncodingException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/net/HttpURLConnection.class(java/net:HttpURLConnection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/net/URL.class(java/net:URL.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/nio/channels/FileChannel.class(java/nio/channels:FileChannel.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Collection.class(java/util:Collection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/LinkedHashMap.class(java/util:LinkedHashMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONException.class(org/json:JSONException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/res/Configuration.class(android/content/res:Configuration.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Debug.class(android/os:Debug.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/KeyEvent.class(android/view:KeyEvent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Enum.class(java/lang:Enum.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/Serializable.class(java/io:Serializable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Comparable.class(java/lang:Comparable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Thread.class(java/lang:Thread.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/security/Principal.class(java/security:Principal.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/security/PrivateKey.class(java/security:PrivateKey.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/security/cert/X509Certificate.class(java/security/cert:X509Certificate.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Boolean.class(java/lang:Boolean.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/ArrayList.class(java/util:ArrayList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/LinkedList.class(java/util:LinkedList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/StringBuilder.class(java/lang:StringBuilder.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Deprecated.class(java/lang:Deprecated.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/regex/Matcher.class(java/util/regex:Matcher.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/regex/Pattern.class(java/util/regex:Pattern.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/xmlpull/v1/XmlPullParser.class(org/xmlpull/v1:XmlPullParser.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/xmlpull/v1/XmlPullParserException.class(org/xmlpull/v1:XmlPullParserException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/app/AlertDialog.class(android/app:AlertDialog.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/DialogInterface.class(android/content:DialogInterface.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/Color.class(android/graphics:Color.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/media/AudioManager.class(android/media:AudioManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Build.class(android/os:Build.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Menu.class(android/view:Menu.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/MenuItem.class(android/view:MenuItem.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ViewGroup.class(android/view:ViewGroup.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Window.class(android/view:Window.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/WindowManager.class(android/view:WindowManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/WebViewClient.class(android/webkit:WebViewClient.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/widget/FrameLayout.class(android/widget:FrameLayout.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater.class(android/view:LayoutInflater.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater$Factory2.class(android/view:LayoutInflater$Factory2.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater$Factory.class(android/view:LayoutInflater$Factory.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Window$Callback.class(android/view:Window$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/KeyEvent$Callback.class(android/view:KeyEvent$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Parcelable.class(android/os:Parcelable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/InputEvent.class(android/view:InputEvent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/View$OnCreateContextMenuListener.class(android/view:View$OnCreateContextMenuListener.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/drawable/Drawable.class(android/graphics/drawable:Drawable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/drawable/Drawable$Callback.class(android/graphics/drawable:Drawable$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/accessibility/AccessibilityEventSource.class(android/view/accessibility:AccessibilityEventSource.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ComponentCallbacks2.class(android/content:ComponentCallbacks2.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ComponentCallbacks.class(android/content:ComponentCallbacks.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ContextThemeWrapper.class(android/view:ContextThemeWrapper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ContextWrapper.class(android/content:ContextWrapper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/concurrent/Executors.class(java/util/concurrent:Executors.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/security/SecureRandom.class(java/security:SecureRandom.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/IllegalAccessException.class(java/lang:IllegalAccessException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/ClientCertRequest.class(android/webkit:ClientCertRequest.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/widget/EditText.class(android/widget:EditText.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/webkit/HttpAuthHandler.class(android/webkit:HttpAuthHandler.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Gravity.class(android/view:Gravity.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/reflect/Constructor.class(java/lang/reflect:Constructor.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/HashSet.class(java/util:HashSet.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Set.class(java/util:Set.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/BroadcastReceiver.class(android/content:BroadcastReceiver.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/IntentFilter.class(android/content:IntentFilter.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/telephony/TelephonyManager.class(android/telephony:TelephonyManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Integer.class(java/lang:Integer.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
100 warnings
warning: android/os/Bundle.class(android/os:Bundle.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/app/Activity.class(android/app:Activity.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater.class(android/view:LayoutInflater.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater$Factory2.class(android/view:LayoutInflater$Factory2.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/LayoutInflater$Factory.class(android/view:LayoutInflater$Factory.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Object.class(java/lang:Object.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Window.class(android/view:Window.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Window$Callback.class(android/view:Window$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/KeyEvent.class(android/view:KeyEvent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/KeyEvent$Callback.class(android/view:KeyEvent$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Parcelable.class(android/os:Parcelable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/InputEvent.class(android/view:InputEvent.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/View.class(android/view:View.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/View$OnCreateContextMenuListener.class(android/view:View$OnCreateContextMenuListener.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/drawable/Drawable.class(android/graphics/drawable:Drawable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/drawable/Drawable$Callback.class(android/graphics/drawable:Drawable$Callback.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/accessibility/AccessibilityEventSource.class(android/view/accessibility:AccessibilityEventSource.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ComponentCallbacks2.class(android/content:ComponentCallbacks2.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ComponentCallbacks.class(android/content:ComponentCallbacks.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ContextThemeWrapper.class(android/view:ContextThemeWrapper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/ContextWrapper.class(android/content:ContextWrapper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/Context.class(android/content:Context.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/BufferedReader.class(java/io:BufferedReader.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/IOException.class(java/io:IOException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/InputStream.class(java/io:InputStream.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/InputStreamReader.class(java/io:InputStreamReader.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/annotation/SuppressLint.class(android/annotation:SuppressLint.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/res/AssetManager.class(android/content/res:AssetManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/util/Log.class(android/util:Log.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/String.class(java/lang:String.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/ArrayList.class(java/util:ArrayList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Enumeration.class(java/util:Enumeration.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/HashMap.class(java/util:HashMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Map.class(java/util:Map.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/zip/ZipEntry.class(java/util/zip:ZipEntry.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/zip/ZipFile.class(java/util/zip:ZipFile.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONArray.class(org/json:JSONArray.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONException.class(org/json:JSONException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Handler.class(android/os:Handler.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/os/Looper.class(android/os:Looper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Runnable.class(java/lang:Runnable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/graphics/Point.class(android/graphics:Point.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/provider/Settings.class(android/provider:Settings.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/provider/Settings$SettingNotFoundException.class(android/provider:Settings$SettingNotFoundException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/Display.class(android/view:Display.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/WindowManager.class(android/view:WindowManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/bluetooth/BluetoothAdapter.class(android/bluetooth:BluetoothAdapter.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/net/ConnectivityManager.class(android/net:ConnectivityManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/net/NetworkInfo.class(android/net:NetworkInfo.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/net/wifi/WifiManager.class(android/net/wifi:WifiManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/xmlpull/v1/XmlPullParser.class(org/xmlpull/v1:XmlPullParser.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Boolean.class(java/lang:Boolean.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ViewDebug.class(android/view:ViewDebug.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ViewDebug$ExportedProperty.class(android/view:ViewDebug$ExportedProperty.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/view/ViewDebug$IntToString.class(android/view:ViewDebug$IntToString.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Override.class(java/lang:Override.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/Annotation.class(java/lang/annotation:Annotation.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/Target.class(java/lang/annotation:Target.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/ElementType.class(java/lang/annotation:ElementType.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/Retention.class(java/lang/annotation:Retention.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/annotation/RetentionPolicy.class(java/lang/annotation:RetentionPolicy.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Error.class(java/lang:Error.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/pm/PackageManager.class(android/content/pm:PackageManager.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/pm/PackageManager$NameNotFoundException.class(android/content/pm:PackageManager$NameNotFoundException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/util/AndroidException.class(android/util:AndroidException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Exception.class(java/lang:Exception.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Throwable.class(java/lang:Throwable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/RuntimeException.class(java/lang:RuntimeException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/IntentSender.class(android/content:IntentSender.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/IntentSender$SendIntentException.class(android/content:IntentSender$SendIntentException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/FileNotFoundException.class(java/io:FileNotFoundException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/StringBuilder.class(java/lang:StringBuilder.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/AbstractStringBuilder.class(java/lang:AbstractStringBuilder.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/nio/charset/Charset.class(java/nio/charset:Charset.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/nio/charset/CharsetDecoder.class(java/nio/charset:CharsetDecoder.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/Reader.class(java/io:Reader.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/CharSequence.class(java/lang:CharSequence.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/Serializable.class(java/io:Serializable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Comparable.class(java/lang:Comparable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/StringBuffer.class(java/lang:StringBuffer.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/Closeable.class(java/io:Closeable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/AutoCloseable.class(java/lang:AutoCloseable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/io/UnsupportedEncodingException.class(java/io:UnsupportedEncodingException.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/System.class(java/lang:System.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/List.class(java/util:List.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONObject.class(org/json:JSONObject.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Integer.class(java/lang:Integer.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Class.class(java/lang:Class.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Number.class(java/lang:Number.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Byte.class(java/lang:Byte.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Character.class(java/lang:Character.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Short.class(java/lang:Short.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Long.class(java/lang:Long.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Float.class(java/lang:Float.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Double.class(java/lang:Double.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: org/json/JSONTokener.class(org/json:JSONTokener.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/Collection.class(java/util:Collection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractMap.class(java/util:AbstractMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractList.class(java/util:AbstractList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractCollection.class(java/util:AbstractCollection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
100 warnings
./build_droid.sh: line 38: FAIL_ON_PURPOSE_SINCE_THIS_IS_ONLY_TESTING_THE_BUILD_PHASE: command not found
