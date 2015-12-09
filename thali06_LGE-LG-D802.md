#### Test 50650278eab32a5_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1875): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1875): launchTask
W/dalvikvm( 1875): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1875): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WBKaowq0FQEaVXefge7sPhlxoH22bRvVhQk5gJ6IGaZQxHwOTFmeJV_o7bjQpvB1bXmk8x7V06l2CcUyI5bxUE7bc6xOSbr_1B2zJ0GKzlBIuDlBJRRzKUHGlazvT_Ov9GGy4MaiedCHED-UxQVnfPbJbBtR-4sQKKuOFaqbOpY_DdBRmVNR2jAZgZieu1oJu_nu5A
D/ChimeraCfgMgr( 1875): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1875): Module APK com.google.android.play.games already loaded
I/GoogleURLConnFactory( 1875): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1875): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1875): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1875): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1875): No vision deps
I/PeopleContactsSync( 1875): CP2 sync disabled
I/dalvikvm( 1875): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1875): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1875): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1875): Using Auth Proxy for data requests.
W/BaseAppContext( 1875): Using Auth Proxy for data requests.
,W/GAV2    ( 4175): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): Killing 3502:com.android.calendar/u0a15 (adj 15): empty #17
W/BaseAppContext( 1875): Using Auth Proxy for data requests.
E/DataScheduler( 1875): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =0
D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1875): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1875): fetch service done; releasing wakelock
I/ConfigFetchService( 1875): stopping self
W/BaseAppContext( 1875): Using Auth Proxy for data requests.
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306ff20 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1875): Using Auth Proxy for data requests.
W/BaseAppContext( 1875): Using Auth Proxy for data requests.
D/dalvikvm( 1875): GC_CONCURRENT freed 1618K, 27% free 18353K/24832K, paused 2ms+4ms, total 29ms
D/ChimeraCfgMgr( 1875): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1875): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4225): 
D/AndroidRuntime( 4225): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4225): CheckJNI is OFF
D/dalvikvm( 4225): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4225): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4225): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4225): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4225): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4225): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4225): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4225): failed to load memtrack module: -2
I/Icing   ( 1875): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4225): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4225
D/Icing   ( 1875): Loaded CLD2 Version V2.0 - 20141016
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (119 us)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306ff20 stackId=1, 2 tasks}
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{4306ff20 stackId=1, 2 tasks}
D/AndroidRuntime( 4225): Shutting down VM
D/UsbSettingsControl( 2595): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2595): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306ff20 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4225): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4240 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3623): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/SlideAside( 3623): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/HyLog   ( 4240): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4240): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4240): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/SlideAside( 3623): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Icing   ( 1875): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4240): Binding Chromium to the background looper Looper (main, tid 1) {42c45f88}
I/chromium( 4240): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4240): Initializing chromium process, renderers=0
W/chromium( 4240): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4240): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4240): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4240): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4240): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4240): Remote Branch: 
I/Adreno-EGL( 4240): Local Patches: 
I/Adreno-EGL( 4240): Reconstruct Branch: 
I/dalvikvm( 4240): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4240): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4240): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4240): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4240): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4240): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4240): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4240): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4240): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4240): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4240): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4240): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4240): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4240): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4240): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4240): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4240): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4240): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4240): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4240): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4240): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4240): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4240): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4240): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4240): Enabling debug mode 0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/AwContents( 4240): nativeOnDraw failed; clearing to background color.
W/AwContents( 4240): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  967): IME STATUS OFF
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +491ms
I/ActivityManager( 4240): Timeline: Activity_idle id: android.os.BinderProxy@42c47668 time:107431
D/JsMessageQueue( 4240): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4240): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42c4bb80
D/dalvikvm( 4240): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42c4bb80
D/jxcore_app_log( 4240): JniHelper::setJavaVM(0x41bf9808), pthread_self() = 1638881080
D/JX-Cordova( 4240): jxcore cordova android initializing
I/dalvikvm( 4240): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4240): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4240): VFY: replacing opcode 0x6e at 0x0045
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3} time:107719
D/ActivityManager(  967): no-history finish of ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{4353b3b0 ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2595): [AUTORUN] onStop()
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4240): GC_CONCURRENT freed 2779K, 13% free 21833K/24832K, paused 3ms+1ms, total 53ms
D/dalvikvm( 4240): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 4240): GC_FOR_ALLOC freed 100K, 13% free 21846K/24832K, paused 22ms, total 22ms
I/dalvikvm-heap( 4240): Grow heap (frag case) to 23.568MB for 63974-byte allocation
D/dalvikvm( 4240): GC_FOR_ALLOC freed 136K, 13% free 21860K/24896K, paused 22ms, total 22ms
D/dalvikvm( 4240): GC_FOR_ALLOC freed 187K, 13% free 21889K/24896K, paused 22ms, total 22ms
I/dalvikvm-heap( 4240): Grow heap (frag case) to 23.686MB for 143930-byte allocation
D/dalvikvm( 4240): GC_FOR_ALLOC freed 254K, 13% free 21936K/25040K, paused 22ms, total 22ms
I/dalvikvm-heap( 4240): Grow heap (frag case) to 23.801MB for 215890-byte allocation
D/dalvikvm( 4240): GC_FOR_ALLOC freed 368K, 13% free 22009K/25252K, paused 22ms, total 22ms
I/dalvikvm-heap( 4240): Grow heap (frag case) to 23.975MB for 323830-byte allocation
D/dalvikvm( 4240): GC_FOR_ALLOC freed 565K, 14% free 22130K/25572K, paused 23ms, total 23ms
I/dalvikvm-heap( 4240): Grow heap (frag case) to 24.248MB for 485740-byte allocation
D/dalvikvm( 4240): GC_FOR_ALLOC freed 862K, 15% free 22305K/26048K, paused 23ms, total 23ms
I/dalvikvm-heap( 4240): Grow heap (frag case) to 24.651MB for 728606-byte allocation
D/dalvikvm( 4240): GC_FOR_ALLOC freed 1278K, 16% free 22561K/26760K, paused 23ms, total 23ms
D/dalvikvm( 4240): GC_CONCURRENT freed 1677K, 15% free 22932K/26760K, paused 1ms+3ms, total 48ms
D/dalvikvm( 4240): WAIT_FOR_CONCURRENT_GC blocked 36ms
D/dalvikvm( 4240): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/dalvikvm( 4240): GC_FOR_ALLOC freed 362K, 15% free 22887K/26760K, paused 24ms, total 25ms
I/dalvikvm-heap( 4240): Grow heap (frag case) to 26.087MB for 1639352-byte allocation
,D/dalvikvm( 4240): GC_CONCURRENT freed 1613K, 18% free 23452K/28364K, paused 2ms+3ms, total 31ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4240): GC_FOR_ALLOC freed 1425K, 18% free 23539K/28364K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4240): Grow heap (frag case) to 27.506MB for 2459024-byte allocation
,D/dalvikvm( 4240): GC_CONCURRENT freed 374K, 17% free 25824K/30768K, paused 2ms+4ms, total 36ms
,D/dalvikvm( 4240): GC_FOR_ALLOC freed 4236K, 21% free 24498K/30768K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4240): Grow heap (frag case) to 29.615MB for 3688532-byte allocation
,D/dalvikvm( 4240): GC_CONCURRENT freed 481K, 19% free 28028K/34372K, paused 2ms+4ms, total 62ms
,D/dalvikvm( 4240): GC_FOR_ALLOC freed 3075K, 26% free 25436K/34372K, paused 24ms, total 24ms
,W/jxcore-log( 4240): Initializing JXcore engine
,W/jxcore-log( 4240): JXcore engine is ready
,D/dalvikvm( 4240): GC_CONCURRENT freed 348K, 19% free 28064K/34372K, paused 2ms+2ms, total 46ms
,D/dalvikvm( 4240): WAIT_FOR_CONCURRENT_GC blocked 39ms
,W/jxcore-log( 4240): Starting JXcore engine
,W/jxcore-log( 4240): Platform android
W/jxcore-log( 4240): 
,W/jxcore-log( 4240): Process ARCH arm
W/jxcore-log( 4240): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4240): JXcore Cordova bridge is ready!
I/jxcore-log( 4240): 
,W/jxcore-log( 4240): JXcore engine is started
,I/chromium( 4240): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4240): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4240): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore  ( 4240): Error!: missing ) after argument list
E/jxcore  ( 4240): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,V/ActivityManager(  967): Finishing activity token=Token{4444c1b0 ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
,I/chromium( 4240): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  967): GC_FOR_ALLOC freed 22165K, 49% free 29193K/57140K, paused 110ms, total 110ms
,W/PluginManager( 4240): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 123ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306ff20 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42fe14b0 stackId=0, 1 tasks}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42fe14b0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1829): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:45:42
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/UpdateThreadPoolManager( 1829): 2 : This is isUpdating : false
D/WeatherQuickCover( 1829): 2 : quick cover state : opened : 0
D/WeatherService( 1829): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1829): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1829): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1829): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1829): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1829): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:45:42
D/WeatherService( 1829): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1829): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1829): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1829): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/WeatherService( 1829): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1829): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1829): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1829): 2 : This is isUpdating : false
D/WeatherService( 1829): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1829): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1829): 2 : Map key string is -2
D/lim     ( 1829): 2 : time = 14:45
I/WeatherReflect( 1829): Model Name : LG-D802
D/WeatherTheme( 1829): 2 : Different view - status_min_formatted : 44 != 45
,D/WeatherTheme( 1829): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1829): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1829): 2 : Fixed theme : optimus
D/WeatherTheme( 1829): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,W/IInputConnectionWrapper( 4240): showStatusIcon on inactive InputConnection
I/InputMethodManagerService(  967): IME STATUS OFF
,D/WeatherQuickCover( 1829): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1829): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1829): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1829): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 6093K, 12% free 69556K/78612K, paused 29ms, total 30ms
,D/dalvikvm( 1489): GC_CONCURRENT freed 5429K, 9% free 61012K/66624K, paused 3ms+3ms, total 24ms
,D/dalvikvm( 1489): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@42c47f10 time:110887
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbSettings( 2595): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2595): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2595): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2595): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43609fa8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42fe14b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1} time:110983
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  967): Killing 3443:com.google.android.music:main/u0a107 (adj 15): empty #17
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4240): call to OpenGL ES API with no current context (logged once per thread)
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{452ca8b8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42fe14b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1}
,F/ActivityManager(  967): Service ServiceRecord{4364c798 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{435d0560 3443:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  967): Service ServiceRecord{4363cce8 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{435d0560 3443:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42fe14b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4175): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1544): onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1489): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.458755 Y: -0.395615 Z: 9.756744 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458755 .y:-0.395615 .z:9.756744
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.471634 Y: -0.407532 Z: 9.759705 
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.441666 Y: -0.380905 Z: 9.783020 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.471634 .y:-0.407532 .z:9.759705
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  294): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3803): [345] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3803): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.444580 Y: -0.383270 Z: 9.785294 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444580 .y:-0.383270 .z:9.785294
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.463058 Y: -0.370453 Z: 9.749557 
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459717 Y: -0.385986 Z: 9.762863 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.463058 .y:-0.370453 .z:9.749557
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668760032, nextTick: 59999, mDrawingTime: 1
,D/WeatherService( 1829): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:46:0
D/WeatherService( 1829): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1829): 2 : SDK version : 19
D/WeatherQuickCover( 1829): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1829): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1829): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1829): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1829): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1829): 2 : This is isUpdating : false
D/WeatherService( 1829): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1829): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1829): 2 : Map key string is -2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668760045, nextTick: 59988, mDrawingTime: 0
,D/lim     ( 1829): 2 : time = 14:46
,I/WeatherReflect( 1829): Model Name : LG-D802
D/WeatherTheme( 1829): 2 : Different view - status_min_formatted : 45 != 46
,D/WeatherTheme( 1829): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1829): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1829): 2 : Fixed theme : optimus
,D/WeatherTheme( 1829): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1829): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:46:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/dalvikvm(  967): Jit: resizing JitTable from 8192 to 16384
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9062 usec
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.467422 Y: -0.380142 Z: 9.774384 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467422 .y:-0.380142 .z:9.774384
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  332): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.447800 Y: -0.376724 Z: 9.774246 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447800 .y:-0.376724 .z:9.774246
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  967): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  967): proximitySensorChanged  positive = true
I/KnockOnPowerController(  967): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.438614 Y: -0.384064 Z: 9.786240 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438614 .y:-0.384064 .z:9.786240
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.442368 Y: -0.380676 Z: 9.796387 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442368 .y:-0.380676 .z:9.796387
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449173 Y: -0.381882 Z: 9.805939 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449173 .y:-0.381882 .z:9.805939
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449814 Y: -0.383621 Z: 9.808792 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449814 .y:-0.383621 .z:9.808792
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43651598)
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb85a8450
,D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
I/WindowManager(  967): No lock screen! windowToken=null
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.446014 Y: -0.379059 Z: 9.795853 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446014 .y:-0.379059 .z:9.795853
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,E/SlideAside( 3623): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: InitialState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: InitialState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: InitialState
,D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): setSuspendOptimizations: 4 false
D/WifiStateMachine(  967): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  278): ParamSet string: screen_state=on
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1159): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{436ff728 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1159): enqueuing start. mLedList.size()=2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1159): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1829): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:46:10
,I/SlideAside( 3623): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1829): 2 : This is isUpdating : false
,D/WeatherAncestor( 1829): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:46:10
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/WeatherService( 1829): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1829): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1829): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1829): 2 : shouldTimeTickRegistered : false
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459137 Y: -0.367447 Z: 9.772202 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.430267 Y: -0.382996 Z: 9.818832 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.459137 .y:-0.367447 .z:9.772202
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1159): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1159): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1159): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1159): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1159): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 219, B = 219
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.450195 Y: -0.375763 Z: 9.785217 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450195 .y:-0.375763 .z:9.785217
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/qdlights( 1159): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1159): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1159): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 423ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1159): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1159): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1159): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1159): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1159): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 165, B = 165
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 5726K, 12% free 69473K/78612K, paused 29ms, total 31ms
,D/qdlights( 1159): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 159, B = 159
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668770410, nextTick: 49623, mDrawingTime: 0
,D/qdlights( 1159): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1159): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 147, B = 147
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668770432, nextTick: 49601, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=4
,D/qdlights( 1159): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 141, B = 141
,D/WeatherService( 1829): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:46:10
,D/WeatherService( 1829): 2 : ACTION screen on
,D/WeatherService( 1829): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1159): set_light_notifications: 2,ff008787,10,0,2
D/WeatherService( 1829): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:46:10
,D/qdlights( 1159): [Current] = 255, R = 0, G = 135, B = 135
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qdlights( 1159): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 129, B = 129
V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
,V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
D/qdlights( 1159): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 123, B = 123
,D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,D/qdlights( 1159): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 117, B = 117
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/KeyguardViewMediator( 1143): handleNotifyScreenOff
D/KeyguardViewManager( 1143): onScreenTurnedOff()
,I/LGImmersionVibrator(  967): Vibrator off
,D/WifiStateMachine(  967): handleScreenStateChanged: false
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: InitialState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: InitialState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): setSuspendOptimizations: 4 true
D/WifiStateMachine(  967): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  967): handleMessage: X
D/qdlights( 1159): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 111, B = 111
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  278): ParamSet string: screen_state=off
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/WifiController(  967): CMD_SCREEN_OFF 
D/WifiController(  967): shouldWifiStayAwake TRUE
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4302d558 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1159): clear
D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=2
D/qdlights( 1159): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 105, B = 105
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1829): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:46:10
,D/WeatherService( 1829): 2 : ACTION screen off
,D/WeatherService( 1829): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:46:10
,D/qdlights( 1159): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 99, B = 99
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
E/Parcel  (  403): Reading a NULL string not supported here.
,E/Parcel  (  403): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1159): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 93, B = 93
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): Emergency Service
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/BrcmNfcJni( 1476): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1476): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,D/NfcService( 1476): NFC-C OFF
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1159): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 87, B = 87
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1159): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1159): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 75, B = 75
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 69, B = 69
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1159): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 63, B = 63
D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1159): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 57, B = 57
D/WifiController(  967): battery changed pluggedType: 2
,D/qdlights( 1159): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1159): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1159): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1159): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1159): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1159): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1159): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1159): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Sensors (  332): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  294): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668783323655882; DSPS: 5112979; Offset: 1449668627287919799
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668803324943582; DSPS: 5768381; Offset: 1449668627287925760
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  967): battery changed pluggedType: 2
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668820049, nextTick: 59980, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668820052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668823326255397; DSPS: 6423784; Offset: 1449668627287925319
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668843327560338; DSPS: 7079186; Offset: 1449668627287948522
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668863329019133; DSPS: 7734594; Offset: 1449668627287942473
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668880049, nextTick: 59982, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668880061, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668883330341364; DSPS: 8389998; Offset: 1449668627287921931
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668903331647347; DSPS: 9045400; Offset: 1449668627287946176
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668923332973120; DSPS: 9700804; Offset: 1449668627287929175
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668940040, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449668940053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668943334258164; DSPS: 10356206; Offset: 1449668627287932481
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668963335609926; DSPS: 11011610; Offset: 1449668627287941469
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x436701d8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/PlayEventLogger( 3803): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3803): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3803): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3803): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  967): GC_CONCURRENT freed 1892K, 47% free 30480K/57140K, paused 13ms+10ms, total 182ms
,W/System  ( 3803): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3803): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LocationManagerService(  967): remove 4369c718
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2656): GC_CONCURRENT freed 7705K, 32% free 16947K/24832K, paused 14ms+2ms, total 58ms
,D/dalvikvm( 2656): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/dalvikvm( 2656): GC_CONCURRENT freed 1846K, 32% free 17134K/24832K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2656): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2656): GC_CONCURRENT freed 1711K, 30% free 17470K/24832K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 2656): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/Mlt MonitorService( 2656): parseLastkmsg to dump
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449668983337223409; DSPS: 11667023; Offset: 1449668627287937521
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669000041, nextTick: 59974, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669000051, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669003339092985; DSPS: 12322444; Offset: 1449668627287945525
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669023340638655; DSPS: 12977855; Offset: 1449668627287934798,
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669043341910730; DSPS: 13633257; Offset: 1449668627287925135
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669060045, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669060056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669063343197962; DSPS: 14288659; Offset: 1449668627287930629
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669083344507121; DSPS: 14944062; Offset: 1449668627287927532
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669103345776853; DSPS: 15599463; Offset: 1449668627287946043
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669120048, nextTick: 59968, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669120059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669123346878512; DSPS: 16254859; Offset: 1449668627287949069
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669143349009234; DSPS: 16910289; Offset: 1449668627287943561
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669163350280894; DSPS: 17565691; Offset: 1449668627287933482
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669180039, nextTick: 59960, mDrawingTime: 14
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669180060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669183351782969; DSPS: 18221100; Offset: 1449668627287940196
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669203353071346; DSPS: 18876502; Offset: 1449668627287946835
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669223354593214; DSPS: 19531912; Offset: 1449668627287942824
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669240040, nextTick: 59983, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669240042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669243355868727; DSPS: 20187314; Offset: 1449668627287936599
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  967): Killing 3094:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42fe14b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669263357224761; DSPS: 20842718; Offset: 1449668627287949859
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x45187378: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3803): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3803): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3803): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3803): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3803): Ignoring header User-Agent because its value was null.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  271): write error (Broken pipe)
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669283359302567; DSPS: 21498146; Offset: 1449668627287952470
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669300046, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669300056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669303360835787; DSPS: 22153557; Offset: 1449668627287929293
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669323362198800; DSPS: 22808961; Offset: 1449668627287949533
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669343363580512; DSPS: 23464367; Offset: 1449668627287927436
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669360054, nextTick: 59968, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669360060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669363365076077; DSPS: 24119776; Offset: 1449668627287927640
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669383365947319; DSPS: 24775164; Offset: 1449668627287944390
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669403366830749; DSPS: 25430553; Offset: 1449668627287942810
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669420056, nextTick: 59968, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669420060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669423367779699; DSPS: 26085944; Offset: 1449668627287945715
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669443369108129; DSPS: 26741348; Offset: 1449668627287931372
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669463369550571; DSPS: 27396722; Offset: 1449668627287946568
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669480047, nextTick: 59966, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669480060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669483370413011; DSPS: 28052110; Offset: 1449668627287954515
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669503372011805; DSPS: 28707523; Offset: 1449668627287935878
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669523372971901; DSPS: 29362914; Offset: 1449668627287949929
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669540040, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669540060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669543374301738; DSPS: 30018318; Offset: 1449668627287936992
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669563375194282; DSPS: 30673707; Offset: 1449668627287944527
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x436649d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3803): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3803): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3803): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3803): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3803): Ignoring header User-Agent because its value was null.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669583376464274; DSPS: 31329109; Offset: 1449668627287932780
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669600045, nextTick: 59971, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669600053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669603378841611; DSPS: 31984547; Offset: 1449668627287929746
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669623380361343; DSPS: 32639957; Offset: 1449668627287923599
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669643381881544; DSPS: 33295366; Offset: 1449668627287948439
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669660043, nextTick: 59971, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669660059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669663382720286; DSPS: 33950754; Offset: 1449668627287932689
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669683384129080; DSPS: 34606160; Offset: 1449668627287937674
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669703385212979; DSPS: 35261555; Offset: 1449668627287953458
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669720049, nextTick: 59978, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669720061, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669723386501565; DSPS: 35916958; Offset: 1449668627287929788
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669743387424526; DSPS: 36572348; Offset: 1449668627287937222
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669763389084519; DSPS: 37227762; Offset: 1449668627287949266
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669780051, nextTick: 59975, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669780060, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669783389977375; DSPS: 37883152; Offset: 1449668627287926594
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669803391269764; DSPS: 38538554; Offset: 1449668627287937245
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669823391708246; DSPS: 39193928; Offset: 1449668627287948481
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,W/SocketClient(  271): write error (Broken pipe)
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669840032, nextTick: 59993, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669840038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669843393005269; DSPS: 39849331; Offset: 1449668627287933248
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669863394310366; DSPS: 40504734; Offset: 1449668627287926089
,D/dalvikvm( 1544): GC_EXPLICIT freed 1508K, 29% free 17824K/24832K, paused 3ms+11ms, total 56ms
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43620158: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3803): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3803): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3803): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3803): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/System  ( 3803): Ignoring header User-Agent because its value was null.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669883395864733; DSPS: 41160145; Offset: 1449668627287924060
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669900048, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669900052, nextTick: 59979, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669903396700454; DSPS: 41815532; Offset: 1449668627287935806
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669923398595498; DSPS: 42470954; Offset: 1449668627287938760
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669943399877054; DSPS: 43126356; Offset: 1449668627287938578
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669960052, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449669960059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669963401450900; DSPS: 43781768; Offset: 1449668627287925510
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449669983402312195; DSPS: 44437156; Offset: 1449668627287932313
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670003403838020; DSPS: 45092566; Offset: 1449668627287932259
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670020051, nextTick: 59979, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670020052, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670023404696607; DSPS: 45747954; Offset: 1449668627287936354
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670043405541703; DSPS: 46403342; Offset: 1449668627287926957
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670063414550029; DSPS: 47058997; Offset: 1449668627287932598
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670080043, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670080050, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670083415510542; DSPS: 47714388; Offset: 1449668627287947066
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670103416391784; DSPS: 48369777; Offset: 1449668627287943298
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670123417480265; DSPS: 49025173; Offset: 1449668627287933146
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670140040, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670140049, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670143419117395; DSPS: 49680586; Offset: 1449668627287952845
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670163420022387; DSPS: 50335976; Offset: 1449668627287942309
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x44d44428: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3803): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3803): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3803): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3803): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3803): Ignoring header User-Agent because its value was null.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  271): write error (Broken pipe)
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670183420471546; DSPS: 50991351; Offset: 1449668627287933705
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670200053, nextTick: 59967, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670200061, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670203421422475; DSPS: 51646742; Offset: 1449668627287938589
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670223421852728; DSPS: 52302116; Offset: 1449668627287941596
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670243422760012; DSPS: 52957506; Offset: 1449668627287933352
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670260041, nextTick: 59962, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670260060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670263423201305; DSPS: 53612880; Offset: 1449668627287947399
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670283428858331; DSPS: 54268426; Offset: 1449668627287928156
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670303430190458; DSPS: 54923829; Offset: 1449668627287948027
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670320052, nextTick: 59963, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670320060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670323431761128; DSPS: 55579241; Offset: 1449668627287931783
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670343433076693; DSPS: 56234644; Offset: 1449668627287935092
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670363434345903; DSPS: 56890046; Offset: 1449668627287922564
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670380039, nextTick: 59974, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670380050, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670383435729229; DSPS: 57545451; Offset: 1449668627287932599
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670403437051201; DSPS: 58200854; Offset: 1449668627287942315
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670423438873486; DSPS: 58856274; Offset: 1449668627287933545
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670440057, nextTick: 59932, mDrawingTime: 18
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670440083, nextTick: 59950, mDrawingTime: 0
I/ProcessStatsService(  967): Prepared write state in 22ms
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-11-35.bin
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670443439854206; DSPS: 59511666; Offset: 1449668627287937703
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670463441178679; DSPS: 60167069; Offset: 1449668627287949920
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  967): GC_CONCURRENT freed 3903K, 48% free 30006K/57132K, paused 12ms+9ms, total 230ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 108ms
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3803): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3803): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3803): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3803): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3803): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3803): Ignoring header User-Agent because its value was null.
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x44882af0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/libc    (  271): _dns_getaddrinfo: iptype =0
D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670483442735077; DSPS: 60822480; Offset: 1449668627287949921
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,I/ActivityManager(  967): Killing 3895:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1828s
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670500027, nextTick: 59994, mDrawingTime: 10
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1449670500060, nextTick: 59972, mDrawingTime: 0
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42fe14b0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670503444076319; DSPS: 61477884; Offset: 1449668627287948390
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670523445685478; DSPS: 62133297; Offset: 1449668627287940117
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1449670543446948127; DSPS: 62788699; Offset: 1449668627287921028
,TIME-OUT KILL (timeout was 1800000ms)
```
