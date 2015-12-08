#### Test 50650278cc6513d_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1016): sending alarm Alarm{43e525e8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3524): 
D/AndroidRuntime( 3524): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3524): CheckJNI is OFF
D/dalvikvm( 3524): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3524): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3524): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3524): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3524): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3524): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3524): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3524): failed to load memtrack module: -2
D/AndroidRuntime( 3524): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3524
W/WindowManager( 1016): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3540 uid=10444 gids={50444, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3524): Shutting down VM
D/dalvikvm( 3524): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3540): Binding Chromium to main looper Looper (main, tid 1) {41ffbad0}
I/LibraryLoader( 3540): Expected native library version number "",actual native library version number ""
I/chromium( 3540): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3540): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1016): Message: 20
D/BluetoothManagerService( 1016): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d84948:true
D/BluetoothAdapter( 3540): 1107362016: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3540): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3540): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3540): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3540): Local Branch: 
I/Adreno-EGL( 3540): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3540): Local Patches: NONE
I/Adreno-EGL( 3540): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3540): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3540): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3540): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3540): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3540): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3540): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3540): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3540): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3540): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3540): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3540): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3540): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3540): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3540): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3540): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3540): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3540): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 3540): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3540): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3540): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3540): Enabling debug mode 0
,W/AwContents( 3540): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3540): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1016): Displayed com.test.thalitest/.MainActivity,cp,ca,396
I/ActivityManager( 1016): Displayed com.test.thalitest/.MainActivity: +372ms (total +396ms)
,D/JsMessageQueue( 3540): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3540): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41ffff80
,D/dalvikvm( 3540): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41ffff80
,D/jxcore_app_log( 3540): JniHelper::setJavaVM(0x41649fa8), pthread_self() = 1614776504
,D/JX-Cordova( 3540): jxcore cordova android initializing
,I/dalvikvm( 3540): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3540): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3540): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3540): GC_CONCURRENT freed 2812K, 17% free 14377K/17224K, paused 3ms+2ms, total 64ms
,D/dalvikvm( 3540): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 130K, 17% free 14367K/17224K, paused 26ms, total 27ms
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 303K, 17% free 14432K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3540): Grow heap (frag case) to 16.263MB for 143930-byte allocation
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 266K, 17% free 14468K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3540): Grow heap (frag case) to 16.368MB for 215890-byte allocation
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 368K, 18% free 14541K/17580K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3540): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 568K, 19% free 14662K/17900K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3540): Grow heap (frag case) to 16.814MB for 485740-byte allocation
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 866K, 20% free 14838K/18376K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3540): Grow heap (frag case) to 17.217MB for 728606-byte allocation
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 1284K, 21% free 15094K/19088K, paused 27ms, total 28ms
,D/dalvikvm( 3540): GC_CONCURRENT freed 1678K, 19% free 15464K/19088K, paused 2ms+3ms, total 44ms
,D/dalvikvm( 3540): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 3540): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 367K, 20% free 15420K/19088K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3540): Grow heap (frag case) to 18.654MB for 1639352-byte allocation
,D/dalvikvm( 3540): GC_CONCURRENT freed 1700K, 23% free 15992K/20692K, paused 1ms+4ms, total 40ms
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 1357K, 23% free 16067K/20692K, paused 29ms, total 30ms
,I/dalvikvm-heap( 3540): Grow heap (frag case) to 20.068MB for 2459024-byte allocation
,D/dalvikvm( 3540): GC_CONCURRENT freed 235K, 21% free 18364K/23096K, paused 4ms+7ms, total 40ms
,D/dalvikvm( 3540): GC_CONCURRENT freed 4372K, 27% free 17043K/23096K, paused 1ms+7ms, total 47ms
,D/dalvikvm( 3540): WAIT_FOR_CONCURRENT_GC blocked 39ms
,I/dalvikvm-heap( 3540): Grow heap (frag case) to 22.194MB for 3688532-byte allocation
,D/dalvikvm( 3540): GC_CONCURRENT freed 2798K, 33% free 18130K/26700K, paused 1ms+4ms, total 55ms
,D/dalvikvm( 3540): GC_FOR_ALLOC freed 736K, 33% free 18009K/26700K, paused 28ms, total 29ms
,W/jxcore-log( 3540): Initializing JXcore engine
,W/jxcore-log( 3540): JXcore engine is ready
,D/dalvikvm( 3540): GC_CONCURRENT freed 390K, 23% free 20596K/26700K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 3540): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 3540): Starting JXcore engine
,W/jxcore-log( 3540): Platform android
W/jxcore-log( 3540): 
,W/jxcore-log( 3540): Process ARCH arm
W/jxcore-log( 3540): 
,I/jxcore-log( 3540): JXcore Cordova bridge is ready!
I/jxcore-log( 3540): 
,W/jxcore-log( 3540): JXcore engine is started
,I/chromium( 3540): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3540): Error!: missing ) after argument list
E/jxcore  ( 3540): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3540): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1016): Killing 3239:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1529): [info] > Updatetime from metadata: 10
,D/Checkin ( 1529): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1529): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1529): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1529): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1529): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1529): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 3540): showStatusIcon on inactive InputConnection
,I/SFPerfTracer(  275):      triggers: (rate: 2:30) (compose: 0:4) (post: 0:1) (render: 0:5) (0:117 frames) (1:548)
,D/SFPerfTracer(  275):        layers: (0:14) (FocusedStackFrame: 1:11)* (StatusBar: 0:200)* (NavigationBar: 0:42)* (com.android.systemui.ImageWallpaper: 0:7)* (com.android.launcher/com.android.launcher2.Launcher: 0:9)* (Starting com.motorola.ccc.ota: 0:33)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:8)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:4)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 1:2)* 
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{43e48610 type 3 android}

```
