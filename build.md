#### Test (Success) 50388019 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/TestDummy
   b17f598..6dc97cd  test_ogz2  -> origin/test_ogz2

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/test_ogz'.
Already up-to-date!
Merge made by the 'recursive' strategy.

Already on 'master'
Switched to branch 'test_ogz'
Note: checking out '6dc97cd'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b new_branch_name

HEAD is now at 6dc97cd... Update build.sh

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

Total time: 44.258 secs
Built the following apk(s):
    /Users/thali/Github/testBuild/platforms/android/build/outputs/apk/android-release-unsigned.apk

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

```

```
   adding: META-INF/MANIFEST.MF
   adding: META-INF/ALIAS_NA.SF
   adding: META-INF/ALIAS_NA.RSA
  signing: AndroidManifest.xml
  signing: assets/jxcore_cordova.js
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
  signing: assets/www/jxcore/node_modules/json-nice/README.md
  signing: assets/www/jxcore/node_modules/json-nice/index.js
  signing: assets/www/jxcore/node_modules/json-nice/package.json
  signing: assets/www/jxcore/node_modules/request/CHANGELOG.md
  signing: assets/www/jxcore/node_modules/request/CONTRIBUTING.md
  signing: assets/www/jxcore/node_modules/request/LICENSE
  signing: assets/www/jxcore/node_modules/request/README.md
  signing: assets/www/jxcore/node_modules/request/disabled.appveyor.yml
  signing: assets/www/jxcore/node_modules/request/examples/README.md
  signing: assets/www/jxcore/node_modules/request/index.js
  signing: assets/www/jxcore/node_modules/request/lib/auth.js
  signing: assets/www/jxcore/node_modules/request/lib/cookies.js
  signing: assets/www/jxcore/node_modules/request/lib/getProxyFromURI.js
  signing: assets/www/jxcore/node_modules/request/lib/har.js
  signing: assets/www/jxcore/node_modules/request/lib/helpers.js
  signing: assets/www/jxcore/node_modules/request/lib/multipart.js
  signing: assets/www/jxcore/node_modules/request/lib/oauth.js
  signing: assets/www/jxcore/node_modules/request/lib/querystring.js
  signing: assets/www/jxcore/node_modules/request/lib/redirect.js
  signing: assets/www/jxcore/node_modules/request/lib/tunnel.js
  signing: assets/www/jxcore/node_modules/request/node_modules/aws-sign2/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/aws-sign2/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/aws-sign2/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/aws-sign2/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/LICENSE.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/bl.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/stream.markdown
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/wg-meetings/2015-01-30.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/duplex.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_duplex.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_passthrough.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_readable.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_transform.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_writable.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/float.patch
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/lib/util.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/util.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/inherits.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/inherits_browser.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/build/build.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/component.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/History.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/browser.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/node.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/passthrough.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/readable.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/transform.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/writable.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/test/basic-test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/test/sauce.js
  signing: assets/www/jxcore/node_modules/request/node_modules/bl/test/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/caseless/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/caseless/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/caseless/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/caseless/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/caseless/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/License
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/Readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/lib/combined_stream.js
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/License
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/Makefile
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/Readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/lib/delayed_stream.js
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/combined-stream/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/extend/CHANGELOG.md
  signing: assets/www/jxcore/node_modules/request/node_modules/extend/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/extend/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/extend/component.json
  signing: assets/www/jxcore/node_modules/request/node_modules/extend/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/extend/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/forever-agent/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/forever-agent/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/forever-agent/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/forever-agent/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/License
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/Readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/lib/browser.js
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/lib/form_data.js
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/CHANGELOG.md
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/lib/async.js
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/form-data/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/bin/har-validator
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/error.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cache.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cacheEntry.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/content.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cookie.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/creator.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/entry.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/har.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/log.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/page.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/pageTimings.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/postData.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/record.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/request.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/response.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/timings.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/changelog.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/bluebird.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/bluebird.min.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/any.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/assert.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/async.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/bind.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/bluebird.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/call_get.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/cancel.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/captured_trace.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/catch_filter.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/context.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/debuggability.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/direct_resolve.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/each.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/errors.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/es5.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/filter.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/finally.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/generators.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/join.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/map.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/method.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/nodeify.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/progress.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise_array.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise_resolver.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promisify.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/props.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/queue.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/race.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/reduce.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/schedule.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/settle.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/some.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/synchronous_inspection.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/thenables.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/timers.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/using.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/util.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/license
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/license
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/license
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/license
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/license
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/license
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/license
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/license
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/History.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/Readme.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/example.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/formats.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/example.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/is-property.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/jsonpointer.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/LICENCE
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/Makefile
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/immutable.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/mutable.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/require.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/fixtures/cosmic.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/additionalItems.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/additionalProperties.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/allOf.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/anyOf.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/bignum.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/default.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/definitions.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/dependencies.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/enum.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/format.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/items.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxItems.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxLength.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxProperties.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maximum.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minItems.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minLength.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minProperties.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minimum.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/multipleOf.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/not.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/nullAndFormat.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/nullAndObject.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/oneOf.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/pattern.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/patternProperties.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/properties.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/ref.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/refRemote.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/required.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/type.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/uniqueItems.json
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/misc.js
  signing: assets/www/jxcore/node_modules/request/node_modules/har-validator/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/bower.json
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/component.json
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/example/usage.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/images/hawk.png
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/images/logo.png
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/lib/browser.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/lib/client.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/lib/crypto.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/lib/server.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/lib/utils.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/CONTRIBUTING.md
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/images/boom.png
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/test/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/Makefile
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/test/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/CONTRIBUTING.md
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/Makefile
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/images/hoek.png
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/escape.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/escaper.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/ignore.txt
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test1.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test2.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test3.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/Makefile
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/offset.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/time.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/test/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/test/browser.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/test/client.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/test/crypto.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/test/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/test/readme.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/test/server.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/test/uri.js
  signing: assets/www/jxcore/node_modules/request/node_modules/hawk/test/utils.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/http_signing.md
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/lib/parser.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/lib/signer.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/lib/util.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/lib/verify.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/errors.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/reader.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/types.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/writer.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/reader.test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/writer.test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/assert.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/CHANGELOG
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/README
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/README.old
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctf.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctio.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctype.js
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/man3ctype/ctio.3ctype
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/jsl.conf
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/jsstyle
  signing: assets/www/jxcore/node_modules/request/node_modules/http-signature/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/isstream/LICENSE.md
  signing: assets/www/jxcore/node_modules/request/node_modules/isstream/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/isstream/isstream.js
  signing: assets/www/jxcore/node_modules/request/node_modules/isstream/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/isstream/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/json-stringify-safe/CHANGELOG.md
  signing: assets/www/jxcore/node_modules/request/node_modules/json-stringify-safe/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/json-stringify-safe/Makefile
  signing: assets/www/jxcore/node_modules/request/node_modules/json-stringify-safe/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/json-stringify-safe/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/json-stringify-safe/stringify.js
  signing: assets/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/mocha.opts
  signing: assets/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/stringify_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/HISTORY.md
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/HISTORY.md
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/db.json
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/mime-types/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/LICENSE.md
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/bench.gnu
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/bench.sh
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/benchmark-native.c
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/benchmark.js
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/bin/uuid
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/bower.json
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/component.json
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/test/compare_v1.js
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/test/test.html
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/test/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/node-uuid/uuid.js
  signing: assets/www/jxcore/node_modules/request/node_modules/oauth-sign/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/oauth-sign/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/oauth-sign/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/oauth-sign/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/oauth-sign/test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/CHANGELOG.md
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/CONTRIBUTING.md
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/bower.json
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/lib/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/lib/parse.js
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/lib/stringify.js
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/lib/utils.js
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/test/parse.js
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/test/stringify.js
  signing: assets/www/jxcore/node_modules/request/node_modules/qs/test/utils.js
  signing: assets/www/jxcore/node_modules/request/node_modules/stringstream/LICENSE.txt
  signing: assets/www/jxcore/node_modules/request/node_modules/stringstream/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/stringstream/example.js
  signing: assets/www/jxcore/node_modules/request/node_modules/stringstream/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/stringstream/stringstream.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/generate-pubsuffix.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/cookie.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/memstore.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/pathMatch.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/permuteDomain.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/pubsuffix.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/store.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/package.json
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/public-suffix.txt
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/api_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_jar_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_sorting_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_to_json_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_to_string_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/date_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/domain_and_path_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/bsd-examples.json
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/examples.json
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/parser.json
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/jar_serialization_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/lifetime_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/parsing_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tough-cookie/test/regression_test.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tunnel-agent/LICENSE
  signing: assets/www/jxcore/node_modules/request/node_modules/tunnel-agent/README.md
  signing: assets/www/jxcore/node_modules/request/node_modules/tunnel-agent/index.js
  signing: assets/www/jxcore/node_modules/request/node_modules/tunnel-agent/package.json
  signing: assets/www/jxcore/node_modules/request/package.json
  signing: assets/www/jxcore/node_modules/request/release.sh
  signing: assets/www/jxcore/node_modules/request/request.js
  signing: assets/www/plugins/cordova-plugin-whitelist/whitelist.js
  signing: assets/www/plugins/io.jxcore.node/www/jxcore.js
  signing: res/drawable-hdpi-v4/icon.png
  signing: res/drawable-land-hdpi-v4/screen.png
  signing: res/drawable-land-ldpi-v4/screen.png
  signing: res/drawable-land-mdpi-v4/screen.png
  signing: res/drawable-land-xhdpi-v4/screen.png
  signing: res/drawable-ldpi-v4/icon.png
  signing: res/drawable-mdpi-v4/icon.png
  signing: res/drawable-port-hdpi-v4/screen.png
  signing: res/drawable-port-ldpi-v4/screen.png
  signing: res/drawable-port-mdpi-v4/screen.png
  signing: res/drawable-port-xhdpi-v4/screen.png
  signing: res/drawable-xhdpi-v4/icon.png
  signing: res/xml/config.xml
  signing: resources.arsc
  signing: classes.dex
  signing: lib/armeabi/libjxcore.so
  signing: lib/armeabi-v7a/libjxcore.so
  signing: lib/x86/libjxcore.so


```

```
Removing "io.jxcore.node"
Adding ios project...
iOS project created with cordova-ios@3.9.2
Discovered plugin "cordova-plugin-whitelist" in config.xml. Installing to the project
Fetching plugin "cordova-plugin-whitelist@1" via npm
Installing "cordova-plugin-whitelist" for ios

This plugin is only applicable for versions of cordova-android greater than 4.0. If you have a previous platform version, you do *not* need this plugin since the whitelist will be built in.
	
Installing "io.jxcore.node" for ios
Running command: /Users/thali/Github/testBuild/platforms/ios/cordova/build --device
Building project  : /Users/thali/Github/testBuild/platforms/ios/HelloWorld.xcodeproj
	Configuration : Debug
	Platform      : device
Build settings from command line:
    ARCHS = armv7 armv7s arm64
    CONFIGURATION_BUILD_DIR = /Users/thali/Github/testBuild/platforms/ios/build/device
    SDKROOT = iphoneos9.0
    SHARED_PRECOMPS_DIR = /Users/thali/Github/testBuild/platforms/ios/build/sharedpch
    VALID_ARCHS = armv7 armv7s arm64

Build settings from configuration file '/Users/thali/Github/testBuild/platforms/ios/cordova/build-debug.xcconfig':
    CODE_SIGN_IDENTITY = iPhone Developer
    ENABLE_BITCODE = NO

=== BUILD TARGET CordovaLib OF PROJECT CordovaLib WITH CONFIGURATION Debug ===

Check dependencies

Write auxiliary files
write-file /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap
write-file /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap
write-file /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap
/bin/mkdir -p /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7
write-file /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/Cordova.LinkFileList
/bin/mkdir -p /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih
write-file /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch.pch.hash-criteria
write-file /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova.hmap
write-file /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap
write-file /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-non-framework-target-headers.hmap

CpHeader Classes/NSDictionary+Extensions.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/NSDictionary+Extensions.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSDictionary+Extensions.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVInvokedUrlCommand.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVInvokedUrlCommand.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVInvokedUrlCommand.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/NSData+Base64.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/NSData+Base64.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSData+Base64.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVPluginResult.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVPluginResult.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPluginResult.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVDebug.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVDebug.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVDebug.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVPlugin.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVPlugin.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPlugin.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVWhitelist.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVWhitelist.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVWhitelist.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/NSMutableArray+QueueAdditions.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/NSMutableArray+QueueAdditions.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSMutableArray+QueueAdditions.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVURLProtocol.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVURLProtocol.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVURLProtocol.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVViewController.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVViewController.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVCommandDelegate.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVCommandDelegate.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandDelegate.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDV.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDV.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVAvailability.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVAvailability.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVAvailability.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVAvailabilityDeprecated.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVAvailabilityDeprecated.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVAvailabilityDeprecated.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVLocalStorage.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVLocalStorage.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVLocalStorage.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/UIDevice+Extensions.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/UIDevice+Extensions.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/UIDevice+Extensions.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/NSArray+Comparisons.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/NSArray+Comparisons.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSArray+Comparisons.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVCommandQueue.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVCommandQueue.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandQueue.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVCommandDelegateImpl.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVCommandDelegateImpl.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandDelegateImpl.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVShared.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVShared.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVShared.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVScreenOrientationDelegate.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVScreenOrientationDelegate.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVScreenOrientationDelegate.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVConfigParser.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVConfigParser.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVConfigParser.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVJSON.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVJSON.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVJSON.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVWebViewDelegate.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVWebViewDelegate.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVWebViewDelegate.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVUserAgentUtil.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVUserAgentUtil.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVUserAgentUtil.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

CpHeader Classes/CDVTimer.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova/CDVTimer.h
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVTimer.h /Users/thali/Github/testBuild/platforms/ios/build/device/include/Cordova

ProcessPCH /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch.pch CordovaLib_Prefix.pch normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c-header -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -MD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch.d -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/CordovaLib_Prefix.pch -o /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch.pch --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch.dia

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+Extensions.o Classes/NSDictionary+Extensions.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+Extensions.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+Extensions.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSDictionary+Extensions.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+Extensions.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.o Classes/CDVInvokedUrlCommand.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVInvokedUrlCommand.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.o
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVInvokedUrlCommand.m:88:60: warning: 'cdv_dataFromBase64String:' is deprecated: Deprecated in Cordova 3.9.2. Use NSData initWithBase64EncodedString instead. This will be removed in 4.0.0 [-Wdeprecated-declarations]
        [newArgs replaceObjectAtIndex:i withObject:[NSData cdv_dataFromBase64String:data]];
                                                           ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVInvokedUrlCommand.m:22:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSData+Base64.h:44:1: note: 'cdv_dataFromBase64String:' has been explicitly marked deprecated here
+ (NSData*)cdv_dataFromBase64String:(NSString*)aString CDV_DEPRECATED(3.9.2, "Use NSData initWithBase64EncodedString instead. This will be removed in 4.0.0");
^
1 warning generated.

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSData+Base64.o Classes/NSData+Base64.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSData+Base64.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSData+Base64.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSData+Base64.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSData+Base64.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.o Classes/CDVPluginResult.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPluginResult.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.o
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPluginResult.m:40:31: warning: 'cdv_base64EncodedString' is deprecated: Deprecated in Cordova 3.9.2. Use NSData base64EncodedStringWithOptions instead. This will be removed in 4.0.0 [-Wdeprecated-declarations]
               @"data" :[data cdv_base64EncodedString]
                              ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPluginResult.m:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSData+Base64.h:45:1: note: 'cdv_base64EncodedString' has been explicitly marked deprecated here
- (NSString*)cdv_base64EncodedString CDV_DEPRECATED(3.9.2, "Use NSData base64EncodedStringWithOptions instead. This will be removed in 4.0.0");
^
1 warning generated.

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.o Classes/CDVPlugin.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPlugin.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.o
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPlugin.m:41:18: warning: 'initWithWebView:' is deprecated: Deprecated in Cordova 3.9.2. Use pluginInitialize method instead. This will be removed in 4.0.0 [-Wdeprecated-declarations]
    return [self initWithWebView:theWebView];
                 ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPlugin.m:20:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPlugin.h:41:1: note: 'initWithWebView:' has been explicitly marked deprecated here
- (CDVPlugin*)initWithWebView:(UIWebView*)theWebView CDV_DEPRECATED(3.9.2, "Use pluginInitialize method instead. This will be removed in 4.0.0");
^
1 warning generated.

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.o Classes/NSMutableArray+QueueAdditions.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSMutableArray+QueueAdditions.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.o Classes/CDVWhitelist.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVWhitelist.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.o Classes/CDVURLProtocol.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVURLProtocol.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.o
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVURLProtocol.m:81:37: warning: 'whitelist' is deprecated: Deprecated in Cordova 3.9.2. Use URLisAllowed to check specific URL. This will be removed in 4.0.0 [-Wdeprecated-declarations]
        gWhitelist = viewController.whitelist;
                                    ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVURLProtocol.m:27:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:44:55: note: 'whitelist' has been explicitly marked deprecated here
@property (nonatomic, readonly, strong) CDVWhitelist* whitelist CDV_DEPRECATED(3.9.2, "Use URLisAllowed to check specific URL. This will be removed in 4.0.0"); // readonly for public
                                                      ^
1 warning generated.

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.o Classes/CDVViewController.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.o
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:84:15: warning: 'printMultitaskingInfo' is deprecated: Deprecated in Cordova 3.9.2. This will be removed in 4.0.0 [-Wdeprecated-declarations]
        [self printMultitaskingInfo];
              ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:67:1: note: 'printMultitaskingInfo' has been explicitly marked deprecated here
- (void)printMultitaskingInfo CDV_DEPRECATED(3.9.2, "This will be removed in 4.0.0");
^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:157:14: warning: 'whitelist' is deprecated: Deprecated in Cordova 3.9.2. Use URLisAllowed to check specific URL. This will be removed in 4.0.0 [-Wdeprecated-declarations]
    if (self.whitelist == nil) {
             ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:44:55: note: 'whitelist' has been explicitly marked deprecated here
@property (nonatomic, readonly, strong) CDVWhitelist* whitelist CDV_DEPRECATED(3.9.2, "Use URLisAllowed to check specific URL. This will be removed in 4.0.0"); // readonly for public
                                                      ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:161:18: warning: 'whitelist' is deprecated: Deprecated in Cordova 3.9.2. Use URLisAllowed to check specific URL. This will be removed in 4.0.0 [-Wdeprecated-declarations]
    return [self.whitelist URLIsAllowed:url];
                 ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:44:55: note: 'whitelist' has been explicitly marked deprecated here
@property (nonatomic, readonly, strong) CDVWhitelist* whitelist CDV_DEPRECATED(3.9.2, "Use URLisAllowed to check specific URL. This will be removed in 4.0.0"); // readonly for public
                                                      ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:189:10: warning: 'whitelist' is deprecated: Deprecated in Cordova 3.9.2. Use URLisAllowed to check specific URL. This will be removed in 4.0.0 [-Wdeprecated-declarations]
    self.whitelist = [[CDVWhitelist alloc] initWithArray:delegate.whitelistHosts];
         ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:44:55: note: 'whitelist' has been explicitly marked deprecated here
@property (nonatomic, readonly, strong) CDVWhitelist* whitelist CDV_DEPRECATED(3.9.2, "Use URLisAllowed to check specific URL. This will be removed in 4.0.0"); // readonly for public
                                                      ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:217:18: warning: 'loadFromString' is deprecated: Deprecated in Cordova 3.9.2. This will be removed in 4.0.0 [-Wdeprecated-declarations]
            self.loadFromString = YES;
                 ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:45:46: note: 'loadFromString' has been explicitly marked deprecated here
@property (nonatomic, readonly, assign) BOOL loadFromString CDV_DEPRECATED(3.9.2, "This will be removed in 4.0.0");
                                             ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:278:15: warning: 'createGapView' is deprecated: Deprecated in Cordova 3.9.2. This will be removed in 4.0.0 [-Wdeprecated-declarations]
        [self createGapView];
              ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:68:1: note: 'createGapView' has been explicitly marked deprecated here
- (void)createGapView CDV_DEPRECATED(3.9.2, "This will be removed in 4.0.0");
^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:304:55: warning: 'initWithWebView:' is deprecated: Deprecated in Cordova 3.9.2. Use pluginInitialize method instead. This will be removed in 4.0.0 [-Wdeprecated-declarations]
        [self registerPlugin:[[CDVLocalStorage alloc] initWithWebView:self.webView] withClassName:NSStringFromClass([CDVLocalStorage class])];
                                                      ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:22:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPlugin.h:41:1: note: 'initWithWebView:' has been explicitly marked deprecated here
- (CDVPlugin*)initWithWebView:(UIWebView*)theWebView CDV_DEPRECATED(3.9.2, "Use pluginInitialize method instead. This will be removed in 4.0.0");
^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:464:52: warning: 'initWithWebView:' is deprecated: Deprecated in Cordova 3.9.2. Use pluginInitialize method instead. This will be removed in 4.0.0 [-Wdeprecated-declarations]
    [self registerPlugin:[[CDVHandleOpenURL alloc] initWithWebView:self.webView] withClassName:NSStringFromClass([CDVHandleOpenURL class])];
                                                   ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:22:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPlugin.h:41:1: note: 'initWithWebView:' has been explicitly marked deprecated here
- (CDVPlugin*)initWithWebView:(UIWebView*)theWebView CDV_DEPRECATED(3.9.2, "Use pluginInitialize method instead. This will be removed in 4.0.0");
^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:784:19: warning: 'loadFromString' is deprecated: Deprecated in Cordova 3.9.2. This will be removed in 4.0.0 [-Wdeprecated-declarations]
    else if (self.loadFromString == YES) {
                  ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:45:46: note: 'loadFromString' has been explicitly marked deprecated here
@property (nonatomic, readonly, assign) BOOL loadFromString CDV_DEPRECATED(3.9.2, "This will be removed in 4.0.0");
                                             ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:785:14: warning: 'loadFromString' is deprecated: Deprecated in Cordova 3.9.2. This will be removed in 4.0.0 [-Wdeprecated-declarations]
        self.loadFromString = NO;
             ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:45:46: note: 'loadFromString' has been explicitly marked deprecated here
@property (nonatomic, readonly, assign) BOOL loadFromString CDV_DEPRECATED(3.9.2, "This will be removed in 4.0.0");
                                             ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:814:19: warning: 'whitelist' is deprecated: Deprecated in Cordova 3.9.2. Use URLisAllowed to check specific URL. This will be removed in 4.0.0 [-Wdeprecated-declarations]
        if ([self.whitelist schemeIsAllowed:[url scheme]]) {
                  ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:44:55: note: 'whitelist' has been explicitly marked deprecated here
@property (nonatomic, readonly, strong) CDVWhitelist* whitelist CDV_DEPRECATED(3.9.2, "Use URLisAllowed to check specific URL. This will be removed in 4.0.0"); // readonly for public
                                                      ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:815:26: warning: 'whitelist' is deprecated: Deprecated in Cordova 3.9.2. Use URLisAllowed to check specific URL. This will be removed in 4.0.0 [-Wdeprecated-declarations]
            return [self.whitelist URLIsAllowed:url];
                         ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:23:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:44:55: note: 'whitelist' has been explicitly marked deprecated here
@property (nonatomic, readonly, strong) CDVWhitelist* whitelist CDV_DEPRECATED(3.9.2, "Use URLisAllowed to check specific URL. This will be removed in 4.0.0"); // readonly for public
                                                      ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:897:52: warning: 'initWithWebView:' is deprecated: Deprecated in Cordova 3.9.2. Use pluginInitialize method instead. This will be removed in 4.0.0 [-Wdeprecated-declarations]
        obj = [[NSClassFromString(className)alloc] initWithWebView:webView];
                                                   ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.m:21:
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDV.h:22:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVPlugin.h:41:1: note: 'initWithWebView:' has been explicitly marked deprecated here
- (CDVPlugin*)initWithWebView:(UIWebView*)theWebView CDV_DEPRECATED(3.9.2, "Use pluginInitialize method instead. This will be removed in 4.0.0");
^
13 warnings generated.

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.o Classes/CDVLocalStorage.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVLocalStorage.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/UIDevice+Extensions.o Classes/UIDevice+Extensions.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/UIDevice+Extensions.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/UIDevice+Extensions.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/UIDevice+Extensions.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/UIDevice+Extensions.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSArray+Comparisons.o Classes/NSArray+Comparisons.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSArray+Comparisons.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSArray+Comparisons.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/NSArray+Comparisons.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSArray+Comparisons.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.o Classes/CDVCommandQueue.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandQueue.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.o Classes/CDVJSON_private.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVJSON_private.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.o Classes/CDVCommandDelegateImpl.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandDelegateImpl.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.o
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandDelegateImpl.m:171:30: warning: 'whitelist' is deprecated: Deprecated in Cordova 3.9.2. Use URLisAllowed to check specific URL. This will be removed in 4.0.0 [-Wdeprecated-declarations]
    return ![_viewController.whitelist schemeIsAllowed:[url scheme]] ||
                             ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandDelegateImpl.m:24:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:44:55: note: 'whitelist' has been explicitly marked deprecated here
@property (nonatomic, readonly, strong) CDVWhitelist* whitelist CDV_DEPRECATED(3.9.2, "Use URLisAllowed to check specific URL. This will be removed in 4.0.0"); // readonly for public
                                                      ^
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandDelegateImpl.m:172:29: warning: 'whitelist' is deprecated: Deprecated in Cordova 3.9.2. Use URLisAllowed to check specific URL. This will be removed in 4.0.0 [-Wdeprecated-declarations]
           [_viewController.whitelist URLIsAllowed:url logFailure:NO];
                            ^
In file included from /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVCommandDelegateImpl.m:24:
/Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVViewController.h:44:55: note: 'whitelist' has been explicitly marked deprecated here
@property (nonatomic, readonly, strong) CDVWhitelist* whitelist CDV_DEPRECATED(3.9.2, "Use URLisAllowed to check specific URL. This will be removed in 4.0.0"); // readonly for public
                                                      ^
2 warnings generated.

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.o Classes/CDVConfigParser.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVConfigParser.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON.o Classes/CDVJSON.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVJSON.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.o Classes/CDVUserAgentUtil.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVUserAgentUtil.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.o Classes/CDVHandleOpenURL.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVHandleOpenURL.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWebViewDelegate.o Classes/CDVWebViewDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWebViewDelegate.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWebViewDelegate.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVWebViewDelegate.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWebViewDelegate.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.o Classes/CDVTimer.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/CordovaLib_Prefix-cdvxzzrppeyhwybmydexviimbgih/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.dia -c /Users/thali/Github/testBuild/platforms/ios/CordovaLib/Classes/CDVTimer.m -o /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.o

Libtool /Users/thali/Github/testBuild/platforms/ios/build/device/libCordova.a normal armv7
    cd /Users/thali/Github/testBuild/platforms/ios/CordovaLib
    export IPHONEOS_DEPLOYMENT_TARGET=6.0
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/libtool -static -arch_only armv7 -syslibroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -L/Users/thali/Github/testBuild/platforms/ios/build/device -filelist /Users/thali/Github/testBuild/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/Cordova.LinkFileList -o /Users/thali/Github/testBuild/platforms/ios/build/device/libCordova.a

=== BUILD TARGET HelloWorld OF PROJECT HelloWorld WITH CONFIGURATION Debug ===

Check dependencies

Write auxiliary files
write-file /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap
/bin/mkdir -p /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx
write-file /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch.pch.hash-criteria
write-file /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Script-304B58A110DAC018002A0835.sh
chmod 0755 /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Script-304B58A110DAC018002A0835.sh
write-file /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap
write-file /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld.hmap
write-file /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap
write-file /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap
write-file /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-non-framework-target-headers.hmap
/bin/mkdir -p /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7
write-file /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/HelloWorld.LinkFileList

Create product structure
/bin/mkdir -p /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app

PhaseScriptExecution Copy\ www\ directory build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Script-304B58A110DAC018002A0835.sh
    cd /Users/thali/Github/testBuild/platforms/ios
    /bin/sh -c /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Script-304B58A110DAC018002A0835.sh

CopyPNGFile build/device/HelloWorld.app/icon-76.png HelloWorld/Resources/icons/icon-76.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-76.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-76.png

CopyPNGFile build/device/HelloWorld.app/icon-40@2x.png HelloWorld/Resources/icons/icon-40@2x.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-40@2x.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-40@2x.png

CopyPNGFile build/device/HelloWorld.app/icon-72.png HelloWorld/Resources/icons/icon-72.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-72.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-72.png

CopyPNGFile build/device/HelloWorld.app/Default-736h.png HelloWorld/Resources/splash/Default-736h.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default-736h.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default-736h.png

CopyPNGFile build/device/HelloWorld.app/icon.png HelloWorld/Resources/icons/icon.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon.png

CopyPNGFile build/device/HelloWorld.app/icon@2x.png HelloWorld/Resources/icons/icon@2x.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon@2x.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon@2x.png

CompileXIB HelloWorld/Classes/MainViewController.xib
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    export XCODE_DEVELOPER_USR_PATH=/Applications/Xcode.app/Contents/Developer/usr/bin/..
    /Applications/Xcode.app/Contents/Developer/usr/bin/ibtool --errors --warnings --notices --module HelloWorld --output-partial-info-plist /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/MainViewController-PartialInfo.plist --auto-activate-custom-fonts --target-device iphone --target-device ipad --minimum-deployment-target 6.0 --output-format human-readable-text --compile /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/MainViewController.nib /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Classes/MainViewController.xib

CopyPNGFile build/device/HelloWorld.app/icon-50.png HelloWorld/Resources/icons/icon-50.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-50.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-50.png

CopyPNGFile build/device/HelloWorld.app/icon-60@2x.png HelloWorld/Resources/icons/icon-60@2x.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-60@2x.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-60@2x.png

CopyPNGFile build/device/HelloWorld.app/icon-small.png HelloWorld/Resources/icons/icon-small.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-small.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-small.png

CopyPNGFile build/device/HelloWorld.app/Default-Landscape@2x~ipad.png HelloWorld/Resources/splash/Default-Landscape@2x~ipad.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default-Landscape@2x~ipad.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default-Landscape@2x~ipad.png

CopyPNGFile build/device/HelloWorld.app/Default-Landscape~ipad.png HelloWorld/Resources/splash/Default-Landscape~ipad.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default-Landscape~ipad.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default-Landscape~ipad.png

CopyPNGFile build/device/HelloWorld.app/Default-Portrait@2x~ipad.png HelloWorld/Resources/splash/Default-Portrait@2x~ipad.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default-Portrait@2x~ipad.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default-Portrait@2x~ipad.png

CopyPNGFile build/device/HelloWorld.app/icon-small@2x.png HelloWorld/Resources/icons/icon-small@2x.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-small@2x.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-small@2x.png

CopyPNGFile build/device/HelloWorld.app/Default-Portrait~ipad.png HelloWorld/Resources/splash/Default-Portrait~ipad.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default-Portrait~ipad.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default-Portrait~ipad.png

CopyPNGFile build/device/HelloWorld.app/Default-667h.png HelloWorld/Resources/splash/Default-667h.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default-667h.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default-667h.png

CopyPNGFile build/device/HelloWorld.app/icon-40.png HelloWorld/Resources/icons/icon-40.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-40.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-40.png

CopyPNGFile build/device/HelloWorld.app/Default@2x~iphone.png HelloWorld/Resources/splash/Default@2x~iphone.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default@2x~iphone.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default@2x~iphone.png

CopyPNGFile build/device/HelloWorld.app/icon-60.png HelloWorld/Resources/icons/icon-60.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-60.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-60.png

CopyPNGFile build/device/HelloWorld.app/Default~iphone.png HelloWorld/Resources/splash/Default~iphone.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default~iphone.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default~iphone.png

CopyPNGFile build/device/HelloWorld.app/Default-568h@2x~iphone.png HelloWorld/Resources/splash/Default-568h@2x~iphone.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default-568h@2x~iphone.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default-568h@2x~iphone.png

CopyPNGFile build/device/HelloWorld.app/Default-Landscape-736h.png HelloWorld/Resources/splash/Default-Landscape-736h.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/splash/Default-Landscape-736h.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Default-Landscape-736h.png

CopyPNGFile build/device/HelloWorld.app/icon-60@3x.png HelloWorld/Resources/icons/icon-60@3x.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-60@3x.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-60@3x.png

CopyPNGFile build/device/HelloWorld.app/icon-50@2x.png HelloWorld/Resources/icons/icon-50@2x.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-50@2x.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-50@2x.png

CopyPNGFile build/device/HelloWorld.app/icon-76@2x.png HelloWorld/Resources/icons/icon-76@2x.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-76@2x.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-76@2x.png

CopyPNGFile build/device/HelloWorld.app/icon-72@2x.png HelloWorld/Resources/icons/icon-72@2x.png
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/copypng -compress /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/icons/icon-72@2x.png /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/icon-72@2x.png

CpResource HelloWorld/Resources/jxcore_cordova.js build/device/HelloWorld.app/jxcore_cordova.js
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Resources/jxcore_cordova.js /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app

ProcessInfoPlistFile build/device/HelloWorld.app/Info.plist HelloWorld/HelloWorld-Info.plist
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-infoPlistUtility /Users/thali/Github/testBuild/platforms/ios/HelloWorld/HelloWorld-Info.plist -genpkginfo /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/PkgInfo -expandbuildsettings -format binary -platform iphoneos -additionalcontentfile /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/MainViewController-PartialInfo.plist -o /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/Info.plist

ProcessPCH build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch.pch HelloWorld/HelloWorld-Prefix.pch normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c-header -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/testBuild/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/testBuild/platforms/ios/build/device -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -MD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch.d -c /Users/thali/Github/testBuild/platforms/ios/HelloWorld/HelloWorld-Prefix.pch -o /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch.pch --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch.dia

CompileC build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/main.o HelloWorld/main.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/testBuild/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/testBuild/platforms/ios/build/device -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/main.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/main.dia -c /Users/thali/Github/testBuild/platforms/ios/HelloWorld/main.m -o /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/main.o

CompileC build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/AppDelegate.o HelloWorld/Classes/AppDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/testBuild/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/testBuild/platforms/ios/build/device -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/AppDelegate.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/AppDelegate.dia -c /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Classes/AppDelegate.m -o /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/AppDelegate.o

CompileC build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/CDVJXcore.o HelloWorld/Plugins/io.jxcore.node/CDVJXcore.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/testBuild/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/testBuild/platforms/ios/build/device -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/CDVJXcore.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/CDVJXcore.dia -c /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Plugins/io.jxcore.node/CDVJXcore.m -o /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/CDVJXcore.o

CompileC build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/MainViewController.o HelloWorld/Classes/MainViewController.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/testBuild/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/testBuild/platforms/ios/build/device -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/MainViewController.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/MainViewController.dia -c /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Classes/MainViewController.m -o /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/MainViewController.o

CompileC build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/JXcore.o HelloWorld/Plugins/io.jxcore.node/JXcore.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/testBuild/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/testBuild/platforms/ios/build/device -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/JXcore.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/JXcore.dia -c /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Plugins/io.jxcore.node/JXcore.m -o /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/JXcore.o

CompileC build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/JXMobile.o HelloWorld/Plugins/io.jxcore.node/JXMobile.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/testBuild/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/testBuild/platforms/ios/build/device -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/JXMobile.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/JXMobile.dia -c /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Plugins/io.jxcore.node/JXMobile.m -o /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/JXMobile.o

CompileC build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/Reachability.o HelloWorld/Plugins/io.jxcore.node/Reachability.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/testBuild/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -gmodules -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=6.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-generated-files.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-own-target-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-all-target-headers.hmap -iquote /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld-project-headers.hmap -I/Users/thali/Github/testBuild/platforms/ios/build/device/include -I/Users/thali/Github/testBuild/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/testBuild/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/testBuild/platforms/ios/build/device -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources/armv7 -I/Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/DerivedSources -F/Users/thali/Github/testBuild/platforms/ios/build/device -include /Users/thali/Github/testBuild/platforms/ios/build/sharedpch/HelloWorld-Prefix-akkfoxblhavzfvbuysdheccloabx/HelloWorld-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/Reachability.d --serialize-diagnostics /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/Reachability.dia -c /Users/thali/Github/testBuild/platforms/ios/HelloWorld/Plugins/io.jxcore.node/Reachability.m -o /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/Reachability.o

Ld build/device/HelloWorld.app/HelloWorld normal armv7
    cd /Users/thali/Github/testBuild/platforms/ios
    export IPHONEOS_DEPLOYMENT_TARGET=6.0
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -arch armv7 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk -L/Users/thali/Github/testBuild/platforms/ios/build/device -L/Users/thali/Github/testBuild/platforms/ios/HelloWorld/Plugins/io.jxcore.node -F/Users/thali/Github/testBuild/platforms/ios/build/device -filelist /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/HelloWorld.LinkFileList -miphoneos-version-min=6.0 -dead_strip -weak_framework CoreFoundation -weak_framework UIKit -weak_framework AVFoundation -weak_framework CoreMedia -weak-lSystem -ObjC -fobjc-arc -fobjc-link-runtime -framework AssetsLibrary /Users/thali/Github/testBuild/platforms/ios/build/device/libCordova.a -framework CoreGraphics -framework MobileCoreServices -lcares -lchrome_zlib -lhttp_parser -ljx -lmozjs -lopenssl -lsqlite3 -luv -lleveldb -lleveldown -lsnappy -framework SystemConfiguration -lstdc++.6.0.9 -framework CFNetwork -framework Foundation -framework Security -Xlinker -dependency_info -Xlinker /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/Objects-normal/armv7/HelloWorld_dependency_info.dat -o /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/HelloWorld

GenerateDSYMFile build/device/HelloWorld.app.dSYM build/device/HelloWorld.app/HelloWorld
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/dsymutil /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/HelloWorld -o /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app.dSYM

ProcessProductPackaging /Users/thali/Library/MobileDevice/Provisioning\ Profiles/3de7a3bd-fb3e-44f1-8ed9-381a00c5aefd.mobileprovision build/device/HelloWorld.app/embedded.mobileprovision
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-productPackagingUtility /Users/thali/Library/MobileDevice/Provisioning\ Profiles/3de7a3bd-fb3e-44f1-8ed9-381a00c5aefd.mobileprovision -o /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app/embedded.mobileprovision

Touch build/device/HelloWorld.app
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    /usr/bin/touch -c /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app

ProcessProductPackaging /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk/Entitlements.plist build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld.app.xcent
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-productPackagingUtility /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk/Entitlements.plist -entitlements -format xml -o /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld.app.xcent

CodeSign build/device/HelloWorld.app
    cd /Users/thali/Github/testBuild/platforms/ios
    export CODESIGN_ALLOCATE=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/codesign_allocate
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    
Signing Identity:     "iPhone Developer: Oguz Bastemur (3VQK56QCRA)"
Provisioning Profile: "iOSTeam Provisioning Profile: com.example.*"
                      (3de7a3bd-fb3e-44f1-8ed9-381a00c5aefd)

    /usr/bin/codesign --force --sign E96432CB6BA20AEA3948490158A302339BD72206 --entitlements /Users/thali/Github/testBuild/platforms/ios/build/HelloWorld.build/Debug-iphoneos/HelloWorld.build/HelloWorld.app.xcent --timestamp=none /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app

Validate build/device/HelloWorld.app
    cd /Users/thali/Github/testBuild/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin"
    export PRODUCT_TYPE=com.apple.product-type.application
    builtin-validationUtility /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app

** BUILD SUCCEEDED **

Packaging application: '/Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app'
Arguments: verbose=1  output=/Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.ipa  
Environment variables:
VERSIONER_PERL_VERSION = 5.18
SDKROOT = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.0.sdk
SSH_CLIENT = 192.168.1.100 55673 22
SHLVL = 3
LC_CTYPE = en_US.UTF-8
SHELL = /bin/bash
PATH = /usr/bin:/bin:/usr/sbin:/sbin
PWD = /Users/thali/Github/testBuild
HOME = /Users/thali
TMPDIR = /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/
USER = thali
MAIL = /var/mail/thali
SSH_CONNECTION = 192.168.1.100 55673 192.168.1.20 22
LOGNAME = thali
__CF_USER_TEXT_ENCODING = 0x1F5:0x0:0x0
VERSIONER_PERL_PREFER_32_BIT = no
_ = /usr/bin/cordova

Output directory: '/Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.ipa'
Temporary Directory: '/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/Jo7etqKywe'  (will NOT be deleted on exit when verbose set)
+ /bin/cp -Rp /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/Jo7etqKywe/Payload
Program /bin/cp returned 0 : []
### Checking original app
+ /usr/bin/codesign --verify -vvvv /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app
Program /usr/bin/codesign returned 1 : [/Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app: CSSMERR_TP_NOT_TRUSTED
In architecture: armv7
]
Codesign check fails : /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.app: CSSMERR_TP_NOT_TRUSTED
In architecture: armv7

Done checking the original app
+ /usr/bin/zip --symlinks --verbose --recurse-paths /Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.ipa .
Program /usr/bin/zip returned 0 : [  adding: Payload/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/_CodeSignature/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/_CodeSignature/CodeResources 	(in=170235) (out=34022) (deflated 80%)
  adding: Payload/HelloWorld.app/config.xml	(in=1626) (out=559) (deflated 66%)
  adding: Payload/HelloWorld.app/Default-568h@2x~iphone.png	(in=61990) (out=56184) (deflated 9%)
  adding: Payload/HelloWorld.app/Default-667h.png	(in=52100) (out=44188) (deflated 15%)
  adding: Payload/HelloWorld.app/Default-736h.png	(in=62285) (out=47468) (deflated 24%)
  adding: Payload/HelloWorld.app/Default-Landscape-736h.png	(in=63597) (out=49356) (deflated 22%)
  adding: Payload/HelloWorld.app/Default-Landscape@2x~ipad.png 	(in=161722) (out=137188) (deflated 15%)
  adding: Payload/HelloWorld.app/Default-Landscape~ipad.png 	(in=76512) (out=69582) (deflated 9%)
  adding: Payload/HelloWorld.app/Default-Portrait@2x~ipad.png 	(in=154923) (out=134644) (deflated 13%)
  adding: Payload/HelloWorld.app/Default-Portrait~ipad.png 	(in=74890) (out=68210) (deflated 9%)
  adding: Payload/HelloWorld.app/Default@2x~iphone.png	(in=55319) (out=50350) (deflated 9%)
  adding: Payload/HelloWorld.app/Default~iphone.png	(in=20021) (out=18443) (deflated 8%)
  adding: Payload/HelloWorld.app/embedded.mobileprovision	(in=7545) (out=5075) (deflated 33%)
  adding: Payload/HelloWorld.app/HelloWorld 	(in=6342336) (out=2835525) (deflated 55%)
  adding: Payload/HelloWorld.app/icon-40.png	(in=4450) (out=4162) (deflated 6%)
  adding: Payload/HelloWorld.app/icon-40@2x.png	(in=8883) (out=8487) (deflated 4%)
  adding: Payload/HelloWorld.app/icon-50.png	(in=5557) (out=5251) (deflated 6%)
  adding: Payload/HelloWorld.app/icon-50@2x.png	(in=11331) (out=10902) (deflated 4%)
  adding: Payload/HelloWorld.app/icon-60.png	(in=6838) (out=6484) (deflated 5%)
  adding: Payload/HelloWorld.app/icon-60@2x.png	(in=14152) (out=13609) (deflated 4%)
  adding: Payload/HelloWorld.app/icon-60@3x.png	(in=33390) (out=32762) (deflated 2%)
  adding: Payload/HelloWorld.app/icon-72.png	(in=8045) (out=7670) (deflated 5%)
  adding: Payload/HelloWorld.app/icon-72@2x.png	(in=17926) (out=17376) (deflated 3%)
  adding: Payload/HelloWorld.app/icon-76.png	(in=8463) (out=8093) (deflated 4%)
  adding: Payload/HelloWorld.app/icon-76@2x.png	(in=16629) (out=16026) (deflated 4%)
  adding: Payload/HelloWorld.app/icon-small.png	(in=3349) (out=3075) (deflated 8%)
  adding: Payload/HelloWorld.app/icon-small@2x.png	(in=6585) (out=6245) (deflated 5%)
  adding: Payload/HelloWorld.app/icon.png	(in=5977) (out=5629) (deflated 6%)
  adding: Payload/HelloWorld.app/icon@2x.png	(in=13012) (out=12564) (deflated 3%)
  adding: Payload/HelloWorld.app/Info.plist	(in=1676) (out=1112) (deflated 34%)
  adding: Payload/HelloWorld.app/jxcore_cordova.js	(in=13106) (out=3553) (deflated 73%)
  adding: Payload/HelloWorld.app/MainViewController.nib	(in=926) (out=614) (deflated 34%)
  adding: Payload/HelloWorld.app/PkgInfo	(in=8) (out=8) (stored 0%)
  adding: Payload/HelloWorld.app/www/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/cordova-js-src/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/cordova-js-src/exec.js	(in=12363) (out=4372) (deflated 65%)
  adding: Payload/HelloWorld.app/www/cordova-js-src/platform.js	(in=943) (out=541) (deflated 43%)
  adding: Payload/HelloWorld.app/www/cordova.js	(in=63609) (out=15632) (deflated 75%)
  adding: Payload/HelloWorld.app/www/cordova_plugins.js	(in=403) (out=236) (deflated 41%)
  adding: Payload/HelloWorld.app/www/index.html	(in=2543) (out=1114) (deflated 56%)
  adding: Payload/HelloWorld.app/www/jxcore/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/app.js	(in=1546) (out=733) (deflated 53%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/json-nice/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/json-nice/index.js	(in=1972) (out=505) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/json-nice/package.json	(in=1103) (out=464) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/json-nice/README.md	(in=133) (out=112) (deflated 16%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/.eslintrc	(in=1444) (out=648) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/.npmignore	(in=28) (out=28) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/.travis.yml	(in=435) (out=234) (deflated 46%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/CHANGELOG.md	(in=49527) (out=13667) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/CONTRIBUTING.md	(in=1821) (out=891) (deflated 51%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/disabled.appveyor.yml	(in=940) (out=497) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/examples/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/examples/README.md	(in=2463) (out=1049) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/index.js	(in=3943) (out=1376) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/auth.js	(in=4214) (out=1463) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/cookies.js	(in=935) (out=371) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/getProxyFromURI.js	(in=2268) (out=884) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/har.js	(in=4787) (out=1420) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/helpers.js	(in=1594) (out=626) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/multipart.js	(in=2562) (out=829) (deflated 68%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/oauth.js	(in=3954) (out=1378) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/querystring.js	(in=1333) (out=399) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/redirect.js	(in=4464) (out=1433) (deflated 68%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/lib/tunnel.js	(in=4839) (out=1422) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/LICENSE	(in=9140) (out=3306) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin/har-validator	(in=1234) (out=551) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin/uuid	(in=595) (out=300) (deflated 50%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/index.js	(in=3896) (out=1312) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/LICENSE	(in=9140) (out=3306) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/package.json	(in=1418) (out=538) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/README.md	(in=130) (out=110) (deflated 15%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.jshintrc	(in=1147) (out=360) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.npmignore	(in=13) (out=13) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.travis.yml	(in=211) (out=152) (deflated 28%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/bl.js	(in=4949) (out=1473) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/LICENSE.md	(in=1211) (out=681) (deflated 44%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.npmignore	(in=36) (out=36) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.travis.yml	(in=1441) (out=578) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.zuul.yml	(in=9) (out=9) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/stream.markdown	(in=53246) (out=15015) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/wg-meetings/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/wg-meetings/2015-01-30.md	(in=2280) (out=1101) (deflated 52%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/duplex.js	(in=52) (out=52) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_duplex.js	(in=1868) (out=761) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_passthrough.js	(in=608) (out=317) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_readable.js	(in=25381) (out=7714) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_transform.js	(in=6413) (out=2351) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_writable.js	(in=13597) (out=4222) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/LICENSE	(in=1096) (out=634) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/float.patch	(in=16278) (out=4986) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/lib/util.js	(in=3040) (out=1183) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/package.json	(in=1359) (out=534) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/README.md	(in=67) (out=65) (deflated 3%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/util.js	(in=3012) (out=1168) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/inherits.js	(in=42) (out=42) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/inherits_browser.js	(in=672) (out=283) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/LICENSE	(in=749) (out=462) (deflated 38%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/package.json	(in=1220) (out=510) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/README.md	(in=1625) (out=798) (deflated 51%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/test.js	(in=510) (out=222) (deflated 56%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/build/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/build/build.js	(in=4089) (out=1344) (deflated 67%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/component.json	(in=470) (out=248) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/index.js	(in=120) (out=107) (deflated 11%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/package.json	(in=1288) (out=507) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/README.md	(in=1557) (out=887) (deflated 43%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/.travis.yml	(in=81) (out=49) (deflated 40%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/index.js	(in=268) (out=172) (deflated 36%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/package.json	(in=1317) (out=527) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/readme.md	(in=451) (out=251) (deflated 44%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/test.js	(in=367) (out=183) (deflated 50%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/.npmignore	(in=11) (out=11) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/index.js	(in=7796) (out=2829) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/LICENSE	(in=1076) (out=625) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/package.json	(in=1358) (out=560) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/README.md	(in=498) (out=306) (deflated 39%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/browser.js	(in=1483) (out=596) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/History.md	(in=180) (out=115) (deflated 36%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/LICENSE	(in=1102) (out=655) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/node.js	(in=123) (out=104) (deflated 15%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/package.json	(in=1451) (out=588) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/README.md	(in=1666) (out=900) (deflated 46%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/package.json	(in=1946) (out=778) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/passthrough.js	(in=57) (out=57) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/readable.js	(in=521) (out=243) (deflated 53%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/README.md	(in=1928) (out=878) (deflated 54%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/transform.js	(in=55) (out=55) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/writable.js	(in=54) (out=54) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/package.json	(in=1674) (out=729) (deflated 56%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/README.md	(in=10172) (out=3337) (deflated 67%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/basic-test.js	(in=12783) (out=2260) (deflated 82%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/sauce.js	(in=1827) (out=498) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/test.js	(in=291) (out=168) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/index.js	(in=1759) (out=601) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/LICENSE	(in=9113) (out=3300) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/package.json	(in=1540) (out=614) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/README.md	(in=1173) (out=539) (deflated 54%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/test.js	(in=987) (out=362) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/lib/combined_stream.js	(in=4300) (out=1058) (deflated 75%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/License	(in=1085) (out=639) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/.npmignore	(in=5) (out=5) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/lib/delayed_stream.js	(in=2319) (out=729) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/License	(in=1085) (out=639) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/Makefile	(in=57) (out=54) (deflated 5%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/package.json	(in=1653) (out=651) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/Readme.md	(in=3871) (out=1557) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/package.json	(in=1730) (out=653) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/Readme.md	(in=4551) (out=1606) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.eslintrc	(in=5389) (out=1686) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.jscs.json	(in=2555) (out=788) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.npmignore	(in=4) (out=4) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.travis.yml	(in=879) (out=273) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/CHANGELOG.md	(in=2162) (out=984) (deflated 54%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/component.json	(in=581) (out=332) (deflated 43%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/index.js	(in=2266) (out=895) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/LICENSE	(in=1081) (out=634) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/package.json	(in=1891) (out=743) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/README.md	(in=2360) (out=1014) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/index.js	(in=4176) (out=1269) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/LICENSE	(in=9140) (out=3306) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/package.json	(in=1580) (out=634) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/README.md	(in=163) (out=121) (deflated 26%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib/browser.js	(in=26) (out=26) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib/form_data.js	(in=10231) (out=3299) (deflated 68%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/License	(in=1118) (out=662) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/CHANGELOG.md	(in=4277) (out=1898) (deflated 56%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/lib/async.js	(in=37225) (out=7606) (deflated 80%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/LICENSE	(in=1063) (out=627) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/package.json	(in=3001) (out=1123) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/package.json	(in=2134) (out=831) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/Readme.md	(in=5844) (out=2151) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/bin/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/bin/har-validator	(in=1234) (out=551) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/error.js	(in=186) (out=109) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/index.js	(in=776) (out=327) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cache.json	(in=187) (out=100) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cacheEntry.json	(in=494) (out=189) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/content.json	(in=377) (out=137) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cookie.json	(in=498) (out=174) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/creator.json	(in=230) (out=107) (deflated 53%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/entry.json	(in=931) (out=321) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/har.json	(in=117) (out=83) (deflated 29%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/index.js	(in=1752) (out=452) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/log.json	(in=493) (out=168) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/page.json	(in=577) (out=234) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/pageTimings.json	(in=225) (out=105) (deflated 53%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/postData.json	(in=654) (out=183) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/record.json	(in=226) (out=105) (deflated 54%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/request.json	(in=853) (out=243) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/response.json	(in=807) (out=233) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/timings.json	(in=565) (out=149) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/LICENSE	(in=755) (out=472) (deflated 37%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/changelog.md	(in=35822) (out=9536) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/bluebird.js 	(in=151827) (out=30294) (deflated 80%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/bluebird.min.js 	(in=69727) (out=19744) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/any.js	(in=421) (out=185) (deflated 56%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/assert.js	(in=1639) (out=616) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/async.js	(in=3953) (out=936) (deflated 76%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/bind.js	(in=2012) (out=586) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/bluebird.js	(in=294) (out=178) (deflated 39%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/call_get.js	(in=4344) (out=1167) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/cancel.js	(in=1398) (out=445) (deflated 68%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/captured_trace.js	(in=15046) (out=3523) (deflated 77%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/catch_filter.js	(in=2074) (out=703) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/context.js	(in=938) (out=315) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/debuggability.js	(in=5073) (out=1316) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/direct_resolve.js	(in=1388) (out=365) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/each.js	(in=298) (out=155) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/errors.js	(in=3618) (out=1121) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/es5.js	(in=1978) (out=588) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/filter.js	(in=314) (out=155) (deflated 51%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/finally.js	(in=2624) (out=692) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/generators.js	(in=4701) (out=1236) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/join.js	(in=3890) (out=1100) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/map.js	(in=4378) (out=1288) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/method.js	(in=1336) (out=501) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/nodeify.js	(in=1636) (out=542) (deflated 67%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/progress.js	(in=2492) (out=781) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise.js	(in=24191) (out=4903) (deflated 80%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise_array.js	(in=4147) (out=1091) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise_resolver.js	(in=3863) (out=1058) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promisify.js	(in=11390) (out=2818) (deflated 75%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/props.js	(in=2172) (out=750) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/queue.js	(in=2354) (out=655) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/race.js	(in=1225) (out=519) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/reduce.js	(in=5023) (out=1318) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/schedule.js	(in=1279) (out=512) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/settle.js	(in=1168) (out=400) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/some.js	(in=3378) (out=915) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/synchronous_inspection.js	(in=2641) (out=554) (deflated 79%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/thenables.js	(in=2344) (out=675) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/timers.js	(in=1602) (out=594) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/using.js	(in=6667) (out=1575) (deflated 76%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/util.js	(in=8633) (out=2442) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/LICENSE	(in=1081) (out=637) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/package.json	(in=2532) (out=993) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/README.md	(in=29675) (out=10330) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/index.js	(in=3155) (out=1336) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/license	(in=1119) (out=651) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/index.js	(in=1254) (out=579) (deflated 54%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/license	(in=1119) (out=651) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/package.json	(in=1730) (out=681) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/readme.md	(in=1448) (out=749) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/index.js	(in=227) (out=176) (deflated 22%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/license	(in=1119) (out=651) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/package.json	(in=1705) (out=641) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/readme.md	(in=548) (out=281) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/index.js	(in=152) (out=121) (deflated 20%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/license	(in=1119) (out=651) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/index.js	(in=135) (out=125) (deflated 7%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/license	(in=1119) (out=651) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/package.json	(in=1867) (out=731) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/readme.md	(in=593) (out=316) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/package.json	(in=1797) (out=695) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/readme.md	(in=856) (out=409) (deflated 52%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/index.js	(in=161) (out=127) (deflated 21%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/license	(in=1119) (out=651) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/index.js	(in=135) (out=125) (deflated 7%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/license	(in=1119) (out=651) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/package.json	(in=1867) (out=731) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/readme.md	(in=593) (out=316) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/package.json	(in=1806) (out=692) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/readme.md	(in=843) (out=401) (deflated 52%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/index.js	(in=901) (out=366) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/license	(in=1119) (out=651) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/package.json	(in=1765) (out=686) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/readme.md	(in=823) (out=435) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/package.json	(in=2143) (out=844) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/readme.md	(in=6050) (out=2627) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/History.md	(in=6266) (out=2377) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/index.js	(in=24300) (out=6824) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/LICENSE	(in=1098) (out=653) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/.npmignore	(in=31) (out=31) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/.travis.yml	(in=61) (out=45) (deflated 26%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/index.js	(in=188) (out=133) (deflated 29%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/LICENSE	(in=1076) (out=634) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/package.json	(in=1311) (out=532) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/README.md	(in=531) (out=258) (deflated 51%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/package.json	(in=1734) (out=684) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/Readme.md	(in=9545) (out=3413) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/.npmignore	(in=30) (out=30) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/.travis.yml	(in=38) (out=34) (deflated 11%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/example.js	(in=430) (out=226) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/formats.js	(in=2342) (out=614) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/index.js	(in=16183) (out=3707) (deflated 77%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/LICENSE	(in=1078) (out=634) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/.npmignore	(in=13) (out=13) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/.travis.yml	(in=38) (out=34) (deflated 11%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/example.js	(in=662) (out=339) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/index.js	(in=1296) (out=451) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/package.json	(in=1401) (out=566) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/README.md	(in=1748) (out=792) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/test.js	(in=796) (out=342) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/.npmignore	(in=13) (out=13) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/.travis.yml	(in=38) (out=34) (deflated 11%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/index.js	(in=287) (out=163) (deflated 43%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/LICENSE	(in=1078) (out=634) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/.npmignore	(in=116) (out=93) (deflated 20%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/is-property.js	(in=11014) (out=2727) (deflated 75%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/LICENSE	(in=1082) (out=638) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/package.json	(in=1441) (out=581) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/README.md	(in=625) (out=345) (deflated 45%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/package.json	(in=1485) (out=564) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/README.md	(in=473) (out=254) (deflated 46%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/test.js	(in=203) (out=117) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/.travis.yml	(in=61) (out=41) (deflated 33%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/jsonpointer.js	(in=1629) (out=560) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/package.json	(in=1353) (out=539) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/README.md	(in=764) (out=404) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/test.js	(in=2778) (out=711) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/.jshintrc	(in=545) (out=230) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/.npmignore	(in=13) (out=13) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/immutable.js	(in=323) (out=173) (deflated 46%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/LICENCE	(in=1056) (out=622) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/Makefile	(in=49) (out=47) (deflated 4%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/mutable.js	(in=308) (out=168) (deflated 45%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/package.json	(in=1862) (out=715) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/README.md	(in=725) (out=417) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/test.js	(in=1356) (out=332) (deflated 76%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/package.json	(in=1707) (out=660) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/README.md	(in=4205) (out=1582) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/require.js	(in=444) (out=226) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/fixtures/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/fixtures/cosmic.js	(in=3900) (out=1304) (deflated 67%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/additionalItems.json	(in=2282) (out=414) (deflated 82%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/additionalProperties.json	(in=2745) (out=424) (deflated 85%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/allOf.json	(in=3025) (out=402) (deflated 87%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/anyOf.json	(in=1608) (out=289) (deflated 82%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/bignum.json	(in=3075) (out=442) (deflated 86%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/default.json	(in=1273) (out=257) (deflated 80%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/definitions.json	(in=854) (out=194) (deflated 77%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/dependencies.json	(in=3139) (out=385) (deflated 88%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/enum.json	(in=1975) (out=374) (deflated 81%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/format.json	(in=4434) (out=686) (deflated 85%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/items.json	(in=1136) (out=263) (deflated 77%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maximum.json	(in=1063) (out=234) (deflated 78%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxItems.json	(in=706) (out=189) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxLength.json	(in=698) (out=181) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxProperties.json	(in=759) (out=202) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minimum.json	(in=1063) (out=236) (deflated 78%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minItems.json	(in=693) (out=183) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minLength.json	(in=696) (out=180) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minProperties.json	(in=725) (out=196) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/multipleOf.json	(in=1525) (out=266) (deflated 83%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/not.json	(in=2266) (out=352) (deflated 84%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/nullAndFormat.json	(in=385) (out=187) (deflated 51%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/nullAndObject.json	(in=316) (out=164) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/oneOf.json	(in=1607) (out=287) (deflated 82%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/pattern.json	(in=582) (out=168) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/patternProperties.json	(in=3365) (out=561) (deflated 83%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/properties.json	(in=2881) (out=437) (deflated 85%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/ref.json	(in=3422) (out=490) (deflated 86%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/refRemote.json	(in=1961) (out=316) (deflated 84%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/required.json	(in=923) (out=215) (deflated 77%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/type.json	(in=9306) (out=622) (deflated 93%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/uniqueItems.json	(in=2613) (out=389) (deflated 85%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema.js	(in=644) (out=289) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/misc.js	(in=9673) (out=1648) (deflated 83%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/package.json	(in=2176) (out=857) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/README.md	(in=8944) (out=1648) (deflated 82%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/.npmignore	(in=215) (out=136) (deflated 37%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/.travis.yml	(in=43) (out=37) (deflated 14%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/bower.json	(in=384) (out=221) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/component.json	(in=335) (out=186) (deflated 44%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/example/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/example/usage.js	(in=2077) (out=804) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images/hawk.png	(in=6945) (out=6851) (deflated 1%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images/logo.png 	(in=71732) (out=71593) (deflated 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/browser.js	(in=26977) (out=7454) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/client.js	(in=10222) (out=2477) (deflated 76%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/crypto.js	(in=3460) (out=1164) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/index.js	(in=366) (out=159) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/server.js	(in=17819) (out=3989) (deflated 78%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/utils.js	(in=3852) (out=1353) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/LICENSE	(in=1660) (out=845) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/.npmignore	(in=178) (out=118) (deflated 34%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/.travis.yml	(in=56) (out=41) (deflated 27%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/CONTRIBUTING.md	(in=105) (out=99) (deflated 6%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/images/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/images/boom.png	(in=29479) (out=29285) (deflated 1%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/lib/index.js	(in=6452) (out=1537) (deflated 76%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/LICENSE	(in=1651) (out=837) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/package.json	(in=1475) (out=633) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/README.md	(in=13804) (out=3112) (deflated 77%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/test/index.js	(in=16207) (out=2313) (deflated 86%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/.npmignore	(in=178) (out=118) (deflated 34%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/.travis.yml	(in=38) (out=34) (deflated 11%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/index.js	(in=34) (out=34) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/lib/index.js	(in=1364) (out=618) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/LICENSE	(in=1660) (out=843) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/Makefile	(in=195) (out=102) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/package.json	(in=1524) (out=617) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/README.md	(in=537) (out=320) (deflated 40%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/test/index.js	(in=2871) (out=697) (deflated 76%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/.npmignore	(in=191) (out=126) (deflated 34%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/.travis.yml	(in=56) (out=41) (deflated 27%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/CONTRIBUTING.md	(in=105) (out=99) (deflated 6%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/images/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/images/hoek.png	(in=37939) (out=37817) (deflated 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/index.js	(in=35) (out=35) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/escape.js	(in=2668) (out=720) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/index.js	(in=24228) (out=5981) (deflated 75%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/LICENSE	(in=1814) (out=915) (deflated 50%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/Makefile	(in=223) (out=108) (deflated 52%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/package.json	(in=1379) (out=593) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/README.md	(in=16706) (out=5697) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/escaper.js	(in=2303) (out=555) (deflated 76%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/index.js 	(in=65598) (out=10178) (deflated 84%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/ignore.txt	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test1.js	(in=15) (out=15) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test2.js	(in=15) (out=15) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test3.js	(in=15) (out=15) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/.npmignore	(in=178) (out=118) (deflated 34%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/.travis.yml	(in=38) (out=34) (deflated 11%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/offset.js	(in=321) (out=159) (deflated 50%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/time.js	(in=627) (out=329) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/index.js	(in=34) (out=34) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/lib/index.js	(in=9758) (out=2602) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/LICENSE	(in=1660) (out=844) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/Makefile	(in=206) (out=111) (deflated 46%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/package.json	(in=1447) (out=589) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/README.md	(in=1898) (out=862) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/test/index.js	(in=12845) (out=1906) (deflated 85%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/package.json	(in=1632) (out=688) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/README.md	(in=30775) (out=10828) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/browser.js	(in=57522) (out=5348) (deflated 91%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/client.js	(in=16544) (out=2051) (deflated 88%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/crypto.js	(in=2149) (out=529) (deflated 75%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/index.js	(in=14411) (out=1334) (deflated 91%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/readme.js	(in=3263) (out=980) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/server.js	(in=49589) (out=3864) (deflated 92%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/uri.js	(in=29013) (out=2921) (deflated 90%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/utils.js	(in=3213) (out=675) (deflated 79%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/.dir-locals.el	(in=178) (out=94) (deflated 47%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/.npmignore	(in=54) (out=48) (deflated 11%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/http_signing.md	(in=11581) (out=4868) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/index.js	(in=555) (out=244) (deflated 56%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/parser.js	(in=8864) (out=2447) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/signer.js	(in=5203) (out=1707) (deflated 67%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/util.js	(in=6959) (out=1973) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/verify.js	(in=2017) (out=666) (deflated 67%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/LICENSE	(in=1067) (out=617) (deflated 42%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/.npmignore	(in=19) (out=19) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/errors.js	(in=239) (out=170) (deflated 29%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/index.js	(in=469) (out=244) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/reader.js	(in=5760) (out=1658) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/types.js	(in=638) (out=356) (deflated 44%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/writer.js	(in=7603) (out=1965) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/index.js	(in=320) (out=229) (deflated 28%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/LICENSE	(in=1076) (out=632) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/package.json	(in=1601) (out=701) (deflated 56%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/README.md	(in=1201) (out=627) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/reader.test.js	(in=4712) (out=1174) (deflated 75%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/writer.test.js	(in=7737) (out=1292) (deflated 83%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/assert.js	(in=6317) (out=1392) (deflated 78%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/package.json	(in=1225) (out=480) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/README.md	(in=3866) (out=1781) (deflated 54%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/.npmignore	(in=5) (out=5) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/CHANGELOG	(in=2057) (out=988) (deflated 52%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctf.js	(in=5834) (out=1709) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctio.js	(in=43551) (out=11346) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctype.js	(in=25257) (out=6797) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/LICENSE	(in=1293) (out=723) (deflated 44%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/man3ctype/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/man3ctype/ctio.3ctype	(in=8265) (out=2464) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/package.json	(in=1080) (out=453) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/README	(in=2890) (out=1345) (deflated 53%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/README.old	(in=10142) (out=3548) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/jsl.conf	(in=6240) (out=2443) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/jsstyle	(in=21591) (out=7669) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/package.json	(in=1809) (out=671) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/README.md	(in=1594) (out=747) (deflated 53%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.jshintrc	(in=1147) (out=360) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.npmignore	(in=6) (out=6) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.travis.yml	(in=150) (out=110) (deflated 27%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/isstream.js	(in=588) (out=206) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/LICENSE.md	(in=1125) (out=636) (deflated 43%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/package.json	(in=1604) (out=658) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/README.md	(in=2424) (out=835) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/test.js	(in=6975) (out=1023) (deflated 85%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/.npmignore	(in=7) (out=7) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/CHANGELOG.md	(in=734) (out=404) (deflated 45%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/LICENSE	(in=765) (out=472) (deflated 38%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/Makefile	(in=675) (out=297) (deflated 56%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/package.json	(in=1718) (out=679) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/README.md	(in=1261) (out=618) (deflated 51%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/stringify.js	(in=907) (out=364) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/mocha.opts	(in=27) (out=27) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/stringify_test.js	(in=7550) (out=1385) (deflated 82%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/HISTORY.md	(in=2843) (out=811) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/index.js	(in=3643) (out=1237) (deflated 66%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/LICENSE	(in=1167) (out=690) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/db.json 	(in=139657) (out=17515) (deflated 87%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/HISTORY.md	(in=6129) (out=1612) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/index.js	(in=136) (out=117) (deflated 14%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/LICENSE	(in=1099) (out=652) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/package.json	(in=2429) (out=924) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/README.md	(in=2994) (out=1282) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/package.json	(in=2148) (out=805) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/README.md	(in=2920) (out=1084) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/.npmignore	(in=23) (out=23) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/bench.gnu	(in=5822) (out=1800) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/bench.sh	(in=1097) (out=603) (deflated 45%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/benchmark-native.c	(in=613) (out=338) (deflated 45%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/benchmark.js	(in=2237) (out=577) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/README.md	(in=2031) (out=957) (deflated 53%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bin/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bin/uuid	(in=595) (out=300) (deflated 50%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bower.json	(in=435) (out=262) (deflated 40%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/component.json	(in=474) (out=285) (deflated 40%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/LICENSE.md	(in=1088) (out=642) (deflated 41%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/package.json	(in=1555) (out=627) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/README.md	(in=7209) (out=3044) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/compare_v1.js	(in=1483) (out=640) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/test.html	(in=340) (out=176) (deflated 48%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/test.js	(in=6168) (out=2325) (deflated 62%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/uuid.js	(in=7243) (out=2697) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/index.js	(in=3548) (out=1373) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/LICENSE	(in=9140) (out=3306) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/package.json	(in=1564) (out=628) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/README.md	(in=107) (out=93) (deflated 13%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/test.js	(in=3554) (out=1406) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.eslintignore	(in=5) (out=5) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.npmignore	(in=196) (out=129) (deflated 34%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.travis.yml	(in=55) (out=41) (deflated 25%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/bower.json	(in=449) (out=272) (deflated 39%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/CHANGELOG.md	(in=5844) (out=1526) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/CONTRIBUTING.md	(in=105) (out=99) (deflated 6%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/index.js	(in=200) (out=128) (deflated 36%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/parse.js	(in=5288) (out=1568) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/stringify.js	(in=3072) (out=813) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/utils.js	(in=4319) (out=1304) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/LICENSE	(in=1654) (out=840) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/package.json	(in=1472) (out=661) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/README.md	(in=8127) (out=2834) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/parse.js	(in=16977) (out=3028) (deflated 82%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/stringify.js	(in=8549) (out=1725) (deflated 80%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/utils.js	(in=507) (out=277) (deflated 45%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/.npmignore	(in=96) (out=77) (deflated 20%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/.travis.yml	(in=43) (out=34) (deflated 21%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/example.js	(in=814) (out=376) (deflated 54%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/LICENSE.txt	(in=170) (out=136) (deflated 20%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/package.json	(in=2368) (out=961) (deflated 59%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/README.md	(in=1062) (out=517) (deflated 51%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/stringstream.js	(in=2792) (out=787) (deflated 72%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.editorconfig	(in=243) (out=165) (deflated 32%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.jshintrc	(in=1609) (out=436) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.npmignore	(in=46) (out=46) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.travis.yml	(in=118) (out=91) (deflated 23%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/generate-pubsuffix.js	(in=11243) (out=3056) (deflated 73%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/cookie.js	(in=36615) (out=11146) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/memstore.js	(in=5514) (out=2060) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/pathMatch.js	(in=2435) (out=1129) (deflated 54%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/permuteDomain.js	(in=2266) (out=1156) (deflated 49%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/pubsuffix.js 	(in=142086) (out=32993) (deflated 77%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/store.js	(in=2841) (out=1211) (deflated 57%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/LICENSE	(in=4109) (out=1846) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/package.json	(in=1611) (out=651) (deflated 60%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/public-suffix.txt 	(in=161546) (out=53515) (deflated 67%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/README.md	(in=24676) (out=8779) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/api_test.js	(in=12727) (out=2645) (deflated 79%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_jar_test.js	(in=17101) (out=3336) (deflated 80%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_sorting_test.js	(in=5848) (out=1828) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_to_json_test.js	(in=6045) (out=1850) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_to_string_test.js	(in=5214) (out=1562) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/date_test.js	(in=3079) (out=1383) (deflated 55%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/domain_and_path_test.js	(in=6699) (out=1969) (deflated 71%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/bsd-examples.json	(in=5262) (out=575) (deflated 89%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/examples.json	(in=1498) (out=361) (deflated 76%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/parser.json	(in=49561) (out=3434) (deflated 93%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_test.js	(in=3760) (out=1568) (deflated 58%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/jar_serialization_test.js	(in=11537) (out=3522) (deflated 69%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/lifetime_test.js	(in=3624) (out=1356) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/parsing_test.js	(in=11108) (out=2372) (deflated 79%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/regression_test.js	(in=4995) (out=1771) (deflated 65%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/.jshintrc	(in=54) (out=38) (deflated 30%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/index.js	(in=6792) (out=2033) (deflated 70%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/LICENSE	(in=9140) (out=3306) (deflated 64%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/package.json	(in=1608) (out=622) (deflated 61%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/README.md	(in=113) (out=94) (deflated 17%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/package.json	(in=2918) (out=1092) (deflated 63%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/README.md	(in=39382) (out=12824) (deflated 67%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/release.sh	(in=1262) (out=704) (deflated 44%)
  adding: Payload/HelloWorld.app/www/jxcore/node_modules/request/request.js	(in=39164) (out=10233) (deflated 74%)
  adding: Payload/HelloWorld.app/www/jxcore/TestingEnvironment/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/jxcore/TestingEnvironment/log.js	(in=400) (out=234) (deflated 42%)
  adding: Payload/HelloWorld.app/www/plugins/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/plugins/io.jxcore.node/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/plugins/io.jxcore.node/www/	(in=0) (out=0) (stored 0%)
  adding: Payload/HelloWorld.app/www/plugins/io.jxcore.node/www/jxcore.js	(in=4289) (out=1509) (deflated 65%)
total bytes=10500018, compressed=4634158 -> 56% savings
]
Results at '/Users/thali/Github/testBuild/platforms/ios/build/device/HelloWorld.ipa' 
** BUILD SUCCEEDED **


```

```

a platforms/ios/build/device/HelloWorld.app
a platforms/ios/build/device/HelloWorld.app/_CodeSignature
a platforms/ios/build/device/HelloWorld.app/config.xml
a platforms/ios/build/device/HelloWorld.app/Default-568h@2x~iphone.png
a platforms/ios/build/device/HelloWorld.app/Default-667h.png
a platforms/ios/build/device/HelloWorld.app/Default-736h.png
a platforms/ios/build/device/HelloWorld.app/Default-Landscape-736h.png
a platforms/ios/build/device/HelloWorld.app/Default-Landscape@2x~ipad.png
a platforms/ios/build/device/HelloWorld.app/Default-Landscape~ipad.png
a platforms/ios/build/device/HelloWorld.app/Default-Portrait@2x~ipad.png
a platforms/ios/build/device/HelloWorld.app/Default-Portrait~ipad.png
a platforms/ios/build/device/HelloWorld.app/Default@2x~iphone.png
a platforms/ios/build/device/HelloWorld.app/Default~iphone.png
a platforms/ios/build/device/HelloWorld.app/embedded.mobileprovision
a platforms/ios/build/device/HelloWorld.app/HelloWorld
a platforms/ios/build/device/HelloWorld.app/icon-40.png
a platforms/ios/build/device/HelloWorld.app/icon-40@2x.png
a platforms/ios/build/device/HelloWorld.app/icon-50.png
a platforms/ios/build/device/HelloWorld.app/icon-50@2x.png
a platforms/ios/build/device/HelloWorld.app/icon-60.png
a platforms/ios/build/device/HelloWorld.app/icon-60@2x.png
a platforms/ios/build/device/HelloWorld.app/icon-60@3x.png
a platforms/ios/build/device/HelloWorld.app/icon-72.png
a platforms/ios/build/device/HelloWorld.app/icon-72@2x.png
a platforms/ios/build/device/HelloWorld.app/icon-76.png
a platforms/ios/build/device/HelloWorld.app/icon-76@2x.png
a platforms/ios/build/device/HelloWorld.app/icon-small.png
a platforms/ios/build/device/HelloWorld.app/icon-small@2x.png
a platforms/ios/build/device/HelloWorld.app/icon.png
a platforms/ios/build/device/HelloWorld.app/icon@2x.png
a platforms/ios/build/device/HelloWorld.app/Info.plist
a platforms/ios/build/device/HelloWorld.app/jxcore_cordova.js
a platforms/ios/build/device/HelloWorld.app/MainViewController.nib
a platforms/ios/build/device/HelloWorld.app/PkgInfo
a platforms/ios/build/device/HelloWorld.app/www
a platforms/ios/build/device/HelloWorld.app/www/cordova-js-src
a platforms/ios/build/device/HelloWorld.app/www/cordova.js
a platforms/ios/build/device/HelloWorld.app/www/cordova_plugins.js
a platforms/ios/build/device/HelloWorld.app/www/index.html
a platforms/ios/build/device/HelloWorld.app/www/jxcore
a platforms/ios/build/device/HelloWorld.app/www/plugins
a platforms/ios/build/device/HelloWorld.app/www/plugins/io.jxcore.node
a platforms/ios/build/device/HelloWorld.app/www/plugins/io.jxcore.node/www
a platforms/ios/build/device/HelloWorld.app/www/plugins/io.jxcore.node/www/jxcore.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/app.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/TestingEnvironment
a platforms/ios/build/device/HelloWorld.app/www/jxcore/TestingEnvironment/log.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/json-nice
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/.eslintrc
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/CHANGELOG.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/CONTRIBUTING.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/disabled.appveyor.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/examples
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/release.sh
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/request.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/.jshintrc
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.editorconfig
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.jshintrc
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/generate-pubsuffix.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/public-suffix.txt
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/api_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_jar_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_sorting_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_to_json_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_to_string_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/date_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/domain_and_path_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/jar_serialization_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/lifetime_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/parsing_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/regression_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/parser.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/bsd-examples.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/examples.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/cookie.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/memstore.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/pathMatch.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/permuteDomain.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/pubsuffix.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/store.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/example.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/LICENSE.txt
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/stringstream.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.eslintignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/bower.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/CHANGELOG.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/CONTRIBUTING.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/parse.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/stringify.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/utils.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/parse.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/stringify.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/utils.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bin
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bower.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/component.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/LICENSE.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/uuid.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/compare_v1.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/test.html
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bin/uuid
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/bench.gnu
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/bench.sh
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/benchmark-native.c
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/benchmark.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/HISTORY.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/db.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/HISTORY.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/CHANGELOG.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/Makefile
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/stringify.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/mocha.opts
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/stringify_test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.jshintrc
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/isstream.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/LICENSE.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/.dir-locals.el
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/http_signing.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/CHANGELOG
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctf.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctio.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctype.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/README
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/README.old
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/jsl.conf
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/jsstyle
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/man3ctype
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/man3ctype/ctio.3ctype
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/assert.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/reader.test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/writer.test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/errors.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/reader.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/types.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/writer.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/parser.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/signer.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/util.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/verify.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/bower.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/component.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/example
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/browser.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/client.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/crypto.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/readme.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/server.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/uri.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/utils.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/Makefile
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/test/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/offset.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/time.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/CONTRIBUTING.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/images
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/Makefile
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/escaper.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/ignore.txt
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test1.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test2.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test3.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/escape.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/images/hoek.png
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/Makefile
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/test/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/CONTRIBUTING.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/images
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/test/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/images/boom.png
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/browser.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/client.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/crypto.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/server.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/utils.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images/hawk.png
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images/logo.png
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/example/usage.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/bin
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/example.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/formats.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/require.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/fixtures
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/misc.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/additionalItems.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/additionalProperties.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/allOf.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/anyOf.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/bignum.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/default.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/definitions.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/dependencies.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/enum.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/format.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/items.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maximum.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxItems.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxLength.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxProperties.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minimum.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minItems.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minLength.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minProperties.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/multipleOf.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/not.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/nullAndFormat.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/nullAndObject.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/oneOf.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/pattern.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/patternProperties.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/properties.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/ref.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/refRemote.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/required.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/type.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/uniqueItems.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/fixtures/cosmic.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/.jshintrc
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/immutable.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/LICENCE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/Makefile
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/mutable.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/jsonpointer.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/is-property.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/example.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/History.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/Readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/license
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/license
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/license
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/license
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/license
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/license
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/license
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/license
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/changelog.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/any.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/assert.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/async.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/bind.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/bluebird.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/call_get.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/cancel.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/captured_trace.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/catch_filter.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/context.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/debuggability.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/direct_resolve.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/each.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/errors.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/es5.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/filter.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/finally.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/generators.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/join.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/map.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/method.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/nodeify.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/progress.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise_array.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise_resolver.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promisify.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/props.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/queue.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/race.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/reduce.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/schedule.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/settle.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/some.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/synchronous_inspection.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/thenables.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/timers.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/using.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/util.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/bluebird.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/bluebird.min.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/error.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cache.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cacheEntry.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/content.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cookie.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/creator.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/entry.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/har.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/log.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/page.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/pageTimings.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/postData.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/record.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/request.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/response.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/timings.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/bin/har-validator
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/License
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/Readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/CHANGELOG.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/lib/async.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib/browser.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib/form_data.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.eslintrc
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.jscs.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/CHANGELOG.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/component.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/License
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/Readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/License
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/Makefile
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/Readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/lib/delayed_stream.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/lib/combined_stream.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.jshintrc
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/bl.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/LICENSE.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/basic-test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/sauce.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.zuul.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/duplex.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/passthrough.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/readable.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/transform.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/writable.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/browser.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/History.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/node.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/.npmignore
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/.travis.yml
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/readme.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/build
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/component.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/build/build.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/inherits.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/inherits_browser.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/test.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/float.patch
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/lib
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/util.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/lib/util.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_duplex.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_passthrough.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_readable.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_transform.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_writable.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/stream.markdown
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/wg-meetings
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/wg-meetings/2015-01-30.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/LICENSE
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin/har-validator
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin/uuid
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/auth.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/cookies.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/getProxyFromURI.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/har.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/helpers.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/multipart.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/oauth.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/querystring.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/redirect.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/tunnel.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/examples/README.md
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/json-nice/index.js
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/json-nice/package.json
a platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/json-nice/README.md
a platforms/ios/build/device/HelloWorld.app/www/cordova-js-src/exec.js
a platforms/ios/build/device/HelloWorld.app/www/cordova-js-src/platform.js
a platforms/ios/build/device/HelloWorld.app/_CodeSignature/CodeResources
x platforms/ios/build/device/HelloWorld.app/
x platforms/ios/build/device/HelloWorld.app/_CodeSignature/
x platforms/ios/build/device/HelloWorld.app/config.xml
x platforms/ios/build/device/HelloWorld.app/Default-568h@2x~iphone.png
x platforms/ios/build/device/HelloWorld.app/Default-667h.png
x platforms/ios/build/device/HelloWorld.app/Default-736h.png
x platforms/ios/build/device/HelloWorld.app/Default-Landscape-736h.png
x platforms/ios/build/device/HelloWorld.app/Default-Landscape@2x~ipad.png
x platforms/ios/build/device/HelloWorld.app/Default-Landscape~ipad.png
x platforms/ios/build/device/HelloWorld.app/Default-Portrait@2x~ipad.png
x platforms/ios/build/device/HelloWorld.app/Default-Portrait~ipad.png
x platforms/ios/build/device/HelloWorld.app/Default@2x~iphone.png
x platforms/ios/build/device/HelloWorld.app/Default~iphone.png
x platforms/ios/build/device/HelloWorld.app/embedded.mobileprovision
x platforms/ios/build/device/HelloWorld.app/HelloWorld
x platforms/ios/build/device/HelloWorld.app/icon-40.png
x platforms/ios/build/device/HelloWorld.app/icon-40@2x.png
x platforms/ios/build/device/HelloWorld.app/icon-50.png
x platforms/ios/build/device/HelloWorld.app/icon-50@2x.png
x platforms/ios/build/device/HelloWorld.app/icon-60.png
x platforms/ios/build/device/HelloWorld.app/icon-60@2x.png
x platforms/ios/build/device/HelloWorld.app/icon-60@3x.png
x platforms/ios/build/device/HelloWorld.app/icon-72.png
x platforms/ios/build/device/HelloWorld.app/icon-72@2x.png
x platforms/ios/build/device/HelloWorld.app/icon-76.png
x platforms/ios/build/device/HelloWorld.app/icon-76@2x.png
x platforms/ios/build/device/HelloWorld.app/icon-small.png
x platforms/ios/build/device/HelloWorld.app/icon-small@2x.png
x platforms/ios/build/device/HelloWorld.app/icon.png
x platforms/ios/build/device/HelloWorld.app/icon@2x.png
x platforms/ios/build/device/HelloWorld.app/Info.plist
x platforms/ios/build/device/HelloWorld.app/jxcore_cordova.js
x platforms/ios/build/device/HelloWorld.app/MainViewController.nib
x platforms/ios/build/device/HelloWorld.app/PkgInfo
x platforms/ios/build/device/HelloWorld.app/www/
x platforms/ios/build/device/HelloWorld.app/www/cordova-js-src/
x platforms/ios/build/device/HelloWorld.app/www/cordova.js
x platforms/ios/build/device/HelloWorld.app/www/cordova_plugins.js
x platforms/ios/build/device/HelloWorld.app/www/index.html
x platforms/ios/build/device/HelloWorld.app/www/jxcore/
x platforms/ios/build/device/HelloWorld.app/www/plugins/
x platforms/ios/build/device/HelloWorld.app/www/plugins/io.jxcore.node/
x platforms/ios/build/device/HelloWorld.app/www/plugins/io.jxcore.node/www/
x platforms/ios/build/device/HelloWorld.app/www/plugins/io.jxcore.node/www/jxcore.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/app.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/TestingEnvironment/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/TestingEnvironment/log.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/json-nice/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/.eslintrc
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/CHANGELOG.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/CONTRIBUTING.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/disabled.appveyor.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/examples/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/release.sh
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/request.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/.jshintrc
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tunnel-agent/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.editorconfig
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.jshintrc
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/generate-pubsuffix.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/public-suffix.txt
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/api_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_jar_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_sorting_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_to_json_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/cookie_to_string_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/date_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/domain_and_path_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/jar_serialization_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/lifetime_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/parsing_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/regression_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/parser.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/bsd-examples.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/test/ietf_data/dates/examples.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/cookie.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/memstore.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/pathMatch.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/permuteDomain.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/pubsuffix.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/tough-cookie/lib/store.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/example.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/LICENSE.txt
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/stringstream/stringstream.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.eslintignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/bower.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/CHANGELOG.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/CONTRIBUTING.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/parse.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/stringify.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/test/utils.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/parse.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/stringify.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/qs/lib/utils.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/oauth-sign/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bin/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bower.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/component.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/LICENSE.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/uuid.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/compare_v1.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/test.html
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/test/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/bin/uuid
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/bench.gnu
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/bench.sh
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/benchmark-native.c
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/benchmark.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/node-uuid/benchmark/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/HISTORY.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/db.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/HISTORY.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/mime-types/node_modules/mime-db/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/CHANGELOG.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/Makefile
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/stringify.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/mocha.opts
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/json-stringify-safe/test/stringify_test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.jshintrc
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/isstream.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/LICENSE.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/isstream/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/.dir-locals.el
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/http_signing.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/CHANGELOG
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctf.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctio.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/ctype.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/README
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/README.old
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/jsl.conf
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/tools/jsstyle
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/man3ctype/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/ctype/man/man3ctype/ctio.3ctype
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/assert.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/assert-plus/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/reader.test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/tst/ber/writer.test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/errors.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/reader.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/types.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/node_modules/asn1/lib/ber/writer.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/parser.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/signer.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/util.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/http-signature/lib/verify.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/bower.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/component.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/example/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/browser.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/client.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/crypto.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/readme.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/server.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/uri.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/test/utils.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/Makefile
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/test/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/offset.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/sntp/examples/time.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/CONTRIBUTING.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/images/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/Makefile
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/escaper.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/ignore.txt
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test1.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test2.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/test/modules/test3.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/escape.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/hoek/images/hoek.png
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/Makefile
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/test/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/cryptiles/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/CONTRIBUTING.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/images/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/test/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/node_modules/boom/images/boom.png
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/browser.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/client.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/crypto.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/server.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/lib/utils.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images/hawk.png
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/images/logo.png
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/hawk/example/usage.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/bin/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/example.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/formats.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/require.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/fixtures/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/misc.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/additionalItems.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/additionalProperties.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/allOf.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/anyOf.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/bignum.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/default.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/definitions.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/dependencies.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/enum.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/format.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/items.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maximum.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxItems.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxLength.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/maxProperties.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minimum.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minItems.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minLength.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/minProperties.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/multipleOf.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/not.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/nullAndFormat.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/nullAndObject.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/oneOf.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/pattern.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/patternProperties.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/properties.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/ref.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/refRemote.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/required.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/type.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/json-schema-draft4/uniqueItems.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/test/fixtures/cosmic.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/.jshintrc
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/immutable.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/LICENCE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/Makefile
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/mutable.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/xtend/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/jsonpointer.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/jsonpointer/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/is-property.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-object-property/node_modules/is-property/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/example.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/is-my-json-valid/node_modules/generate-function/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/History.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/Readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/commander/node_modules/graceful-readlink/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/license
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/license
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/supports-color/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/license
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/license
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/strip-ansi/node_modules/ansi-regex/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/license
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/license
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/has-ansi/node_modules/ansi-regex/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/license
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/escape-string-regexp/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/license
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/chalk/node_modules/ansi-styles/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/changelog.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/any.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/assert.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/async.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/bind.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/bluebird.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/call_get.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/cancel.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/captured_trace.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/catch_filter.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/context.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/debuggability.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/direct_resolve.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/each.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/errors.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/es5.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/filter.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/finally.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/generators.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/join.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/map.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/method.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/nodeify.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/progress.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise_array.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promise_resolver.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/promisify.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/props.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/queue.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/race.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/reduce.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/schedule.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/settle.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/some.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/synchronous_inspection.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/thenables.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/timers.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/using.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/main/util.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/bluebird.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/node_modules/bluebird/js/browser/bluebird.min.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/error.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cache.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cacheEntry.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/content.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/cookie.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/creator.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/entry.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/har.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/log.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/page.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/pageTimings.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/postData.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/record.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/request.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/response.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/lib/schemas/timings.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/har-validator/bin/har-validator
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/License
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/Readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/CHANGELOG.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/node_modules/async/lib/async.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib/browser.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/form-data/lib/form_data.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/forever-agent/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.eslintrc
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.jscs.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/CHANGELOG.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/component.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/extend/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/License
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/Readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/License
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/Makefile
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/Readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/node_modules/delayed-stream/lib/delayed_stream.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/combined-stream/lib/combined_stream.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/caseless/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.jshintrc
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/bl.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/LICENSE.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/basic-test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/sauce.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/test/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/.zuul.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/duplex.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/passthrough.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/readable.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/transform.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/writable.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/browser.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/History.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/node.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/util-deprecate/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/.npmignore
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/string_decoder/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/.travis.yml
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/readme.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/process-nextick-args/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/build/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/component.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/isarray/build/build.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/inherits.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/inherits_browser.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/inherits/test.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/float.patch
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/lib/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/util.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/node_modules/core-util-is/lib/util.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_duplex.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_passthrough.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_readable.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_transform.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/lib/_stream_writable.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/stream.markdown
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/wg-meetings/
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/bl/node_modules/readable-stream/doc/wg-meetings/2015-01-30.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/LICENSE
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/aws-sign2/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin/har-validator
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/node_modules/.bin/uuid
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/auth.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/cookies.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/getProxyFromURI.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/har.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/helpers.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/multipart.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/oauth.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/querystring.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/redirect.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/lib/tunnel.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/request/examples/README.md
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/json-nice/index.js
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/json-nice/package.json
x platforms/ios/build/device/HelloWorld.app/www/jxcore/node_modules/json-nice/README.md
x platforms/ios/build/device/HelloWorld.app/www/cordova-js-src/exec.js
x platforms/ios/build/device/HelloWorld.app/www/cordova-js-src/platform.js
x platforms/ios/build/device/HelloWorld.app/_CodeSignature/CodeResources

```

```


```
