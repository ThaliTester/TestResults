#### Test 50650278cc6513d_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1943): Using Auth Proxy for data requests.
,D/dalvikvm( 1943): GC_CONCURRENT freed 1512K, 26% free 18500K/24832K, paused 1ms+4ms, total 27ms
W/GAV2    ( 4050): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  959): Killing 3346:com.google.android.music:main/u0a107 (adj 15): empty #17
F/ActivityManager(  959): Service ServiceRecord{432ea730 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432cc148 3346:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  959): Service ServiceRecord{431b09b8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432cc148 3346:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322a608 stackId=1, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4091): 
D/AndroidRuntime( 4091): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4091): CheckJNI is OFF
D/dalvikvm( 4091): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4091): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4091): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4091): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4091): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4091): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  959): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/memtrack( 4091): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4091): failed to load memtrack module: -2
I/Icing   ( 1943): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4091): Calling main entry com.android.commands.am.Am
D/Icing   ( 1943): Loaded CLD2 Version V2.0 - 20141016
I/ActivityManager(  959): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4091
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322a608 stackId=1, 2 tasks}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (101 us)
V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  959): resumeTopActivityLocked: Pausing null
V/ActivityManager(  959): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  959): startService SlideAside
W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  959): setFocusedStack: mFocusedStack=ActivityStack{4322a608 stackId=1, 2 tasks}
D/AndroidRuntime( 4091): Shutting down VM
D/UsbSettingsControl( 2528): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2528): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4091): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  959): allPausedActivitiesComplete: r=ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322a608 stackId=1, 2 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Restarting ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  959): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4109 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  959): Moving to RESUMED: ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3516): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm(  269): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+1ms, total 25ms
D/HyLog   ( 4109): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4109): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4109): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 17ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3516): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3516): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 16ms
V/WebViewChromium( 4109): Binding Chromium to the background looper Looper (main, tid 1) {428bbff8}
I/chromium( 4109): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4109): Initializing chromium process, renderers=0
I/Icing   ( 1943): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/chromium( 4109): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4109): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4109): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4109): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4109): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4109): Remote Branch: 
I/Adreno-EGL( 4109): Local Patches: 
I/Adreno-EGL( 4109): Reconstruct Branch: 
I/dalvikvm( 4109): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4109): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4109): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4109): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4109): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4109): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4109): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4109): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4109): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4109): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4109): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4109): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4109): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4109): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4109): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4109): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4109): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4109): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4109): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4109): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4109): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4109): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4109): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4109): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4109): Enabling debug mode 0
W/AwContents( 4109): nativeOnDraw failed; clearing to background color.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  959): Displayed com.test.thalitest/.MainActivity: +366ms
W/AwContents( 4109): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  959): IME STATUS OFF
I/ActivityManager( 4109): Timeline: Activity_idle id: android.os.BinderProxy@428bd8b8 time:107320
D/JsMessageQueue( 4109): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4109): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428c1998
D/dalvikvm( 4109): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428c1998
D/jxcore_app_log( 4109): JniHelper::setJavaVM(0x4177e838), pthread_self() = 1639295216
D/JX-Cordova( 4109): jxcore cordova android initializing
I/dalvikvm( 4109): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4109): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4109): VFY: replacing opcode 0x6e at 0x0045
D/ActivityManager(  959): no-history finish of ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2}
I/ActivityManager(  959): Timeline: Activity_windows_visible id: ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3} time:107707
V/ActivityManager(  959): Finishing activity token=Token{43374548 ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  959): Moving to FINISHING: ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3}
D/UsbSettings( 2528): [AUTORUN] onStop()
V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  959): Moving to STOPPED: ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4109): GC_CONCURRENT freed 2805K, 13% free 21833K/24832K, paused 1ms+2ms, total 45ms
,D/dalvikvm( 4109): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 113K, 13% free 21833K/24832K, paused 21ms, total 21ms
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 301K, 12% free 21899K/24832K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 23.696MB for 143930-byte allocation
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 265K, 13% free 21935K/24976K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 23.800MB for 215890-byte allocation
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 367K, 13% free 22008K/25188K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 23.975MB for 323830-byte allocation
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 565K, 14% free 22129K/25508K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 24.248MB for 485740-byte allocation
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 862K, 15% free 22305K/25984K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 24.650MB for 728606-byte allocation
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 1279K, 16% free 22561K/26696K, paused 30ms, total 30ms
,D/dalvikvm( 4109): GC_CONCURRENT freed 1677K, 15% free 22932K/26696K, paused 1ms+2ms, total 31ms
,D/dalvikvm( 4109): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 365K, 15% free 22887K/26696K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 26.087MB for 1639352-byte allocation
,D/dalvikvm( 4109): GC_CONCURRENT freed 1612K, 18% free 23453K/28300K, paused 2ms+3ms, total 38ms
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 1427K, 17% free 23539K/28300K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 27.505MB for 2459024-byte allocation
,D/dalvikvm( 4109): GC_CONCURRENT freed 336K, 16% free 25843K/30704K, paused 2ms+2ms, total 57ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 4272K, 21% free 24497K/30704K, paused 28ms, total 36ms
,I/dalvikvm-heap( 4109): Grow heap (frag case) to 29.614MB for 3688532-byte allocation
,D/dalvikvm( 4109): GC_CONCURRENT freed 342K, 18% free 28137K/34308K, paused 3ms+4ms, total 58ms
,D/dalvikvm( 4109): GC_FOR_ALLOC freed 3190K, 26% free 25459K/34308K, paused 24ms, total 24ms
,W/jxcore-log( 4109): Initializing JXcore engine
,W/jxcore-log( 4109): JXcore engine is ready
,D/dalvikvm( 4109): GC_CONCURRENT freed 371K, 19% free 28063K/34308K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4109): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4109): Starting JXcore engine
,W/jxcore-log( 4109): Platform android
W/jxcore-log( 4109): 
,W/jxcore-log( 4109): Process ARCH arm
W/jxcore-log( 4109): 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4109): JXcore Cordova bridge is ready!
I/jxcore-log( 4109): 
,W/jxcore-log( 4109): JXcore engine is started
,I/chromium( 4109): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4109): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4109): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore  ( 4109): Error!: missing ) after argument list
E/jxcore  ( 4109): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,V/ActivityManager(  959): Finishing activity token=Token{43ff38a0 ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
,V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3 f}
,I/chromium( 4109): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/dalvikvm(  959): GC_FOR_ALLOC freed 22203K, 50% free 28794K/56680K, paused 107ms, total 108ms
,W/PluginManager( 4109): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 119ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322a608 stackId=1, 2 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  959): moveHomeStack:
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c39670 stackId=0, 1 tasks}
V/ActivityManager(  959): Moving to RESUMED: ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  959): resumeTopActivityLocked: Resumed ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  959): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c39670 stackId=0, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1446): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1891): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:57:11
,D/UpdateThreadPoolManager( 1891): 2 : This is isUpdating : false
D/WeatherQuickCover( 1891): 2 : quick cover state : opened : 0
,D/WeatherService( 1891): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1891): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1891): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1891): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1891): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1891): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:57:11
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/WeatherService( 1891): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1891): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1891): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1891): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1891): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1891): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1891): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1891): 2 : This is isUpdating : false
D/WeatherService( 1891): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1891): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1891): 2 : Map key string is -2
,W/IInputConnectionWrapper( 4109): showStatusIcon on inactive InputConnection
,I/InputMethodManagerService(  959): IME STATUS OFF
D/lim     ( 1891): 2 : time = 15:57
I/WeatherReflect( 1891): Model Name : LG-D802
D/WeatherTheme( 1891): 2 : Different view - status_min_formatted : 55 != 57
D/WeatherTheme( 1891): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1891): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1891): 2 : Fixed theme : optimus
D/WeatherTheme( 1891): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1891): 2 : quick cover state : opened : 0
D/Weather.Utils( 1891): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1891): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1891): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 5580K, 10% free 71049K/78332K, paused 32ms, total 36ms
,D/dalvikvm( 1487): GC_CONCURRENT freed 5374K, 9% free 61087K/66664K, paused 1ms+3ms, total 26ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@428b6fb0 time:110749
,D/UsbSettings( 2528): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2528): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2528): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2528): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  959): Moving to DESTROYING: ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{42b9b8d8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c39670 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  959): Timeline: Activity_windows_visible id: ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1} time:110817
V/ActivityManager(  959): Moving to FINISHING: ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  959): Killing 2134:android.process.media/u0a23 (adj 15): empty #17
V/ActivityManager(  959): Moving to DESTROYING: ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4109): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c39670 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{43c49e30 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c39670 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4050): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1532): onDestroy
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.453018 Y: -0.393814 Z: 9.750336 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453018 .y:-0.393814 .z:9.750336
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.461975 Y: -0.389786 Z: 9.751587 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461975 .y:-0.389786 .z:9.751587
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  959): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 3678): [337] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3678): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.457138 Y: -0.383286 Z: 9.789871 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457138 .y:-0.383286 .z:9.789871
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.447586 Y: -0.395309 Z: 9.777466 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447586 .y:-0.395309 .z:9.777466
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,I/PowerManagerService(  959): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  959): [updateScreenState] screen on = false
,D/KnockOnPowerController(  959): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  959): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  959): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  959): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  959): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  959): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  959): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9073 usec
,D/qcom_sensors_hal(  959): hal_acquire_resources
,I/qcom_sensors_hal(  959): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  959): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  959): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  959): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  959): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  959): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  959): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  959): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.445770 Y: -0.372284 Z: 9.764236 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445770 .y:-0.372284 .z:9.764236
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.444931 Y: -0.375931 Z: 9.783920 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444931 .y:-0.375931 .z:9.783920
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,I/Sensors (  471): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  959): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  959): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  959): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  959): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  959): proximitySensorChanged  positive = true
I/KnockOnPowerController(  959): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.450760 Y: -0.379593 Z: 9.787125 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450760 .y:-0.379593 .z:9.787125
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.453720 Y: -0.373856 Z: 9.764267 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453720 .y:-0.373856 .z:9.764267
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.455032 Y: -0.369156 Z: 9.781021 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455032 .y:-0.369156 .z:9.781021
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.458191 Y: -0.384415 Z: 9.787506 ,
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.448212 Y: -0.373306 Z: 9.779739 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.458191 .y:-0.384415 .z:9.787506
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  959): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@42c1f270)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb7da0450
,D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  959): **** SHOWN CALLED ****
I/WindowManager(  959): No lock screen! windowToken=null
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.444443 Y: -0.379837 Z: 9.765747 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444443 .y:-0.379837 .z:9.765747
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WeatherAncestor( 1891): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:57:39
,E/SlideAside( 3516): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3516): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/WifiStateMachine(  959): handleScreenStateChanged: true
,D/WifiServiceExtension(  959): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  959): handleMessage: E msg.what=131154
,D/WifiStateMachine(  959): processMsg: InitialState
D/WifiStateMachine(  959): processMsg: DefaultState
,D/WifiStateMachine(  959): handleMessage: X
D/WifiStateMachine(  959): handleMessage: E msg.what=131127
D/WifiStateMachine(  959): processMsg: InitialState
,D/WifiStateMachine(  959): processMsg: DefaultState
D/WifiStateMachine(  959): handleMessage: X
D/WifiStateMachine(  959): handleMessage: E msg.what=131158
,D/WifiStateMachine(  959): processMsg: InitialState
D/WifiStateMachine(  959): processMsg: DefaultState
D/WifiStateMachine(  959): setSuspendOptimizations: 4 false
,D/WifiStateMachine(  959): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  959): handleMessage: X
,D/WifiOffDelayIfNotUsed(  959): stopMonitoring
,E/AudioSystem(  959): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 959
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4333b808 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1891): 2 : This is isUpdating : false
,D/WeatherAncestor( 1891): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:57:39
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/WeatherService( 1891): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1891): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1891): 2 : TimeTick Receiver Unregister
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1891): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1154): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1154): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.461990 Y: -0.378571 Z: 9.783417 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461990 .y:-0.378571 .z:9.783417
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  959): Excessive delay in blankDisplay() while turning screen off: 401ms
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.460449 Y: -0.377167 Z: 9.782471 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460449 .y:-0.377167 .z:9.782471
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586660204, nextTick: 19828, mDrawingTime: 0
,D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586660230, nextTick: 19802, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
D/WeatherService( 1891): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:57:40
,D/WeatherService( 1891): 2 : ACTION screen on
,D/WeatherService( 1891): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1891): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:57:40
,D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  959): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  495): Reading a NULL string not supported here.
E/Parcel  (  495): Reading a NULL string not supported here.
E/Parcel  (  495): Reading a NULL string not supported here.
,E/Parcel  (  495): Reading a NULL string not supported here.
D/GsmSST  ( 1446): Emergency Service
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1446): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1446): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,V/PhoneApp( 1446): Action intent recieved:android.intent.action.SCREEN_ON
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  959): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  959): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
D/qcom_sensors_hal(  959): hal_acquire_resources
D/qcom_sensors_hal(  959): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  959): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=1000
D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  959): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  959): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  959): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
W/ProcessCpuTracker(  959): Skipping unknown process pid 4250
W/ProcessCpuTracker(  959): Skipping unknown process pid 4251
W/ProcessCpuTracker(  959): Skipping unknown process pid 4257
W/ProcessCpuTracker(  959): Skipping unknown process pid 4258
W/ProcessCpuTracker(  959): Skipping unknown process pid 4263
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
,I/LGImmersionVibrator(  959): Vibrator off
,D/WifiStateMachine(  959): handleScreenStateChanged: false
D/WifiStateMachine(  959): handleMessage: E msg.what=131154
D/WifiStateMachine(  959): processMsg: InitialState
D/WifiStateMachine(  959): processMsg: DefaultState
,D/WifiStateMachine(  959): handleMessage: X
D/WifiStateMachine(  959): handleMessage: E msg.what=131158
D/WifiStateMachine(  959): processMsg: InitialState
D/WifiStateMachine(  959): processMsg: DefaultState
D/WifiStateMachine(  959): setSuspendOptimizations: 4 true
D/WifiStateMachine(  959): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  959): handleMessage: X
D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
V/ActivityManager(  959): Moving to STOPPED: ActivityRecord{430e44f8 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  959): CMD_SCREEN_OFF 
,D/WifiController(  959): shouldWifiStayAwake TRUE
I/dalvikvm(  959): Jit: resizing JitTable from 8192 to 16384
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
D/KeyguardViewManager( 1140): onScreenTurnedOff()
E/AudioSystem(  959): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 959
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1154): clear
D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,V/TelephonyAutoProfiling(  959): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  495): Reading a NULL string not supported here.
E/Parcel  (  495): Reading a NULL string not supported here.
E/Parcel  (  495): Reading a NULL string not supported here.
,E/Parcel  (  495): Reading a NULL string not supported here.
D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WeatherService( 1891): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:57:40
D/WeatherService( 1891): 2 : ACTION screen off
,D/WeatherService( 1891): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:57:40
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1446): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1446): Emergency Service
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1446): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_smart_dialing, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_gfit, value : null
D/NfcService( 1474): NFC-C OFF
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
V/PhoneApp( 1446): Action intent recieved:android.intent.action.SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  471): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1446): getIsInUseVoLTE : false
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/PhoneApp( 1446): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  959): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586673276410518; DSPS: 5118165; Offset: 1449586517082410274
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586680035, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586680043, nextTick: 59989, mDrawingTime: 0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  959): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586693277716968; DSPS: 5773568; Offset: 1449586517082404468
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586713279261649; DSPS: 6428978; Offset: 1449586517082423271
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586733280564453; DSPS: 7084381; Offset: 1449586517082413819
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586740042, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586740046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586753282092831; DSPS: 7739791; Offset: 1449586517082416318
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586773283327094; DSPS: 8395192; Offset: 1449586517082399360
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586793285038649; DSPS: 9050607; Offset: 1449586517082432448
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586800041, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586800045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586813285924059; DSPS: 9705997; Offset: 1449586517082402331
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586833287163426; DSPS: 10361397; Offset: 1449586517082420995
,D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006,
D/QcConnectivityService(  959): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1532): Vacuum at: now=1449586842907 tag=VacuumService
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LocationManagerService(  959): remove 42a26d78
,D/LocationManagerService(  959): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  959): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  959): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  959): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  959): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586853288163522; DSPS: 11016790; Offset: 1449586517082414011
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  959): updateLightListLocked :r=null, action=2
,W/GLSActivity( 1532): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1532): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1532): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1532): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1532): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1532): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1532): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1532): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/PlayEventLogger( 3678): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3678): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3678): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3678): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3678): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3678): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3678): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3678): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  959): GC_CONCURRENT freed 1780K, 47% free 30084K/56680K, paused 7ms+7ms, total 147ms
,W/System  ( 3678): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3678): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =0
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586860042, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586860046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586873291259660; DSPS: 11672251; Offset: 1449586517082427873
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586893292106736; DSPS: 12327639; Offset: 1449586517082420457
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449586913292963760; DSPS: 12983027; Offset: 1449586517082422989
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586920041, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449586920051, nextTick: 59972, mDrawingTime: 3

```
