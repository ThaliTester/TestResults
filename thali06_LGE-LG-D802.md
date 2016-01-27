#### Test 564496604206eac_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4062): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 3349:com.google.android.music:main/u0a107 (adj 15): empty #17
F/ActivityManager(  966): Service ServiceRecord{432ccc30 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43295fd0 3349:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  966): Service ServiceRecord{4327e030 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43295fd0 3349:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4334fb38 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1967): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1967): GC_CONCURRENT freed 1514K, 26% free 18435K/24832K, paused 3ms+3ms, total 28ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1967): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1967): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1967): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/AndroidRuntime( 4112): 
D/AndroidRuntime( 4112): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4112): CheckJNI is OFF
D/dalvikvm( 4112): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4112): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4112): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4112): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4112): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4112): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/memtrack( 4112): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4112): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4112): Calling main entry com.android.commands.am.Am
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4112
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4334fb38 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (90 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  966): GC_FOR_ALLOC freed 24096K, 54% free 27658K/59360K, paused 168ms, total 168ms
D/UsbSettingsControl( 2541): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2541): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4112): Shutting down VM
D/dalvikvm( 4112): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3510): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{4334fb38 stackId=1, 2 tasks}
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  966): startService SlideAside
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4334fb38 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4131 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3510): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3510): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4131): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4131): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4131): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4131): Binding Chromium to the background looper Looper (main, tid 1) {4288f160}
I/chromium( 4131): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4131): Initializing chromium process, renderers=0
I/Adreno-EGL( 4131): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4131): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4131): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4131): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4131): Remote Branch: 
I/Adreno-EGL( 4131): Local Patches: 
I/Adreno-EGL( 4131): Reconstruct Branch: 
W/chromium( 4131): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/dalvikvm( 4131): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4131): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4131): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4131): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4131): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4131): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4131): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4131): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4131): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4131): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4131): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4131): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4131): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4131): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4131): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4131): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4131): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4131): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4131): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4131): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4131): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4131): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4131): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4131): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4131): Enabling debug mode 0
,W/AwContents( 4131): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +495ms
,I/InputMethodManagerService(  966): IME STATUS OFF
W/AwContents( 4131): nativeOnDraw failed; clearing to background color.
,I/ActivityManager( 4131): Timeline: Activity_idle id: android.os.BinderProxy@42890840 time:109489
,D/JsMessageQueue( 4131): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4131): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42894920
,D/dalvikvm( 4131): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42894920
,D/jxcore_app_log( 4131): JniHelper::setJavaVM(0x41752838), pthread_self() = 1637539848
I/chromium( 4131): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3} time:109735
D/UsbSettings( 2541): [AUTORUN] onStop()
D/ActivityManager(  966): no-history finish of ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{4327cc48 ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/chromium( 4131): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4131): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4131): GC_CONCURRENT freed 2644K, 12% free 22009K/24832K, paused 3ms+3ms, total 42ms
D/dalvikvm( 4131): WAIT_FOR_CONCURRENT_GC blocked 32ms
D/dalvikvm( 4131): WAIT_FOR_CONCURRENT_GC blocked 31ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4131): GC_FOR_ALLOC freed 393K, 11% free 22313K/24832K, paused 29ms, total 30ms
D/dalvikvm( 4131): GC_FOR_ALLOC freed 104K, 11% free 22320K/24832K, paused 28ms, total 29ms
I/dalvikvm-heap( 4131): Grow heap (frag case) to 24.032MB for 63974-byte allocation
D/dalvikvm( 4131): GC_FOR_ALLOC freed 126K, 11% free 22340K/24896K, paused 26ms, total 26ms
I/dalvikvm-heap( 4131): Grow heap (frag case) to 24.082MB for 95956-byte allocation
D/dalvikvm( 4131): GC_FOR_ALLOC freed 179K, 11% free 22375K/24992K, paused 26ms, total 26ms
I/dalvikvm-heap( 4131): Grow heap (frag case) to 24.162MB for 143930-byte allocation
D/dalvikvm( 4131): GC_FOR_ALLOC freed 254K, 11% free 22422K/25136K, paused 27ms, total 27ms
I/dalvikvm-heap( 4131): Grow heap (frag case) to 24.276MB for 215890-byte allocation
D/dalvikvm( 4131): GC_FOR_ALLOC freed 366K, 12% free 22496K/25348K, paused 26ms, total 26ms
I/dalvikvm-heap( 4131): Grow heap (frag case) to 24.451MB for 323830-byte allocation
D/dalvikvm( 4131): GC_FOR_ALLOC freed 566K, 12% free 22616K/25668K, paused 24ms, total 25ms
,D/dalvikvm( 4131): GC_FOR_ALLOC freed 861K, 12% free 22793K/25668K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 25.127MB for 728606-byte allocation
,D/dalvikvm( 4131): GC_FOR_ALLOC freed 1279K, 13% free 23048K/26380K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 25.724MB for 1092904-byte allocation
,D/dalvikvm( 4131): GC_CONCURRENT freed 1927K, 15% free 23487K/27448K, paused 2ms+3ms, total 38ms
,D/dalvikvm( 4131): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 26.673MB for 1639352-byte allocation
,D/dalvikvm( 4131): GC_CONCURRENT freed 2139K, 18% free 23988K/29052K, paused 1ms+3ms, total 41ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4131): GC_FOR_ALLOC freed 894K, 18% free 23928K/29052K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 27.885MB for 2459024-byte allocation
,D/dalvikvm( 4131): GC_CONCURRENT freed 1916K, 22% free 24699K/31456K, paused 2ms+2ms, total 36ms
,D/dalvikvm( 4131): GC_CONCURRENT freed 2475K, 21% free 24968K/31456K, paused 2ms+4ms, total 48ms
,D/dalvikvm( 4131): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm( 4131): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4131): GC_FOR_ALLOC freed 252K, 22% free 24823K/31456K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 29.932MB for 3688532-byte allocation
,D/dalvikvm( 4131): GC_CONCURRENT freed 256K, 11% free 28288K/31456K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 4131): GC_FOR_ALLOC freed 4256K, 10% free 26092K/28832K, paused 29ms, total 31ms
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 30.539MB for 3024760-byte allocation
,W/jxcore-log( 4131): Initializing JXcore engine
,W/jxcore-log( 4131): JXcore engine is ready
,W/jxcore-log( 4131): Starting JXcore engine
,D/dalvikvm( 4131): GC_CONCURRENT freed 499K, 9% free 28949K/31788K, paused 1ms+3ms, total 45ms
,W/jxcore-log( 4131): Platform android
W/jxcore-log( 4131): 
,W/jxcore-log( 4131): Process ARCH arm
W/jxcore-log( 4131): 
,I/GAV2    ( 4062): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
,I/ConfigService( 1558): onDestroy
,I/jxcore-log( 4131): JXcore Cordova bridge is ready!
I/jxcore-log( 4131): 
,W/jxcore-log( 4131): JXcore engine is started
,E/jxcore  ( 4131): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4131): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4131): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  966): Finishing activity token=Token{4443cd78 ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  966): GC_CONCURRENT freed 1080K, 51% free 29258K/59360K, paused 2ms+4ms, total 71ms
,D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 68ms
,W/PluginManager( 4131): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 89ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4334fb38 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  966): moveHomeStack:
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cd1548 stackId=0, 1 tasks}
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  966): resumeTopActivityLocked: Resumed ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  966): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42cd1548 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1868): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 10:5:56
,D/UpdateThreadPoolManager( 1868): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1868): 2 : quick cover state : opened : 0
,D/WeatherService( 1868): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1868): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1868): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1868): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1868): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1868): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 10:5:56
D/WeatherService( 1868): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1868): 2 : quick cover state : opened : 0
D/Weather.Utils( 1868): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1868): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1868): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1868): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1868): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1868): 2 : This is isUpdating : false
D/WeatherService( 1868): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1868): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1868): 2 : Map key string is -2
,D/lim     ( 1868): 2 : time = 10:05
,I/WeatherReflect( 1868): Model Name : LG-D802
D/WeatherTheme( 1868): 2 : Different view - status_min_formatted : 04 != 05
D/WeatherTheme( 1868): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1868): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1868): 2 : Fixed theme : optimus
I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/WeatherTheme( 1868): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,W/IInputConnectionWrapper( 4131): showStatusIcon on inactive InputConnection
,D/WeatherQuickCover( 1868): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1868): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/InputMethodManagerService(  966): IME STATUS OFF
D/WeatherService( 1868): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1868): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 7225K, 13% free 68788K/78464K, paused 37ms, total 41ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1487): GC_CONCURRENT freed 5296K, 9% free 61080K/66600K, paused 3ms+4ms, total 25ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 19ms
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
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.584030 Y: -0.351425 Z: 9.811539 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.584030 .y:-0.351425 .z:9.811539
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@4288b098 time:112772
,D/UsbSettings( 2541): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2541): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2541): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2541): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{4310fb50 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cd1548 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1}
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.586060 Y: -0.352524 Z: 9.795349 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.586060 .y:-0.352524 .z:9.795349
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1} time:112868
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  966): Killing 3032:android.process.media/u0a23 (adj 15): empty #17
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4131): call to OpenGL ES API with no current context (logged once per thread)
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43a61d08 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cd1548 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cd1548 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1868): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:6:0
,D/WeatherService( 1868): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1868): 2 : SDK version : 19
,D/WeatherQuickCover( 1868): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1868): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1868): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1868): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1868): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1868): 2 : This is isUpdating : false
D/WeatherService( 1868): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1868): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1868): 2 : Map key string is -2
D/lim     ( 1868): 2 : time = 10:06
D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885560042, nextTick: 59987, mDrawingTime: 1
D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885560046, nextTick: 59987, mDrawingTime: 0
I/WeatherReflect( 1868): Model Name : LG-D802
D/WeatherTheme( 1868): 2 : Different view - status_min_formatted : 05 != 06
D/WeatherTheme( 1868): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1868): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1868): 2 : Fixed theme : optimus
D/WeatherTheme( 1868): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherService( 1868): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:6:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/Finsky  ( 3684): [333] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3684): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.582306 Y: -0.343552 Z: 9.824387 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.582306 .y:-0.343552 .z:9.824387
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.560501 Y: -0.346710 Z: 9.832596 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560501 .y:-0.346710 .z:9.832596
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/dalvikvm(  966): Jit: resizing JitTable from 8192 to 16384
,I/PowerManagerService(  966): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  966): [updateScreenState] screen on = false
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  966): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8429 usec
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  966): hal_acquire_resources
,I/qcom_sensors_hal(  966): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  966): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  966): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.564011 Y: -0.314941 Z: 9.835068 
V/qcom_sensors_hal(  966): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.564011 .y:-0.314941 .z:9.835068
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  966): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  966): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  966): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.577560 Y: -0.323822 Z: 9.821075 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.565338 Y: -0.332718 Z: 9.819962 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.577560 .y:-0.323822 .z:9.821075
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Sensors (  321): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  966): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  966): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  966): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  966): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  966): proximitySensorChanged  positive = true
I/KnockOnPowerController(  966): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.587051 Y: -0.311905 Z: 9.825211 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.587051 .y:-0.311905 .z:9.825211
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.579208 Y: -0.337402 Z: 9.831741 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.579208 .y:-0.337402 .z:9.831741
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.563446 Y: -0.339432 Z: 9.838394 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.563446 .y:-0.339432 .z:9.838394
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.579636 Y: -0.356293 Z: 9.823441 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.579636 .y:-0.356293 .z:9.823441
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.586365 Y: -0.356842 Z: 9.823685 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.586365 .y:-0.356842 .z:9.823685
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  966): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43264470)
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7c51450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  966): **** SHOWN CALLED ****
I/WindowManager(  966): No lock screen! windowToken=null
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  966): handleScreenStateChanged: true
,D/WifiServiceExtension(  966): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: InitialState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131127
D/WifiStateMachine(  966): processMsg: InitialState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: InitialState
,D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): setSuspendOptimizations: 4 false
D/WifiStateMachine(  966): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiOffDelayIfNotUsed(  966): stopMonitoring
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 966
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,E/SlideAside( 3510): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
,V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43377298 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
D/WeatherAncestor( 1868): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:6:23
I/SlideAside( 3510): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/UpdateThreadPoolManager( 1868): 2 : This is isUpdating : false
D/WeatherAncestor( 1868): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:6:23
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/WeatherService( 1868): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1868): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1868): 2 : TimeTick Receiver Unregister
D/WeatherService( 1868): 2 : shouldTimeTickRegistered : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.570862 Y: -0.340485 Z: 9.829620 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.570862 .y:-0.340485 .z:9.829620
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  966): Excessive delay in blankDisplay() while turning screen off: 401ms
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.567780 Y: -0.330475 Z: 9.820358 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.567780 .y:-0.330475 .z:9.820358
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1157): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 231, B = 231
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 5281K, 12% free 69105K/78464K, paused 25ms, total 25ms
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885583472, nextTick: 36561, mDrawingTime: 0
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885583491, nextTick: 36541, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/WeatherService( 1868): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:6:23
,D/WeatherService( 1868): 2 : ACTION screen on
,D/WeatherService( 1868): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1868): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:6:23
D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  966): hal_acquire_resources
D/qcom_sensors_hal(  966): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  966): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.562454 Y: -0.316422 Z: 9.846146 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.564667 Y: -0.319748 Z: 9.841690 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.562454 .y:-0.316422 .z:9.846146
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
D/qcom_sensors_hal(  966): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  966): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  966): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,D/KeyguardViewMediator( 1143): handleNotifyScreenOff
,D/KeyguardViewManager( 1143): onScreenTurnedOff()
E/Parcel  (  416): Reading a NULL string not supported here.
E/Parcel  (  416): Reading a NULL string not supported here.
E/Parcel  (  416): Reading a NULL string not supported here.
E/Parcel  (  416): Reading a NULL string not supported here.
D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,I/LGImmersionVibrator(  966): Vibrator off
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  966): handleScreenStateChanged: false
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: InitialState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: InitialState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): setSuspendOptimizations: 4 true
D/WifiStateMachine(  966): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  966): handleMessage: X
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 966
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{43196b48 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  966): CMD_SCREEN_OFF 
D/WifiController(  966): shouldWifiStayAwake TRUE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1157): clear
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/WeatherService( 1868): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:6:23
,D/WeatherService( 1868): 2 : ACTION screen off
,D/WeatherService( 1868): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:6:23
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  416): Reading a NULL string not supported here.
E/Parcel  (  416): Reading a NULL string not supported here.
E/Parcel  (  416): Reading a NULL string not supported here.
,E/Parcel  (  416): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/NfcService( 1474): NFC-C OFF
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  321): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885596499025152; DSPS: 5119555; Offset: 1453885440262605475
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  966): battery changed pluggedType: 2
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885616500884104; DSPS: 5774976; Offset: 1453885440262602854
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885620036, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885620053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885636502146492; DSPS: 6430378; Offset: 1453885440262583504
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885656503512838; DSPS: 7085782; Offset: 1453885440262607077
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885676504770226; DSPS: 7741184; Offset: 1453885440262582726
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885680041, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885680054, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885696505664906; DSPS: 8396573; Offset: 1453885440262592397
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885716506117919; DSPS: 9051948; Offset: 1453885440262587646
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885736506954682; DSPS: 9707335; Offset: 1453885440262600434
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885740034, nextTick: 59993, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885740044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885756507839050; DSPS: 10362724; Offset: 1453885440262599793
,I/LocationManagerService(  966): remove 42cc9660
,D/LocationManagerService(  966): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  966): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  966): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  966): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  966): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885776509148156; DSPS: 11018127; Offset: 1453885440262596643
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x43109c38: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1558): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1558): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1558): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1558): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1558): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3684): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3684): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3684): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3684): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3684): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3684): Ignoring header User-Agent because its value was null.
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885796512090388; DSPS: 11673583; Offset: 1453885440262609187
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885800033, nextTick: 59995, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885800039, nextTick: 59989, mDrawingTime: 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885816512965121; DSPS: 12328972; Offset: 1453885440262598911
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885836514291049; DSPS: 12984376; Offset: 1453885440262582065
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,D/dalvikvm( 2600): GC_CONCURRENT freed 7748K, 33% free 16857K/24832K, paused 2ms+1ms, total 35ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885856515167189; DSPS: 13639764; Offset: 1453885440262603713
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885860040, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885860053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885876516503275; DSPS: 14295168; Offset: 1453885440262597025
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885896517342746; DSPS: 14950556; Offset: 1453885440262582004
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885916518632218; DSPS: 15605958; Offset: 1453885440262589738
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885920047, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885920061, nextTick: 59969, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885936520470023; DSPS: 16261378; Offset: 1453885440262596488
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885956521436162; DSPS: 16916770; Offset: 1453885440262586065
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885976521863081; DSPS: 17572144; Offset: 1453885440262585738
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885980044, nextTick: 59964, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453885980060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453885996522892135; DSPS: 18227537; Offset: 1453885440262607712
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886016523302440; DSPS: 18882911; Offset: 1453885440262590771
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886036524572901; DSPS: 19538313; Offset: 1453885440262579493
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886040030, nextTick: 59996, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886040049, nextTick: 59984, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886056525002581; DSPS: 20193686; Offset: 1453885440262612445
,I/ActivityManager(  966): Killing 3210:com.android.mms/u0a35 (adj 15): empty #17
,D/CountryDetector(  966): No listener is left
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cd1548 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886076525857574; DSPS: 20849074; Offset: 1453885440262612946
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x43a1af80: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1558): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1558): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1558): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1558): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1558): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3684): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3684): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3684): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3684): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3684): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3684): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886096526728399; DSPS: 21504463; Offset: 1453885440262598761
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886100033, nextTick: 59994, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886100044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886116528027974; DSPS: 22159866; Offset: 1453885440262586080
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886136528836613; DSPS: 22815252; Offset: 1453885440262601262
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886156530365877; DSPS: 23470662; Offset: 1453885440262604647
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886160036, nextTick: 59991, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886160044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886176530804306; DSPS: 24126037; Offset: 1453885440262585312
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886196532048205; DSPS: 24781437; Offset: 1453885440262608508
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886216532455333; DSPS: 25436811; Offset: 1453885440262588390
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886220040, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886220043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886236533310221; DSPS: 26092199; Offset: 1453885440262588786
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886256533711411; DSPS: 26747572; Offset: 1453885440262593247
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,D/Finsky  ( 3684): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1558): Vacuum at: now=1453886262096 tag=VacuumService
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3684): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  966): GC_CONCURRENT freed 2218K, 49% free 30244K/58612K, paused 11ms+11ms, total 183ms
,D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1558): GC_EXPLICIT freed 1646K, 29% free 17844K/24832K, paused 2ms+3ms, total 24ms
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3684): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3684): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3684): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3684): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3684): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886276534159217; DSPS: 27402946; Offset: 1453885440262613807
,D/Finsky  ( 3684): [333] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3684): [1] 5.onFinished: Installation state replication succeeded.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886280034, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886280042, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886296535017229; DSPS: 28058335; Offset: 1453885440262586810
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886316535854148; DSPS: 28713722; Offset: 1453885440262599754
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886336536274714; DSPS: 29369096; Offset: 1453885440262593074
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886340043, nextTick: 59974, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886340052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886356536726477; DSPS: 30024471; Offset: 1453885440262587073
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886376537967250; DSPS: 30679871; Offset: 1453885440262607143
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x443e5cf0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1558): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1558): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1558): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1558): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1558): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/PlayEventLogger( 3684): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3684): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3684): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3684): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3684): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3684): Ignoring header User-Agent because its value was null.
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886396538812660; DSPS: 31335259; Offset: 1453885440262598061
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886400043, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886400056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886416540307757; DSPS: 31990668; Offset: 1453885440262597797
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886436540719000; DSPS: 32646041; Offset: 1453885440262612311
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886456546879824; DSPS: 33301603; Offset: 1453885440262608584
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886460044, nextTick: 59977, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886460058, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886476547311952; DSPS: 33956977; Offset: 1453885440262613466
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886496548211945; DSPS: 34612367; Offset: 1453885440262597932
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886516548630582; DSPS: 35267741; Offset: 1453885440262589323
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886520034, nextTick: 59973, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886520053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886536550184221; DSPS: 35923152; Offset: 1453885440262586565
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886556551465047; DSPS: 36578554; Offset: 1453885440262585653
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886576552729466; DSPS: 37233955; Offset: 1453885440262598851
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886580042, nextTick: 59965, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886580060, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886596554060292; DSPS: 37889359; Offset: 1453885440262586904
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886616555287159; DSPS: 38544759; Offset: 1453885440262593068
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886636556602672; DSPS: 39200162; Offset: 1453885440262596325
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886640040, nextTick: 59969, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886640053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886656557538706; DSPS: 39855553; Offset: 1453885440262586314
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886676565578699; DSPS: 40511176; Offset: 1453885440262600184
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x4318a698: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1558): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1558): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1558): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1558): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1558): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3684): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3684): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3684): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3684): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3684): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3684): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3684): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886696566928170; DSPS: 41166580; Offset: 1453885440262606881
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886700033, nextTick: 59991, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886700036, nextTick: 59995, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886716567827589; DSPS: 41821970; Offset: 1453885440262590773
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886736569055915; DSPS: 42477370; Offset: 1453885440262598396
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1453886756570881950; DSPS: 43132790; Offset: 1453885440262593376
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886760043, nextTick: 59973, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1453886760052, nextTick: 59979, mDrawingTime: 1
,TIME-OUT KILL (timeout was 1200000ms)
```
