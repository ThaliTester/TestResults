#### Test (Fail) 50242285 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/TestDummy
   d7f7159..e17d765  test_ogz   -> origin/test_ogz

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Merge made by the 'recursive' strategy.
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

Already on 'master'
Already on 'master'
Note: checking out 'e17d765'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at e17d765... update jxcore-cordova

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
:compileReleaseJava FAILED

BUILD FAILED

Total time: 30.202 secs
ERROR building one of the platforms: Error: /Users/thali/Github/testBuild/platforms/android/cordova/build: Command failed with exit code 8
You may not have the required environment or OS to build this project
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

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
warning: android/os/Looper.class(android/os:Looper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:62: cannot find symbol
symbol  : class CoreThread
location: class io.jxcore.node.jxcore
  public static CoreThread coreThread = null;
                ^
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
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:100: cannot find symbol
symbol  : class CoreRunnable
location: class io.jxcore.node.jxcore
        activity.runOnUiThread(new CoreRunnable(callback_id, result) {
                                   ^
warning: java/util/AbstractList.class(java/util:AbstractList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractCollection.class(java/util:AbstractCollection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:171: cannot find symbol
symbol  : class CoreRunnable
location: class io.jxcore.node.jxcore
      coreThread.handler.post(new CoreRunnable(id, args) {
                                  ^
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:191: cannot find symbol
symbol  : class CoreRunnable
location: class io.jxcore.node.jxcore
      coreThread.handler.post(new CoreRunnable(id, json) {
                                  ^
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:220: cannot find symbol
symbol  : class CoreRunnable
location: class io.jxcore.node.jxcore
        coreThread.handler.post(new CoreRunnable(callbackContext
                                    ^
warning: java/io/File.class(java/io:File.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Runnable.class(java/lang:Runnable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/pm/ApplicationInfo.class(android/content/pm:ApplicationInfo.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractMap.class(java/util:AbstractMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:369: cannot find symbol
symbol  : class CoreThread
location: class io.jxcore.node.jxcore
    coreThread = new CoreThread(runnable);
                     ^
6 errors
100 warnings

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':compileReleaseJava'.
> Compilation failed; see the compiler error output for details.

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

node.js:927
            throw ee;
                  ^
Error code 1 for command: /Users/thali/Github/testBuild/platforms/android/gradlew with args: cdvBuildRelease,-b,/Users/thali/Github/testBuild/platforms/android/build.gradle,-Dorg.gradle.daemon=true
Error: /Users/thali/Github/testBuild/platforms/android/cordova/build: Command failed with exit code 8
    at ChildProcess.whenDone (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/cordova/superspawn.js:139:23)
    at ChildProcess.emit (events.js:85:17)
    at maybeClose (child_process.js:773:16)
    at Process.ChildProcess._handle.onexit (child_process.js:839:5)

```

Error: Command failed: warning: java/lang/Object.class(java/lang:Object.class): major version 51 is newer than 50, the highest major version supported by this compiler.
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
warning: android/os/Looper.class(android/os:Looper.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:62: cannot find symbol
symbol  : class CoreThread
location: class io.jxcore.node.jxcore
  public static CoreThread coreThread = null;
                ^
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
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:100: cannot find symbol
symbol  : class CoreRunnable
location: class io.jxcore.node.jxcore
        activity.runOnUiThread(new CoreRunnable(callback_id, result) {
                                   ^
warning: java/util/AbstractList.class(java/util:AbstractList.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractCollection.class(java/util:AbstractCollection.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:171: cannot find symbol
symbol  : class CoreRunnable
location: class io.jxcore.node.jxcore
      coreThread.handler.post(new CoreRunnable(id, args) {
                                  ^
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:191: cannot find symbol
symbol  : class CoreRunnable
location: class io.jxcore.node.jxcore
      coreThread.handler.post(new CoreRunnable(id, json) {
                                  ^
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:220: cannot find symbol
symbol  : class CoreRunnable
location: class io.jxcore.node.jxcore
        coreThread.handler.post(new CoreRunnable(callbackContext
                                    ^
warning: java/io/File.class(java/io:File.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/lang/Runnable.class(java/lang:Runnable.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: android/content/pm/ApplicationInfo.class(android/content/pm:ApplicationInfo.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
warning: java/util/AbstractMap.class(java/util:AbstractMap.class): major version 51 is newer than 50, the highest major version supported by this compiler.
It is recommended that the compiler be upgraded.
/Users/thali/Github/testBuild/platforms/android/src/io/jxcore/node/jxcore.java:369: cannot find symbol
symbol  : class CoreThread
location: class io.jxcore.node.jxcore
    coreThread = new CoreThread(runnable);
                     ^
6 errors
100 warnings

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':compileReleaseJava'.
> Compilation failed; see the compiler error output for details.

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

node.js:927
            throw ee;
                  ^
Error code 1 for command: /Users/thali/Github/testBuild/platforms/android/gradlew with args: cdvBuildRelease,-b,/Users/thali/Github/testBuild/platforms/android/build.gradle,-Dorg.gradle.daemon=true
Error: /Users/thali/Github/testBuild/platforms/android/cordova/build: Command failed with exit code 8
    at ChildProcess.whenDone (/usr/local/lib/node_modules/cordova/node_modules/cordova-lib/src/cordova/superspawn.js:139:23)
    at ChildProcess.emit (events.js:85:17)
    at maybeClose (child_process.js:773:16)
    at Process.ChildProcess._handle.onexit (child_process.js:839:5)
