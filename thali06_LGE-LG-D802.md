#### Test 5667282762e056f_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1926): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1926): launchTask
W/dalvikvm( 1926): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/ChimeraCfgMgr( 1926): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1926): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1926): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VcUxZGA4jU-tJGlh2_0bNSjYg1alFPQChY9t42M3JTPv_4zTDnfPTcmTD5xfna3sKxpN37h4xzfd7yvxGfqtJMkQfekgsICMMgCKjYlp5GVp3hXjpIpButaYOy-oGkLPYyWHhDv9FdnsZwXjKSkfhj7edHIT1zCgRurNqOJJmMBkfAfRcOWevkKinogHnOiGcj4ptv
D/ChimeraCfgMgr( 1926): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/GoogleURLConnFactory( 1926): Using platform SSLCertificateSocketFactory
D/Vision  ( 1926): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1926): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1926): No vision deps
W/BaseAppContext( 1926): Using Auth Proxy for data requests.
W/BaseAppContext( 1926): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1926): CP2 sync disabled
I/dalvikvm( 1926): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1926): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1926): VFY: replacing opcode 0x6e at 0x000e
W/GAV2    ( 4025): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  961): Killing 3336:com.google.android.music:main/u0a107 (adj 15): empty #17
F/ActivityManager(  961): Service ServiceRecord{432d6f98 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43276888 3336:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  961): Service ServiceRecord{430ab908 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43276888 3336:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43183740 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2}
E/DataScheduler( 1926): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
W/BaseAppContext( 1926): Using Auth Proxy for data requests.
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1926): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1926): fetch service done; releasing wakelock
I/ConfigFetchService( 1926): stopping self
W/BaseAppContext( 1926): Using Auth Proxy for data requests.
W/BaseAppContext( 1926): Using Auth Proxy for data requests.
W/BaseAppContext( 1926): Using Auth Proxy for data requests.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4073): 
D/AndroidRuntime( 4073): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4073): CheckJNI is OFF
D/dalvikvm( 4073): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4073): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4073): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4073): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4073): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4073): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/dalvikvm( 1926): GC_CONCURRENT freed 1555K, 26% free 18421K/24832K, paused 3ms+4ms, total 29ms
I/Icing   ( 1926): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/ChimeraCfgMgr( 1926): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1926): Module APK com.google.android.play.games already loaded
D/Icing   ( 1926): Loaded CLD2 Version V2.0 - 20141016
E/memtrack( 4073): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4073): failed to load memtrack module: -2
I/Icing   ( 1926): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4073): Calling main entry com.android.commands.am.Am
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4073
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43183740 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (328 us)
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  961): GC_FOR_ALLOC freed 24163K, 54% free 28168K/60708K, paused 119ms, total 119ms
D/ActivityManager(  961): resumeTopActivityLocked: Pausing null
V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  961): setFocusedStack: mFocusedStack=ActivityStack{43183740 stackId=1, 2 tasks}
D/AndroidRuntime( 4073): Shutting down VM
D/UsbSettingsControl( 2575): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2575): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4073): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 2ms
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  961): startService SlideAside
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43183740 stackId=1, 2 tasks}
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  961): resumeTopActivityLocked: Restarting ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3519): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/SlideAside( 3519): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  961): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4103 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/SlideAside( 3519): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HyLog   ( 4103): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4103): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4103): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
V/WebViewChromium( 4103): Binding Chromium to the background looper Looper (main, tid 1) {42868150}
I/chromium( 4103): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4103): Initializing chromium process, renderers=0
W/chromium( 4103): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4103): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4103): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4103): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4103): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4103): Remote Branch: 
I/Adreno-EGL( 4103): Local Patches: 
I/Adreno-EGL( 4103): Reconstruct Branch: 
I/dalvikvm( 4103): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4103): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4103): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4103): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4103): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4103): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4103): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4103): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4103): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4103): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4103): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4103): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4103): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4103): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4103): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4103): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4103): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4103): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4103): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4103): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4103): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4103): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4103): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4103): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4103): Enabling debug mode 0
W/AwContents( 4103): nativeOnDraw failed; clearing to background color.
W/AwContents( 4103): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  961): IME STATUS OFF
I/ActivityManager(  961): Displayed com.test.thalitest/.MainActivity: +427ms
I/ActivityManager( 4103): Timeline: Activity_idle id: android.os.BinderProxy@42869830 time:109084
D/JsMessageQueue( 4103): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4103): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4286d910
D/dalvikvm( 4103): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4286d910
D/jxcore_app_log( 4103): JniHelper::setJavaVM(0x4172b838), pthread_self() = 1631574000
I/chromium( 4103): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3} time:109423
D/ActivityManager(  961): no-history finish of ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  961): Finishing activity token=Token{431e0990 ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2575): [AUTORUN] onStop()
I/chromium( 4103): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4103): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4103): GC_CONCURRENT freed 2645K, 12% free 22007K/24832K, paused 3ms+4ms, total 55ms
D/dalvikvm( 4103): WAIT_FOR_CONCURRENT_GC blocked 47ms
,D/dalvikvm( 4103): WAIT_FOR_CONCURRENT_GC blocked 41ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 393K, 11% free 22314K/24832K, paused 28ms, total 28ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 104K, 11% free 22321K/24832K, paused 43ms, total 43ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 24.032MB for 63974-byte allocation
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 126K, 11% free 22341K/24896K, paused 40ms, total 41ms
I/dalvikvm-heap( 4103): Grow heap (frag case) to 24.083MB for 95956-byte allocation
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 179K, 11% free 22376K/24992K, paused 37ms, total 37ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 24.162MB for 143930-byte allocation
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 254K, 11% free 22423K/25136K, paused 32ms, total 33ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 24.277MB for 215890-byte allocation
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 366K, 12% free 22497K/25348K, paused 33ms, total 33ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 24.452MB for 323830-byte allocation
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 566K, 12% free 22617K/25668K, paused 33ms, total 33ms
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 862K, 12% free 22794K/25668K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 25.127MB for 728606-byte allocation
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 1279K, 13% free 23049K/26380K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 25.725MB for 1092904-byte allocation
,D/dalvikvm( 4103): GC_CONCURRENT freed 1906K, 15% free 23453K/27448K, paused 3ms+2ms, total 38ms
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 154K, 15% free 23356K/27448K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 26.545MB for 1639352-byte allocation
,D/dalvikvm( 4103): GC_CONCURRENT freed 1819K, 18% free 23960K/29052K, paused 2ms+2ms, total 32ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 1065K, 18% free 23944K/29052K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 27.902MB for 2459024-byte allocation
,D/dalvikvm( 4103): GC_CONCURRENT freed 354K, 17% free 26301K/31456K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 4152K, 21% free 24977K/31456K, paused 31ms, total 33ms
,I/dalvikvm-heap( 4103): Grow heap (frag case) to 30.083MB for 3688532-byte allocation
,D/dalvikvm( 4103): GC_CONCURRENT freed 473K, 20% free 28298K/35060K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 4103): GC_FOR_ALLOC freed 4196K, 26% free 26082K/35060K, paused 27ms, total 28ms
,W/jxcore-log( 4103): Initializing JXcore engine
,W/jxcore-log( 4103): JXcore engine is ready
,D/dalvikvm( 4103): GC_CONCURRENT freed 414K, 18% free 28874K/35060K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 4103): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4103): WAIT_FOR_CONCURRENT_GC blocked 14ms
,W/jxcore-log( 4103): Starting JXcore engine
,W/jxcore-log( 4103): Platform android
W/jxcore-log( 4103): 
,W/jxcore-log( 4103): Process ARCH arm
W/jxcore-log( 4103): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4103): JXcore Cordova bridge is ready!
I/jxcore-log( 4103): 
,W/jxcore-log( 4103): JXcore engine is started
,E/jxcore  ( 4103): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4103): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4103): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  961): Finishing activity token=Token{44045dc0 ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
,V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43183740 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  961): moveHomeStack:
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c84108 stackId=0, 1 tasks}
,V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  961): resumeTopActivityLocked: Resumed ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c84108 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1817): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:56:53
,D/UpdateThreadPoolManager( 1817): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1817): 2 : quick cover state : opened : 0
D/WeatherService( 1817): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1817): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1817): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1817): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1817): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1817): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:56:53
,I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/WeatherService( 1817): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1817): 2 : quick cover state : opened : 0
,W/IInputConnectionWrapper( 4103): showStatusIcon on inactive InputConnection
I/InputMethodManagerService(  961): IME STATUS OFF
,D/Weather.Utils( 1817): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1817): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1817): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1817): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1817): 2 : This is isUpdating : false
D/WeatherService( 1817): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1817): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1817): 2 : Map key string is -2
,D/lim     ( 1817): 2 : time = 18:56
I/WeatherReflect( 1817): Model Name : LG-D802
,D/WeatherTheme( 1817): 2 : Different view - status_min_formatted : 55 != 56
D/WeatherTheme( 1817): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1817): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1817): 2 : Fixed theme : optimus
,D/WeatherTheme( 1817): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1817): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1817): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1817): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1141): GC_FOR_ALLOC freed 5939K, 12% free 69230K/78208K, paused 24ms, total 24ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1488): GC_CONCURRENT freed 5302K, 9% free 61078K/66624K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@42863fb0 time:112458
,V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2575): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2575): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2575): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2575): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{430d1620 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c84108 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1}
,D/dalvikvm(  961): GC_CONCURRENT freed 1239K, 52% free 29733K/60708K, paused 3ms+4ms, total 74ms
,I/GAV2    ( 4025): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1} time:112550
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  961): Killing 2134:android.process.media/u0a23 (adj 15): empty #17
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4103): call to OpenGL ES API with no current context (logged once per thread)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c84108 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{43b1f5b0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c84108 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1}
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.565002 Y: -0.340805 Z: 9.804642 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565002 .y:-0.340805 .z:9.804642
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.564560 Y: -0.348785 Z: 9.794525 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.564560 .y:-0.348785 .z:9.794525
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1551): onDestroy
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1488): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1817): 2 : TimeTick Intent has been received, Time(hour:min:sec) 18:57:0
,D/WeatherService( 1817): 2 : TimeTick Intent And Screen On
D/WeatherService( 1817): 2 : SDK version : 19
,D/WeatherQuickCover( 1817): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1817): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1817): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1817): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1817): 2 : This is isUpdating : false
D/WeatherService( 1817): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1817): 2 : buildUpdate, appWidgetId: 1
D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831020029, nextTick: 60001, mDrawingTime: 2
,D/WeatherReflect( 1817): 2 : Map key string is -2
,D/lim     ( 1817): 2 : time = 18:57
,I/WeatherReflect( 1817): Model Name : LG-D802
D/WeatherTheme( 1817): 2 : Different view - status_min_formatted : 56 != 57
,D/WeatherTheme( 1817): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1817): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1817): 2 : Fixed theme : optimus
D/WeatherTheme( 1817): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1817): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 18:57:0
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831020062, nextTick: 59953, mDrawingTime: 6
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  961): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 3709): [333] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3709): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.583389 Y: -0.340332 Z: 9.821686 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.583389 .y:-0.340332 .z:9.821686
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.584076 Y: -0.340225 Z: 9.827164 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.584076 .y:-0.340225 .z:9.827164
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/dalvikvm(  961): Jit: resizing JitTable from 8192 to 16384
,I/PowerManagerService(  961): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  961): [updateScreenState] screen on = false
,D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  961): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8174 usec
D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  961): hal_acquire_resources
,I/qcom_sensors_hal(  961): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  961): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  961): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  961): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  961): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  961): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  961): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.561356 Y: -0.332703 Z: 9.835205 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.561356 .y:-0.332703 .z:9.835205
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  961): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.560638 Y: -0.337509 Z: 9.838165 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560638 .y:-0.337509 .z:9.838165
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Sensors (  320): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  961): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  961): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  961): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  961): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  961): proximitySensorChanged  positive = true
I/KnockOnPowerController(  961): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.562424 Y: -0.337082 Z: 9.854660 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.562424 .y:-0.337082 .z:9.854660
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.561478 Y: -0.343338 Z: 9.851578 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.561478 .y:-0.343338 .z:9.851578
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.560013 Y: -0.331131 Z: 9.831314 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560013 .y:-0.331131 .z:9.831314
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.559479 Y: -0.319473 Z: 9.820450 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.559479 .y:-0.319473 .z:9.820450
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  961): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4322a940)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  961): **** SHOWN CALLED ****
,I/WindowManager(  961): No lock screen! windowToken=null
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.558807 Y: -0.331070 Z: 9.826538 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.558807 .y:-0.331070 .z:9.826538
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb76cf450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,E/SlideAside( 3519): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiStateMachine(  961): handleScreenStateChanged: true
,D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131127
D/WifiStateMachine(  961): processMsg: InitialState
,D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
,D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): setSuspendOptimizations: 4 false
,D/WifiStateMachine(  961): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiServiceExtension(  961): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  961): stopMonitoring
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 961
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4332f518 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
D/WeatherAncestor( 1817): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:57:20
I/SlideAside( 3519): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1817): 2 : This is isUpdating : false
,D/WeatherAncestor( 1817): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:57:20
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1817): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1817): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.566162 Y: -0.331345 Z: 9.850067 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.566162 .y:-0.331345 .z:9.850067
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
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
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.562668 Y: -0.335281 Z: 9.836166 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.562668 .y:-0.335281 .z:9.836166
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
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
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1157): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  961): Excessive delay in blankDisplay() while turning screen off: 421ms
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1141): GC_FOR_ALLOC freed 5616K, 13% free 68783K/78208K, paused 33ms, total 34ms
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831041032, nextTick: 38999, mDrawingTime: 1
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831041061, nextTick: 38969, mDrawingTime: 3
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,D/WeatherService( 1817): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:57:21
,D/WeatherService( 1817): 2 : ACTION screen on
,D/WeatherService( 1817): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,D/WeatherService( 1817): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:57:21
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1141): notifyScreenOffLocked
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qcom_sensors_hal(  961): hal_acquire_resources
D/qcom_sensors_hal(  961): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  961): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  961): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  961): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  961): hal_smgr_report_delete: Rcvd success response from request
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  961): Vibrator off
,I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  961): handleScreenStateChanged: false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): setSuspendOptimizations: 4 true
D/WifiStateMachine(  961): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  961): handleMessage: X
,D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
D/WifiController(  961): battery changed pluggedType: 2
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{42bd8bf0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  961): CMD_SCREEN_OFF 
,D/WifiController(  961): shouldWifiStayAwake TRUE
E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 961
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1157): clear
D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/WeatherService( 1817): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:57:21
D/WeatherService( 1817): 2 : ACTION screen off
,D/WeatherService( 1817): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:57:21
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/NfcService( 1475): NFC-C OFF
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  320): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831053785517861; DSPS: 5116011; Offset: 1453830897657252481
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831073786817750; DSPS: 5771413; Offset: 1453830897657270631
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831080045, nextTick: 59984, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831080055, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831093788155190; DSPS: 6426817; Offset: 1453830897657265298
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831113789470807; DSPS: 7082220; Offset: 1453830897657268659
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831133790365018; DSPS: 7737609; Offset: 1453830897657277860
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831140038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831140044, nextTick: 59983, mDrawingTime: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831153791655271; DSPS: 8393012; Offset: 1453830897657255857
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831173792120055; DSPS: 9048387; Offset: 1453830897657262878
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831193793041037; DSPS: 9703777; Offset: 1453830897657268332
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831200033, nextTick: 59998, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831200043, nextTick: 59985, mDrawingTime: 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831213794960248; DSPS: 10359200; Offset: 1453830897657264936
,I/LocationManagerService(  961): remove 4308ae08
,D/LocationManagerService(  961): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831233796286698; DSPS: 11014603; Offset: 1453830897657279130
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=null, action=2
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3709): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3709): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3709): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3709): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3709): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 3709): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3709): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831253797165077; DSPS: 11669992; Offset: 1453830897657272499
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831260038, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831260043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831273798461215; DSPS: 12325395; Offset: 1453830897657256382
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831293799775582; DSPS: 12980798; Offset: 1453830897657258493
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,D/dalvikvm( 2627): GC_CONCURRENT freed 7740K, 33% free 16856K/24832K, paused 3ms+1ms, total 38ms
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831313801120002; DSPS: 13636202; Offset: 1453830897657260139
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831320034, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831320044, nextTick: 59986, mDrawingTime: 1
,D/dalvikvm( 2627): GC_CONCURRENT freed 1623K, 31% free 17280K/24832K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 1556K, 31% free 17235K/24832K, paused 21ms, total 21ms
,I/Mlt MonitorService( 2627): parseLastkmsg to dump
,D/dalvikvm( 2627): GC_CONCURRENT freed 1259K, 28% free 17918K/24832K, paused 2ms+1ms, total 40ms
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831333801987963; DSPS: 14291590; Offset: 1453830897657273608
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831353803837279; DSPS: 14947011; Offset: 1453830897657261352
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831373805139563; DSPS: 15602414; Offset: 1453830897657251380
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831380027, nextTick: 59999, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831380050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831393806009918; DSPS: 16257802; Offset: 1453830897657267243
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831413806853298; DSPS: 16913190; Offset: 1453830897657256131
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831433807715842; DSPS: 17568578; Offset: 1453830897657264182
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831440044, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831440057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831453808151720; DSPS: 18223952; Offset: 1453830897657272814
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831473809019941; DSPS: 18879341; Offset: 1453830897657256025
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831493809905871; DSPS: 19534730; Offset: 1453830897657256946
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831500045, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831500055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831513811199249; DSPS: 20190132; Offset: 1453830897657268585
,I/ActivityManager(  961): Killing 3184:com.android.mms/u0a35 (adj 15): empty #17
,D/CountryDetector(  961): No listener is left
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c84108 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831533811626323; DSPS: 20845506; Offset: 1453830897657268413
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x433322e0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3709): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3709): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3709): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3709): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3709): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3709): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831553815152671; DSPS: 21500982; Offset: 1453830897657254722
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831560049, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831560056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831573815584434; DSPS: 22156356; Offset: 1453830897657259239
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831593816434739; DSPS: 22811744; Offset: 1453830897657255052
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831613817290460; DSPS: 23467132; Offset: 1453830897657256281
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831620035, nextTick: 59983, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831620043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831633818643838; DSPS: 24122536; Offset: 1453830897657266885
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831653819078674; DSPS: 24777910; Offset: 1453830897657274475
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831673820152937; DSPS: 25433305; Offset: 1453830897657280623
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831680027, nextTick: 59994, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831680050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831693824091211; DSPS: 26088794; Offset: 1453830897657282129
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1926): Aggregate from 1453829694676 (log), 1453829694676 (data)
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831713825513547; DSPS: 26744201; Offset: 1453830897657270139
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831733826394529; DSPS: 27399590; Offset: 1453830897657266112
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831740046, nextTick: 59971, mDrawingTime: 7,
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831740055, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831753826828218; DSPS: 28054964; Offset: 1453830897657272554
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831773832169357; DSPS: 28710499; Offset: 1453830897657273117
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831793834112059; DSPS: 29365923; Offset: 1453830897657262694
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831800036, nextTick: 59991, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831800043, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831813835501061; DSPS: 30021328; Offset: 1453830897657278405
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831833836766678; DSPS: 30676730; Offset: 1453830897657262284
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x443c77f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3709): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3709): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3709): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3709): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3709): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/System  ( 3709): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831853838106358; DSPS: 31332134; Offset: 1453830897657259191
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831860059, nextTick: 59972, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831860059, nextTick: 59972, mDrawingTime: 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 270 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831873839652496; DSPS: 31987545; Offset: 1453830897657248932
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831893840927697; DSPS: 32642946; Offset: 1453830897657272912
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831913842232689; DSPS: 33298349; Offset: 1453830897657265648
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831920031, nextTick: 60000, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831920050, nextTick: 59983, mDrawingTime: 0
,W/ProcessCpuTracker(  961): Skipping unknown process pid 5136
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831933844190391; DSPS: 33953773; Offset: 1453830897657270225
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831953845867154; DSPS: 34609188; Offset: 1453830897657268522
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831973847176261; DSPS: 35264591; Offset: 1453830897657265373
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831980044, nextTick: 59983, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453831980050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453831993848487503; DSPS: 35919994; Offset: 1453830897657264359
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832013849799318; DSPS: 36575397; Offset: 1453830897657263918
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832033851100092; DSPS: 37230800; Offset: 1453830897657252436
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453832040050, nextTick: 59979, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453832040054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832053852387844; DSPS: 37886202; Offset: 1453830897657258450
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832073854326587; DSPS: 38541625; Offset: 1453830897657274586
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832093855607777; DSPS: 39197027; Offset: 1453830897657274037
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453832100044, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453832100063, nextTick: 59970, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832113856894645; DSPS: 39852430; Offset: 1453830897657248649
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832133858170835; DSPS: 40507831; Offset: 1453830897657273619
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3709): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3709): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3709): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3709): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3709): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3709): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3709): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  961): GC_CONCURRENT freed 2548K, 50% free 30439K/60704K, paused 8ms+10ms, total 155ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 149ms
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x432d8b80: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832153859593119; DSPS: 41163238; Offset: 1453830897657261577
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453832160055, nextTick: 59976, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453832160056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832173860931653; DSPS: 41818642; Offset: 1453830897657257337
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832193862187062; DSPS: 42474043; Offset: 1453830897657261525
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1453832213864129659; DSPS: 43129467; Offset: 1453830897657250997
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453832220058, nextTick: 59970, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453832220061, nextTick: 59971, mDrawingTime: 0
,TIME-OUT KILL (timeout was 1200000ms)
```
