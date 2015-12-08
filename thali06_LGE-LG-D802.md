#### Test 5065027865f659b_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4059): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  950): Killing 3354:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  950): Service ServiceRecord{43321838 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43234d98 3354:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  950): Service ServiceRecord{4329be20 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43234d98 3354:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43301fc0 stackId=1, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1950): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1950): GC_CONCURRENT freed 1628K, 26% free 18437K/24832K, paused 4ms+3ms, total 42ms
D/AndroidRuntime( 4105): 
D/AndroidRuntime( 4105): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4105): CheckJNI is OFF
D/dalvikvm( 4105): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4105): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4105): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4105): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4105): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4105): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1950): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1950): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1950): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4105): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4105): failed to load memtrack module: -2
D/AndroidRuntime( 4105): Calling main entry com.android.commands.am.Am
I/ActivityManager(  950): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4105
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43301fc0 stackId=1, 2 tasks}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (128 us)
V/ActivityManager(  950): Moving to PAUSING: ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  950): resumeTopActivityLocked: Pausing null
V/ActivityManager(  950): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  950): startService SlideAside
W/ContextImpl(  950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  950): setFocusedStack: mFocusedStack=ActivityStack{43301fc0 stackId=1, 2 tasks}
D/UsbSettingsControl( 2583): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2583): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4105): Shutting down VM
D/dalvikvm( 4105): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 1ms
D/ActivityManager(  950): allPausedActivitiesComplete: r=ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  950): Moving to PAUSED: ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43301fc0 stackId=1, 2 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Restarting ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  950): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4118 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  950): Moving to RESUMED: ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3536): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/dalvikvm(  950): Jit: resizing JitTable from 8192 to 16384
D/dalvikvm(  269): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
D/HyLog   ( 4118): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4118): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4118): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/SlideAside( 3536): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3536): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+4ms, total 26ms
V/WebViewChromium( 4118): Binding Chromium to the background looper Looper (main, tid 1) {42879f20}
I/chromium( 4118): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4118): Initializing chromium process, renderers=0
W/chromium( 4118): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4118): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4118): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4118): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4118): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4118): Remote Branch: 
I/Adreno-EGL( 4118): Local Patches: 
I/Adreno-EGL( 4118): Reconstruct Branch: 
I/dalvikvm( 4118): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4118): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4118): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4118): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4118): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4118): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4118): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4118): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4118): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4118): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4118): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4118): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4118): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4118): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4118): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4118): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4118): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4118): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4118): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4118): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4118): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4118): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4118): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4118): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4118): Enabling debug mode 0
W/AwContents( 4118): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  950): Displayed com.test.thalitest/.MainActivity: +393ms
W/AwContents( 4118): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  950): IME STATUS OFF
I/ActivityManager( 4118): Timeline: Activity_idle id: android.os.BinderProxy@4287b6f0 time:108919
D/JsMessageQueue( 4118): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4118): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4287f7d0
D/dalvikvm( 4118): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4287f7d0
D/jxcore_app_log( 4118): JniHelper::setJavaVM(0x4173c838), pthread_self() = 1632224856
D/JX-Cordova( 4118): jxcore cordova android initializing
I/dalvikvm( 4118): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4118): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4118): VFY: replacing opcode 0x6e at 0x0045
I/ActivityManager(  950): Timeline: Activity_windows_visible id: ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3} time:109267
D/ActivityManager(  950): no-history finish of ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  950): Finishing activity token=Token{432c7820 ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  950): Moving to FINISHING: ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  950): Moving to STOPPING: ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2583): [AUTORUN] onStop()
V/ActivityManager(  950): Moving to STOPPED: ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4118): GC_CONCURRENT freed 2808K, 13% free 21832K/24832K, paused 2ms+1ms, total 51ms
,D/dalvikvm( 4118): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 112K, 13% free 21833K/24832K, paused 31ms, total 31ms
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 130K, 12% free 21854K/24832K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 23.607MB for 95956-byte allocation
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 182K, 13% free 21888K/24928K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 23.686MB for 143930-byte allocation
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 255K, 13% free 21935K/25072K, paused 34ms, total 34ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 23.800MB for 215890-byte allocation
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 368K, 13% free 22008K/25284K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 23.975MB for 323830-byte allocation
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 565K, 14% free 22129K/25604K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 24.248MB for 485740-byte allocation
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 862K, 15% free 22305K/26080K, paused 24ms, total 24ms
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 1282K, 14% free 22560K/26080K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 25.248MB for 1092904-byte allocation
,D/dalvikvm( 4118): GC_CONCURRENT freed 1860K, 16% free 22958K/27148K, paused 2ms+3ms, total 46ms
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 173K, 16% free 22892K/27148K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 26.093MB for 1639352-byte allocation
,D/dalvikvm( 4118): GC_CONCURRENT freed 1886K, 19% free 23476K/28752K, paused 0ms+3ms, total 44ms
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 1181K, 19% free 23513K/28752K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 27.481MB for 2459024-byte allocation
,D/dalvikvm( 4118): GC_CONCURRENT freed 1859K, 23% free 24211K/31156K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4118): GC_CONCURRENT freed 2334K, 22% free 24460K/31156K, paused 2ms+4ms, total 36ms
,D/dalvikvm( 4118): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 614K, 23% free 24282K/31156K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4118): Grow heap (frag case) to 29.405MB for 3688532-byte allocation
,D/dalvikvm( 4118): GC_CONCURRENT freed 2775K, 27% free 25428K/34760K, paused 2ms+4ms, total 36ms
,D/dalvikvm( 4118): GC_FOR_ALLOC freed 550K, 27% free 25446K/34760K, paused 24ms, total 24ms
,W/jxcore-log( 4118): Initializing JXcore engine
,W/jxcore-log( 4118): JXcore engine is ready
,D/dalvikvm( 4118): GC_CONCURRENT freed 358K, 20% free 28063K/34760K, paused 0ms+1ms, total 24ms
,D/dalvikvm( 4118): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4118): Starting JXcore engine
,W/jxcore-log( 4118): Platform android
W/jxcore-log( 4118): 
,W/jxcore-log( 4118): Process ARCH arm
W/jxcore-log( 4118): 
,I/jxcore-log( 4118): JXcore Cordova bridge is ready!
I/jxcore-log( 4118): 
,W/jxcore-log( 4118): JXcore engine is started
,I/chromium( 4118): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4118): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4118): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore  ( 4118): Error!: missing ) after argument list
E/jxcore  ( 4118): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,V/ActivityManager(  950): Finishing activity token=Token{43d0a870 ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
,V/ActivityManager(  950): Moving to PAUSING: ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3 f}
,I/chromium( 4118): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/dalvikvm(  950): GC_FOR_ALLOC freed 22206K, 50% free 28825K/56692K, paused 136ms, total 136ms
,V/ActivityManager(  950): Moving to PAUSED: ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  950): Moving to STOPPING: ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
,W/PluginManager( 4118): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 147ms. Plugin should use CordovaInterface.getThreadPool().
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{43301fc0 stackId=1, 2 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  950): moveHomeStack:
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c00920 stackId=0, 1 tasks}
V/ActivityManager(  950): Moving to RESUMED: ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  950): resumeTopActivityLocked: Resumed ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/ActivityManager(  950): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c00920 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1}
D/PhoneApp( 1452): getIsInUseVoLTE : false
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1846): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:13:18
D/UpdateThreadPoolManager( 1846): 2 : This is isUpdating : false
D/WeatherQuickCover( 1846): 2 : quick cover state : opened : 0
D/WeatherService( 1846): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1846): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1846): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1846): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1846): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1846): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:13:18
D/WeatherService( 1846): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,I/[LGHome]EVENT( 1490): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/WeatherQuickCover( 1846): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1846): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1846): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1846): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1846): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/InputMethodManagerService(  950): IME STATUS OFF
W/IInputConnectionWrapper( 4118): showStatusIcon on inactive InputConnection
D/UpdateThreadPoolManager( 1846): 2 : This is isUpdating : false
D/WeatherService( 1846): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1846): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1846): 2 : Map key string is -2
D/lim     ( 1846): 2 : time = 19:13
I/WeatherReflect( 1846): Model Name : LG-D802
D/WeatherTheme( 1846): 2 : Different view - status_min_formatted : 11 != 13
D/WeatherTheme( 1846): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1846): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1846): 2 : Fixed theme : optimus
D/WeatherTheme( 1846): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1846): 2 : quick cover state : opened : 0
D/Weather.Utils( 1846): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1846): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1141): GC_FOR_ALLOC freed 5556K, 10% free 71117K/78436K, paused 27ms, total 27ms
,D/dalvikvm( 1490): GC_CONCURRENT freed 5329K, 9% free 61001K/66512K, paused 2ms+7ms, total 29ms
,D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager(  950): Killing 2126:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c00920 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/GAV2    ( 4059): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 1490): GC_FOR_ALLOC freed 4937K, 9% free 61759K/67608K, paused 27ms, total 28ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@42874f18 time:112591
D/UsbSettings( 2583): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2583): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2583): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2583): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  950): Moving to DESTROYING: ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/ActivityManager(  950): Timeline: Activity_windows_visible id: ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1} time:112602
V/ActivityManager(  950): Moving to FINISHING: ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  950): Killing 3795:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
V/ActivityManager(  950): Moving to DESTROYING: ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  950): Moving to DESTROYED: ActivityRecord{430e6b28 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c00920 stackId=0, 1 tasks}
E/libEGL  ( 4118): call to OpenGL ES API with no current context (logged once per thread)
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c00920 stackId=0, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1}
V/ActivityManager(  950): Moving to DESTROYED: ActivityRecord{43c88948 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c00920 stackId=0, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1}
I/ConfigService( 1553): onDestroy
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.456116 Y: -0.391937 Z: 9.757416 
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.467209 Y: -0.404129 Z: 9.740768 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.456116 .y:-0.391937 .z:9.757416
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.452271 Y: -0.393433 Z: 9.735580 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452271 .y:-0.393433 .z:9.735580
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1490): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  950): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3719): [333] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3719): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.471527 Y: -0.402100 Z: 9.755493 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471527 .y:-0.402100 .z:9.755493
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.456329 Y: -0.388367 Z: 9.767914 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456329 .y:-0.388367 .z:9.767914
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/PowerManagerService(  950): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  950): [updateScreenState] screen on = false
D/KnockOnPowerController(  950): [setProximitySensorEnabled] enable = false
I/qcom_sensors_hal(  950): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  950): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  950): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  950): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  950): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8747 usec
D/KnockOnPowerController(  950): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  950): hal_acquire_resources
,I/qcom_sensors_hal(  950): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  950): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  950): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  950): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  950): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  950): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  950): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  950): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.457275 Y: -0.391342 Z: 9.774323 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457275 .y:-0.391342 .z:9.774323
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.449509 Y: -0.369751 Z: 9.776825 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449509 .y:-0.369751 .z:9.776825
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/Sensors (  560): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  950): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  950): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  950): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  950): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  950): proximitySensorChanged  positive = true
I/KnockOnPowerController(  950): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.447540 Y: -0.377945 Z: 9.783478 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447540 .y:-0.377945 .z:9.783478
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.440109 Y: -0.386780 Z: 9.775253 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440109 .y:-0.386780 .z:9.775253
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.448730 Y: -0.388794 Z: 9.764526 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448730 .y:-0.388794 .z:9.764526
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.453232 Y: -0.387619 Z: 9.774414 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453232 .y:-0.387619 .z:9.774414
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  950): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4320a2b8)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  950): **** SHOWN CALLED ****
,D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb82d7450
,D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
I/WindowManager(  950): No lock screen! windowToken=null
,E/SlideAside( 3536): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.446350 Y: -0.378479 Z: 9.786377 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446350 .y:-0.378479 .z:9.786377
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=4
,D/WifiStateMachine(  950): handleScreenStateChanged: true
,D/WifiServiceExtension(  950): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  950): handleMessage: E msg.what=131154
,D/WifiStateMachine(  950): processMsg: InitialState
D/WifiStateMachine(  950): processMsg: DefaultState
,D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131127
D/WifiStateMachine(  950): processMsg: InitialState
,D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131158
,D/WifiStateMachine(  950): processMsg: InitialState
D/WifiStateMachine(  950): processMsg: DefaultState
,D/WifiStateMachine(  950): setSuspendOptimizations: 4 false
D/WifiStateMachine(  950): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  950): handleMessage: X
,D/WifiOffDelayIfNotUsed(  950): stopMonitoring
,E/AudioSystem(  950): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=on, calling pid 950
V/SRS_Proc(  272): ParamSet string: screen_state=on
,D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43268168 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1846): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 19:13:45
,I/SlideAside( 3536): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1846): 2 : This is isUpdating : false
,D/WeatherAncestor( 1846): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 19:13:45
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/WeatherService( 1846): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1846): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  950): Excessive delay in blankDisplay() while turning screen off: 401ms
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.426636 Y: -0.375366 Z: 9.812607 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.426636 .y:-0.375366 .z:9.812607
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.451538 Y: -0.382263 Z: 9.787216 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451538 .y:-0.382263 .z:9.787216
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598426066, nextTick: 13966, mDrawingTime: 0
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598426116, nextTick: 13917, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=4
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,E/Parcel  (  582): Reading a NULL string not supported here.
E/Parcel  (  582): Reading a NULL string not supported here.
E/Parcel  (  582): Reading a NULL string not supported here.
,E/Parcel  (  582): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/WeatherService( 1846): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:13:46
D/WeatherService( 1846): 2 : ACTION screen on
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/WeatherService( 1846): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:13:46
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  950): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  950): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
,I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
,V/ActivityManager(  950): Moving to PAUSING: ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  950): hal_acquire_resources
D/qcom_sensors_hal(  950): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  950): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  950): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  950): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  950): hal_smgr_report_delete: Rcvd success response from request
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  950): Vibrator off
,D/WifiStateMachine(  950): handleScreenStateChanged: false
V/ActivityManager(  950): Moving to PAUSED: ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  950): Moving to STOPPING: ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  950): handleMessage: E msg.what=131154
D/WifiStateMachine(  950): processMsg: InitialState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131158
D/WifiStateMachine(  950): processMsg: InitialState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): setSuspendOptimizations: 4 true
D/WifiStateMachine(  950): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  950): handleMessage: X
,E/AudioSystem(  950): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=off, calling pid 950
V/SRS_Proc(  272): ParamSet string: screen_state=off
,D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
D/WifiController(  950): CMD_SCREEN_OFF 
D/WifiController(  950): shouldWifiStayAwake TRUE
V/ActivityManager(  950): Moving to STOPPED: ActivityRecord{4307d458 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
D/EmotionalLed( 1155): RESTART MSG
D/VolumeVibrator( 1155): clear
,D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=2
,I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1846): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:13:46
D/WeatherService( 1846): 2 : ACTION screen off
,D/WeatherService( 1846): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:13:46
,V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  582): Reading a NULL string not supported here.
E/Parcel  (  582): Reading a NULL string not supported here.
E/Parcel  (  582): Reading a NULL string not supported here.
,E/Parcel  (  582): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/BrcmNfcJni( 1476): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1476): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/NfcService( 1476): NFC-C OFF
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Sensors (  560): sns_pwr.c(320):releasing wakelock
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  287): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598438886110622; DSPS: 5130508; Offset: 1449598282315431912
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598440044, nextTick: 59982, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598440049, nextTick: 59983, mDrawingTime: 0
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598458886971656; DSPS: 5785896; Offset: 1449598282315438453
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598478887863680; DSPS: 6441285; Offset: 1449598282315445468
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598498889180026; DSPS: 7096688; Offset: 1449598282315449558
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598500042, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598500045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598518890514862; DSPS: 7752092; Offset: 1449598282315441620
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598538890963188; DSPS: 8407467; Offset: 1449598282315432183
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598558892291253; DSPS: 9062870; Offset: 1449598282315447992
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598560046, nextTick: 59970, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598560057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598578894163381; DSPS: 9718292; Offset: 1449598282315428030
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598598895690301; DSPS: 10373702; Offset: 1449598282315429071
,I/LocationManagerService(  950): remove 42b16698
,D/LocationManagerService(  950): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  950): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  950): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  950): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  950): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598618897014720; DSPS: 11029105; Offset: 1449598282315441234
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598620046, nextTick: 59968, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598620057, nextTick: 59975, mDrawingTime: 0
,I/GLSUser ( 1553): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1553): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1553): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1553): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1553): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  950): updateLightListLocked :r=null, action=2
,W/GLSActivity( 1553): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1553): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1553): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1553): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1553): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/PlayEventLogger( 3719): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3719): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3719): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3719): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3719): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3719): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598638897858358; DSPS: 11684493; Offset: 1449598282315430380
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598658899118559; DSPS: 12339894; Offset: 1449598282315439360
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598678900533811; DSPS: 12995300; Offset: 1449598282315450804
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598680055, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598680059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598698902037085; DSPS: 13650710; Offset: 1449598282315428199
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598718903338848; DSPS: 14306112; Offset: 1449598282315448223
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  950): GC_CONCURRENT freed 1891K, 48% free 29910K/56692K, paused 6ms+9ms, total 143ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598738905237122; DSPS: 14961535; Offset: 1449598282315423890
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598740042, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598740057, nextTick: 59976, mDrawingTime: 0
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598758906524927; DSPS: 15616937; Offset: 1449598282315429957
,D/dalvikvm( 2638): GC_CONCURRENT freed 7580K, 32% free 16975K/24832K, paused 3ms+2ms, total 48ms
,D/dalvikvm( 2638): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 2638): GC_CONCURRENT freed 1493K, 30% free 17529K/24832K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 2638): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Mlt MonitorService( 2638): parseLastkmsg to dump
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598778907419555; DSPS: 16272326; Offset: 1449598282315439575
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598798908809183; DSPS: 16927732; Offset: 1449598282315425394
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598800041, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598800046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598818909238498; DSPS: 17583106; Offset: 1449598282315427463
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598838910503542; DSPS: 18238507; Offset: 1449598282315441287
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598858911748743; DSPS: 18893908; Offset: 1449598282315435267
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598860041, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598860044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598878912599412; DSPS: 19549296; Offset: 1449598282315431444
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598898914752165; DSPS: 20204727; Offset: 1449598282315417449
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598918916031741; DSPS: 20860128; Offset: 1449598282315445804
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598920041, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598920055, nextTick: 59977, mDrawingTime: 0
,I/GLSUser ( 1553): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1553): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1553): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1553): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1553): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x431095c8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1553): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1553): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1553): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1553): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1553): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3719): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3719): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3719): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3719): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3719): Ignoring header User-Agent because its value was null.
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598938917332723; DSPS: 21515531; Offset: 1449598282315434530
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598958918274174; DSPS: 22170922; Offset: 1449598282315429936
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598978919731926; DSPS: 22826329; Offset: 1449598282315453362
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598980039, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449598980043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449598998921003793; DSPS: 23481731; Offset: 1449598282315443491
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599018921872380; DSPS: 24137120; Offset: 1449598282315427068
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599038923180445; DSPS: 24792523; Offset: 1449598282315422877
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599040034, nextTick: 59983, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599040054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599058925032521; DSPS: 25447943; Offset: 1449598282315443898
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599078926285118; DSPS: 26103344; Offset: 1449598282315445275
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599098927713547; DSPS: 26758751; Offset: 1449598282315439378
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599100039, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599100043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599118929274372; DSPS: 27414162; Offset: 1449598282315443806
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599138930164574; DSPS: 28069551; Offset: 1449598282315448998
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599158931474513; DSPS: 28724954; Offset: 1449598282315446681
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599160040, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599160044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599178932383517; DSPS: 29380344; Offset: 1449598282315440158
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599198934210905; DSPS: 30035764; Offset: 1449598282315436491
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599218935497668; DSPS: 30691166; Offset: 1449598282315441516
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599220042, nextTick: 59976, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599220051, nextTick: 59981, mDrawingTime: 0
,I/GLSUser ( 1553): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1553): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1553): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1553): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1553): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x42c599d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1553): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1553): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1553): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1553): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1553): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3719): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3719): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3719): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3719): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3719): Ignoring header User-Agent because its value was null.
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599238937042036; DSPS: 31346577; Offset: 1449598282315429488
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599258937924944; DSPS: 32001966; Offset: 1449598282315427386
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599278939191551; DSPS: 32657367; Offset: 1449598282315442772
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599280041, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599280046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599298940473367; DSPS: 33312769; Offset: 1449598282315442850
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599318941782682; DSPS: 33968172; Offset: 1449598282315439909
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599338942617726; DSPS: 34623559; Offset: 1449598282315450978
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599340044, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599340049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599358944569698; DSPS: 35278983; Offset: 1449598282315449825
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599378945424117; DSPS: 35934371; Offset: 1449598282315449752
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599398946805516; DSPS: 36589777; Offset: 1449598282315427343
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599400047, nextTick: 59969, mDrawingTime: 7,
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599400058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599418948085561; DSPS: 37245179; Offset: 1449598282315425649
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599438949338938; DSPS: 37900580; Offset: 1449598282315427806
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599458950871483; DSPS: 38555990; Offset: 1449598282315434472
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599460046, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599460056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599478951299339; DSPS: 39211364; Offset: 1449598282315435082
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599498952151728; DSPS: 39866752; Offset: 1449598282315432978
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599518953999064; DSPS: 40522172; Offset: 1449598282315449260
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599520042, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599520045, nextTick: 59987, mDrawingTime: 0
,I/GLSUser ( 1553): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1553): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1553): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1553): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1553): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x4288d018: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1553): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1553): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1553): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1553): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1553): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3719): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3719): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3719): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3719): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3719): Ignoring header User-Agent because its value was null.
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  265): write error (Broken pipe)
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599538954779473; DSPS: 41177558; Offset: 1449598282315436212
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599558955614778; DSPS: 41832945; Offset: 1449598282315447542
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599578956866333; DSPS: 42488346; Offset: 1449598282315447876
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599580047, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599580050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599598958217731; DSPS: 43143751; Offset: 1449598282315425983
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599618959469078; DSPS: 43799152; Offset: 1449598282315426110
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599638960718028; DSPS: 44454553; Offset: 1449598282315423839
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599640046, nextTick: 59978, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599640051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599658962001926; DSPS: 45109955; Offset: 1449598282315425999
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599678963318638; DSPS: 45765358; Offset: 1449598282315430455
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599698965379568; DSPS: 46420785; Offset: 1449598282315446707
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599700050, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599700056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599718966681697; DSPS: 47076188; Offset: 1449598282315436580
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599738967993199; DSPS: 47731591; Offset: 1449598282315435826
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599758969245847; DSPS: 48386992; Offset: 1449598282315437254
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599760044, nextTick: 59975, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599760054, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599778970525163; DSPS: 49042394; Offset: 1449598282315434831
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599798971774999; DSPS: 49697795; Offset: 1449598282315433447
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599818973082282; DSPS: 50353198; Offset: 1449598282315428474
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599820036, nextTick: 59982, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599820044, nextTick: 59987, mDrawingTime: 1
,I/GLSUser ( 1553): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1553): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1553): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1553): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1553): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x43ca1bf8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1553): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1553): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1553): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1553): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1553): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3719): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3719): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3719): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3719): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3719): Ignoring header User-Agent because its value was null.
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  265): write error (Broken pipe)
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599838974947172; DSPS: 51008619; Offset: 1449598282315431792
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599858975773986; DSPS: 51664006; Offset: 1449598282315434631
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599878976953511; DSPS: 52319404; Offset: 1449598282315454488
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599880049, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599880054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599898978235950; DSPS: 52974807; Offset: 1449598282315424671
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599918979912765; DSPS: 53630222; Offset: 1449598282315423019
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599938981165779; DSPS: 54285623; Offset: 1449598282315424813
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599940041, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449599940056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599958982500562; DSPS: 54941026; Offset: 1449598282315447340
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599978984313784; DSPS: 55596446; Offset: 1449598282315429507
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449599998985147475; DSPS: 56251833; Offset: 1449598282315439224
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449600000037, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449600000042, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600018986501634; DSPS: 56907237; Offset: 1449598282315450609
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600038987754804; DSPS: 57562639; Offset: 1449598282315422041
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600058989263493; DSPS: 58218048; Offset: 1449598282315435368
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449600060037, nextTick: 59977, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449600060053, nextTick: 59975, mDrawingTime: 2
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600078990103798; DSPS: 58873435; Offset: 1449598282315451699
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600098995679937; DSPS: 59528978; Offset: 1449598282315443121
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600118996275242; DSPS: 60184358; Offset: 1449598282315428075
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449600120097, nextTick: 59931, mDrawingTime: 4
D/Clock   ( 1141): Clock updated, drawingStartTime : 1449600120098, nextTick: 59933, mDrawingTime: 1
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
I/ProcessStatsService(  950): Prepared write state in 62ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ProcessStatsService(  950): Pruning old procstats: /data/system/procstats/state-2015-12-07-22-13-07.bin
,D/dalvikvm(  950): GC_CONCURRENT freed 3269K, 47% free 29942K/55612K, paused 6ms+8ms, total 202ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
,I/GLSUser ( 1553): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1553): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1553): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1553): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1553): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x432bdc00: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1553): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1553): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1553): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1553): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1553): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1553): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3719): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3719): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3719): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3719): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3719): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3719): Ignoring header User-Agent because its value was null.
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  265): write error (Broken pipe)
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600138997390494; DSPS: 60839754; Offset: 1449598282315444694
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600158998725591; DSPS: 61495158; Offset: 1449598282315437017
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600179000232406; DSPS: 62150567; Offset: 1449598282315448471
,I/ActivityManager(  950): Killing 3205:com.android.mms/u0a35 (adj 15): empty for 1853s
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449600180058, nextTick: 59973, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449600180059, nextTick: 59974, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/CountryDetector(  950): No listener is left
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c00920 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1449600199001084949; DSPS: 62805955; Offset: 1449598282315446522
,TIME-OUT KILL (timeout was 1800000ms)
```
