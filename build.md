#### Test (Success) 49526184 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/TestDummy
   549c368..1f420de  thaliproject-ci-issues-7 -> origin/thaliproject-ci-issues-7

```

```
Your branch is up-to-date with 'origin/master'.
Branch TestResultFake set up to track remote branch TestResultFake from origin.
Branch thaliproject-ci-issues-7 set up to track remote branch thaliproject-ci-issues-7 from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'TestResultFake'
Switched to a new branch 'thaliproject-ci-issues-7'

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

Total time: 41.848 secs
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


```
