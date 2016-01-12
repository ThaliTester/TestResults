#### Test 55613145ac448d4_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1941): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1941): launchTask
W/dalvikvm( 1941): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1941): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,V/ConfigFetchTask( 1941): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X4JeKYk-xnxHPNwVBaXdFWz47vDGqohwOVg3goF2o2O1Oy7p9fgue8lyvEc1_-qDKdQW5smeObEH5g0iPeV4QPoXv5tPY6p7_gJzT9PuYcmlv0hx2L-qbFHW-UA4MsJsKxfjLWVzspclCv0UDftN06-J6gn2K-G7Y04pqsxR-zVr0ZHmE-s-EwSJ-89QLM56qYQg6jGenDDnqAGtistWJZe9SxQVZj54Fwy24qUcj3tas5j_RLmbh4i1jJvfnDfhKTM5FKoSX7g9EAI1hmLgVX1ml9ppWY5oJ2hM9QxtWPDbX-Lz0
D/Vision  ( 1941): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1941): No vision deps
I/GoogleURLConnFactory( 1941): Using platform SSLCertificateSocketFactory
I/PeopleContactsSync( 1941): CP2 sync disabled
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/dalvikvm( 1941): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1941): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1941): VFY: replacing opcode 0x6e at 0x000e
W/GAV2    ( 4074): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  967): Killing 3356:com.google.android.music:main/u0a107 (adj 15): empty #17
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
F/ActivityManager(  967): Service ServiceRecord{43ba1bf0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43b24c60 3356:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  967): Service ServiceRecord{43b8ee58 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43b24c60 3356:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 1 tasks}
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
E/DataScheduler( 1941): isDataSchedulerEnabled():false
D/libc    (  269): _dns_getaddrinfo: iptype =0
D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1941): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchTask( 1941):   purging config for com.example.hello
I/ConfigFetchService( 1941): fetch service done; releasing wakelock
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConfigFetchService( 1941): stopping self
D/dalvikvm( 1941): GC_CONCURRENT freed 1583K, 27% free 18374K/24832K, paused 3ms+3ms, total 27ms
D/AndroidRuntime( 4116): 
D/AndroidRuntime( 4116): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4116): CheckJNI is OFF
D/dalvikvm( 4116): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4116): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4116): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4116): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4116): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4116): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1941): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
D/Icing   ( 1941): Loaded CLD2 Version V2.0 - 20141016
E/memtrack( 4116): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4116): failed to load memtrack module: -2
I/Icing   ( 1941): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4116): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4116
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/PermissionCache(  272): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (113 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/UsbSettingsControl( 2548): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2548): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4116): Shutting down VM
D/dalvikvm( 4116): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3545): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4139 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3545): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3545): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/dalvikvm(  273): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+2ms, total 19ms
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4139): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4139): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4139): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 18ms
D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
V/WebViewChromium( 4139): Binding Chromium to the background looper Looper (main, tid 1) {430a7090}
I/chromium( 4139): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4139): Initializing chromium process, renderers=0
W/chromium( 4139): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4139): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4139): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4139): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4139): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4139): Remote Branch: 
I/Adreno-EGL( 4139): Local Patches: 
I/Adreno-EGL( 4139): Reconstruct Branch: 
I/dalvikvm( 4139): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4139): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4139): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4139): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4139): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4139): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4139): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4139): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4139): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4139): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4139): VFY: replacing opcode 0x6f at 0x001a
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
W/dalvikvm( 4139): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4139): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4139): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4139): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4139): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4139): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4139): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4139): CordovaWebView is running on device made by: LGE
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/dalvikvm( 4139): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4139): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4139): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4139): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4139): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4139): Enabling debug mode 0
W/AwContents( 4139): nativeOnDraw failed; clearing to background color.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/InputMethodManagerService(  967): IME STATUS OFF
W/AwContents( 4139): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +381ms
I/ActivityManager( 4139): Timeline: Activity_idle id: android.os.BinderProxy@430a8860 time:105786
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/JsMessageQueue( 4139): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4139): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x430ac940
D/dalvikvm( 4139): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x430ac940
D/jxcore_app_log( 4139): JniHelper::setJavaVM(0x42053808), pthread_self() = 1632603208
D/JX-Cordova( 4139): jxcore cordova android initializing
I/dalvikvm(  967): Jit: resizing JitTable from 8192 to 16384
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3} time:106167
D/ActivityManager(  967): no-history finish of ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{43a63980 ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2548): [AUTORUN] onStop()
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4139): GC_CONCURRENT freed 2781K, 12% free 21872K/24832K, paused 2ms+1ms, total 42ms
,D/dalvikvm( 4139): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 131K, 12% free 21878K/24832K, paused 38ms, total 38ms
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 115K, 12% free 21908K/24832K, paused 35ms, total 35ms
,I/dalvikvm-heap( 4139): Grow heap (frag case) to 23.660MB for 95956-byte allocation
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 192K, 13% free 21929K/24928K, paused 37ms, total 38ms
,I/dalvikvm-heap( 4139): Grow heap (frag case) to 23.726MB for 143930-byte allocation
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
D/dalvikvm( 4139): GC_FOR_ALLOC freed 252K, 13% free 21976K/25072K, paused 40ms, total 40ms
I/dalvikvm-heap( 4139): Grow heap (frag case) to 23.840MB for 215890-byte allocation
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 366K, 13% free 22050K/25284K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4139): Grow heap (frag case) to 24.016MB for 323830-byte allocation
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 564K, 14% free 22171K/25604K, paused 37ms, total 38ms
,I/dalvikvm-heap( 4139): Grow heap (frag case) to 24.289MB for 485740-byte allocation
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 860K, 15% free 22347K/26080K, paused 22ms, total 23ms
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 1279K, 14% free 22602K/26080K, paused 34ms, total 34ms
,I/dalvikvm-heap( 4139): Grow heap (frag case) to 25.288MB for 1092904-byte allocation
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 272 plugged : true isCharging : false
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/dalvikvm( 4139): GC_CONCURRENT freed 1775K, 16% free 22988K/27148K, paused 1ms+2ms, total 31ms
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 271K, 16% free 22917K/27148K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4139): Grow heap (frag case) to 26.117MB for 1639352-byte allocation
,D/dalvikvm( 4139): GC_CONCURRENT freed 1985K, 19% free 23534K/28752K, paused 1ms+5ms, total 50ms
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 1024K, 19% free 23528K/28752K, paused 24ms, total 28ms
,I/dalvikvm-heap( 4139): Grow heap (frag case) to 27.496MB for 2459024-byte allocation
,D/dalvikvm( 4139): GC_CONCURRENT freed 232K, 17% free 25989K/31156K, paused 3ms+2ms, total 41ms
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 4341K, 22% free 24555K/31156K, paused 37ms, total 38ms
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/dalvikvm-heap( 4139): Grow heap (frag case) to 29.670MB for 3688532-byte allocation
D/WifiController(  967): battery changed pluggedType: 2
,D/dalvikvm( 4139): GC_CONCURRENT freed 331K, 20% free 28085K/34760K, paused 2ms+4ms, total 38ms
,D/dalvikvm( 4139): GC_FOR_ALLOC freed 3308K, 27% free 25500K/34760K, paused 24ms, total 24ms
,W/jxcore-log( 4139): Initializing JXcore engine
,W/jxcore-log( 4139): JXcore engine is ready
,D/dalvikvm( 4139): GC_CONCURRENT freed 369K, 20% free 28128K/34760K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 4139): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4139): Starting JXcore engine
,W/jxcore-log( 4139): Platform android
W/jxcore-log( 4139): 
,W/jxcore-log( 4139): Process ARCH arm
W/jxcore-log( 4139): 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/jxcore-log( 4139): JXcore Cordova bridge is ready!
I/jxcore-log( 4139): 
W/jxcore-log( 4139): JXcore engine is started
I/chromium( 4139): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4139): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4139): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4139): Toggling radios to true
I/jxcore-log( 4139): 
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4588e2c8:true
D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  967): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  967): Message: 1
,D/BluetoothManagerService(  967): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  967): New client listening to asynchronous messages
D/WifiService(  967): setWifiEnabled: true pid=4139, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
,D/WifiStateMachine(  967): setting operational mode to 1
D/WifiStateMachine(  967): handleMessage: E msg.what=131083
,D/WifiStateMachine(  967): processMsg: InitialState
,I/jxcore-log( 4139): Radios toggled
I/jxcore-log( 4139): 
,I/jxcore-log( 4139): My device name is: LGE-LG-D802
I/jxcore-log( 4139): 
D/WifiService(  967): disconnect pid=4139, uid=10304
D/WifiService(  967): reconnect pid=4139, uid=10304
,D/BluetoothAdapterService( 1224): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1124914120)( 1224): onCreate
E/WifiHW  (  967): Wifi MAC Address = 34:fc:ef:de:0a:e2
,E/WifiHW  (  967): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  967): ": cur_etheraddr=34:fc:ef:de:0a:e2
,D/SoftapController(  269): Softap fwReload - Ok
,D/BluetoothAdapterState( 1224): make
D/CommandListener(  269): Setting iface cfg
,D/CommandListener(  269): Trying to bring down wlan0
I/bluedroid( 1224): init ready=0
,D/bt-btif ( 1224): in initialized:0
D/bt-btif ( 1224): root, p->name:Bluedroid, child/value:0x606c13e8, bytes:160
,D/bt-btif ( 1224): p->used:0, type:0, p->flag:0
,I/BluetoothAdapterState( 1224): Entering OffState
,I/bte_conf( 1224): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@458939d0:true
,D/WifiMonitor(  967): WifiMonitorSingleton gotten
W/BT_PROF ( 1224): set profile trace flags 0x0
,D/BTIF_CORE( 1224): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 1224):  [BTUI] Load_abtddress
D/bt-btif ( 1224): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
D/bt-btif ( 1224): Got prior random BDA 34:FC:EF:9D:93:0B
I/bluedroid( 1224): get_profile_interface socket
I/bt-btif ( 1224): btif_get_adapter_property 2
,I/bt-btif ( 1224): btif_get_adapter_property 1
,D/BluetoothAdapterService(1124914120)( 1224): onBind
,D/BluetoothManagerService(  967): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  967): Message: 40
,D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 1224): config_hci_snoop_log
D/BluetoothManagerService(  967): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  967): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/lge_bdaddr_loader( 4192): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 4192): [BTUI] bluetooth_load_bdaddress
D/lge_bdaddr_loader( 4192): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
E/lge_bdaddr_loader( 4192): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
D/lge_bdaddr_loader( 4192): [BTUI] bdaddr_loader ::: END
D/WifiStateMachine(  967): setWifiState: enabling
,E/WifiStateMachine(  967): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  967): useWiFiOffloading() : false
E/WifiStateMachine(  967): CONFIG_LGE_WLAN_PATH : true
D/WifiStateMachine(  967): Supplicant start successful
D/WifiMonitor(  967): WifiMonitorSingleton gotten
,D/WifiMonitor(  967): startMonitoring(wlan0) with mConnected = false
,D/WifiMonitor(  967): connecting to supplicant
,V/WfdStateTracker( 1158): WfdStateTracker handleDirectStateChangedEvent: 1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/btif_config_util( 1224): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/WifiServiceExtension(  967): WIFI_STATE_CHANGED_ACTION [2]
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4196 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/dalvikvm( 1224): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,I/GKI_LINUX( 1224): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1224): btif task starting
D/bt-btif ( 1224): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1224): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1224): execute storage request event : 3
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:2 
,I/bt-btif ( 1224): HAL bt_hal_cbacks->adapter_properties_cb
D/wpa_supplicant( 4195): wpa_supplicant v2.1-devel-4.4.2
D/wpa_supplicant( 4195): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4195): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4195): Get randomness: len=20 entropy=1
,I/bt-btif ( 1224): execute storage request event : 3
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:1 
D/wpa_supplicant( 4195): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/bt-btif ( 1224): in, bd addr:, prop type:1, len:512
,D/wpa_supplicant( 4195): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4195): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4195): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4195): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4195): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4195): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4195): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4195): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4195): disable_scan_offload=1
D/wpa_supplicant( 4195): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4195): update_config=1
D/wpa_supplicant( 4195): device_name='g2_open_com'
D/wpa_supplicant( 4195): manufacturer='LGE'
D/wpa_supplicant( 4195): model_name='LG-D802'
D/wpa_supplicant( 4195): model_number='LG-D802'
D/wpa_supplicant( 4195): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4195): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4195): p2p_disabled=1
D/wpa_supplicant( 4195): p2p_no_group_iface=1
D/wpa_supplicant( 4195): Line: 15 - start of a new network block
D/wpa_supplicant( 4195): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4195): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4195): key_mgmt: 0x2
,D/wpa_supplicant( 4195): priority=1 (0x1)
,D/BluetoothAdapterService(1124914120)( 1224): Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1224): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,I/BluetoothAdapterState( 1224): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 1224): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  967): Message: 60
,D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  967): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothAdapterService(1124914120)( 1224): processStart()
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/LGBluetoothAPIService( 1158): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BluetoothAdapterService(1124914120)( 1224): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1224): make
D/BluetoothAdapterService( 1224): setAdapterService(): set to: null
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
D/LGBluetoothServiceAdapter( 1224): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
,D/LGBluetoothServiceAdapter( 1224): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 1224): StableState(): Entering Off State
,D/LGBluetoothSettingsDBObserver( 1224): [BTUI] register observer for LG device name DB
,E/BluetoothAdapterService( 1224): File transfer profiels supported!!
,W/BluetoothAdapterService( 1224): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
,D/BrcmHeadsetService( 1224): Received start request. Starting profile...
I/Brcm_BluetoothHeadsetServiceJni( 1224): classInitNative: succeeds
D/BluetoothHeadset(  967): Proxy object connected
D/HyLog   ( 4196): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4196): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4196): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HeadsetStateMachine( 1224): make
D/BluetoothHeadset( 1451): Proxy object connected
,D/BluetoothHeadset( 1451): Proxy object connected
,D/BluetoothHeadset( 1451): Proxy object connected
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
E/BluetoothAdapterService( 1224): File transfer profiels supported!!
W/BluetoothAdapterService( 1224): Starting service com.android.bluetooth.a2dp.A2dpService
D/wpa_supplicant( 4195): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4195): Priority group 1
D/wpa_supplicant( 4195):    id=0 ssid='NG700'
D/wpa_supplicant( 4195): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
D/wpa_supplicant( 4195): disable_scan_offload=1
D/wpa_supplicant( 4195): Priority group 1
D/wpa_supplicant( 4195):    id=0 ssid='NG700'
I/wpa_supplicant( 4195): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4195): nl80211: RFKILL status not available
D/wpa_supplicant( 4195): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4195): nl80211: TDLS supported
D/wpa_supplicant( 4195): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4195): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4195): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4195): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4195): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4195): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4195): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 0a 11
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
E/BluetoothAdapterService( 1224): File transfer profiels supported!!,
W/BluetoothAdapterService( 1224): Starting service com.android.bluetooth.hid.HidService
I/LGBluetoothHeadsetServiceJni( 1224): classInitNative: succeeds
E/BluetoothAdapterService( 1224): File transfer profiels supported!!
D/LGBluetoothHfpAdapter( 1224): Version 1.5
W/BluetoothAdapterService( 1224): Starting service com.android.bluetooth.hdp.HealthService
I/bluedroid( 1224): get_profile_interface handsfree
I/bt-btif ( 1224): btif_hf_get_interface
I/bt-btif ( 1224): init
D/bt-btif ( 1224): btif_enable_service: current services:0x40
V/AudioPolicyService(  275): getOutput()
V/AudioPolicyManagerBase(  275): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  275): getOutput() returns output 2
V/AudioSystem( 1224): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  275): registerClient() client 0xb8c643c0, pid 1224
V/AudioFlinger(  275): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  275): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  275): thread 0xb26dc008 type 0 TID 709 waking up
V/AudioFlinger(  275): thread 0xb2571008 type 0 TID 1002 waking up
E/BluetoothAdapterService( 1224): File transfer profiels supported!!
V/AudioFlinger(  275): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  275): processConfigEvents() remaining events 1
V/AudioFlinger(  275): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  275): processConfigEvents() remaining events 1
V/AudioFlinger(  275): PlaybackThread::audioConfigChanged_l, thread 0xb26dc008, event 0, param 0
V/AudioSystem(  275): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  275): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  967): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  967): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  275): PlaybackThread::audioConfigChanged_l, thread 0xb2571008, event 0, param 0
V/AudioSystem(  275): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  275): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  275): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem( 1224): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1224): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioSystem( 1451): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1451): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1603): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1603): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  967): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  967): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1224): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1224): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1603): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1603): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  275): acquireWakeLock_l() AudioOut_3 status 0
V/AudioSystem( 1224): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1224): sampleRate 0, channelMask 0x1, format 1
V/AudioTrack( 1224): streamType 8
V/AudioTrack( 1224): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1451): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1451): ioConfigChanged() opening already existing output! 3
V/AudioPolicyService(  275): checkPlayCondition().. streamType = 8
V/AudioPolicyManagerBase(  275): checkPlayCondition()... stream = 8, bResult = 0
V/AudioTrack( 1224): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
D/HeadsetStateMachine( 1224): Enter Disconnected: -2
W/BluetoothAdapterService( 1224): Starting service com.android.bluetooth.pan.PanServic,e
D/HeadsetPhoneState( 1224): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1224): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1224): [BTUI] change sampling rate to 8000 when device is disconnected
E/AudioSystem( 1224): AudioSystem::setParameters()...keyValue bt_samplerate=8000
V/AudioFlinger(  275): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1224
V/SRS_Proc(  275): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  275): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  275): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  275): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  275): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
D/BluetoothA2dp(  967): Proxy object connected
E/BluetoothAdapterService( 1224): File transfer profiels supported!!
W/BluetoothAdapterService( 1224): Starting service com.android.bluetooth.map.BluetoothMapService
D/PCSuite ( 4196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/A2dpService( 1224): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 1224): classInitNative: succeeds
D/A2dpStateMachine( 1224): make
E/BluetoothAdapterService( 1224): File transfer profiels supported!!
I/bluedroid( 1224): get_profile_interface a2dp
I/bt-btif ( 1224): btif_av_get_interface
I/bt-btif ( 1224): init
I/bt-btif ( 1224): ## A2DP START MEDIA TASK ##
I/GKI_LINUX( 1224): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1224): UIPC_Init
I/bt-btif ( 1224): ### uipc_main_init ###
D/bt-btif ( 1224): UIPC_Open : ch_id 0, p_cback 60b54b25
I/bt-btif ( 1224): SETUP CHANNEL SERVER 0
I/bt-btif ( 1224): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1224): created socket fd 69
,I/bt-btif ( 1224): ADD SERVER FD TO ACTIVE SET 69
I/bt-btif ( 1224): UIPC SEND WAKE UP
I/bt-btif ( 1224): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1224): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1224): btif_enable_service: current services:0x48
D/bt-btif ( 1224): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1224): ## ON A2DP IDLE ##
D/bt-btif ( 1224): UIPC_Close : ch_id 1
I/bt-btif ( 1224): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1224): classInitNative: succeeds
,I/LGBluetoothA2dpAdapter( 1224): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,I/ActivityManager(  967): Killing 3048:android.process.media/u0a23 (adj 15): empty #17
W/BluetoothAdapterService( 1224): Starting service com.android.bluetooth.gatt.GattService
D/A2dpStateMachine( 1224): Enter Disconnected: -2
I/BluetoothAVRCP1.3ServiceJni( 1224): classInitNativeAVRCP
V/Avrcp   ( 1224): make
I/bt-btif ( 1224): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  967): Bluetooth Adapter name changed to Thali Test's G2
D/BluetoothManagerService(  967): Stored Bluetooth name: Thali Test's G2
E/BluetoothAdapterService( 1224): File transfer profiels supported!!
W/BluetoothAdapterService( 1224): Starting service com.broadcom.bt.service.sap.SapService
D/LGBluetoothXmlHandler( 2548): dvice configuraion start
D/LGBluetoothXmlHandler( 2548): startDocument!
D/LGBluetoothXmlHandler( 2548): startElement - elet = Device
D/LGBluetoothXmlHandler( 2548): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2548): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2548): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2548): startElement - elet = OPP_DIRECTORY_BLUETOOTH
D/LGBluetoothXmlHandler( 2548): endDocument!
D/LGBluetoothAvrcpManager( 1224): [BTUI] initAvcrpManager
E/BluetoothAdapterService( 1224): File transfer profiels supported!!
,W/BluetoothAdapterService( 1224): Starting service com.broadcom.bt.service.ftp.FTPService
,D/dalvikvm( 1224): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
I/BluetoothAdapterState( 1224): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/LGBluetoothAvrcpManager( 1224): [BTUI] initPlayStatus() : isMusicActive = false
D/LGBluetoothAvrcpAdapter( 1224): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1224): initNativeAVRCP
I/bluedroid( 1224): get_profile_interface avrcp
I/bt-btif ( 1224): btif_rc_get_interface
I/bt-btif ( 1224): ## init ##
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
I/BluetoothHidServiceJni( 1224): classInitNative: succeeds
D/HidService( 1224): Received start request. Starting profile...
I/bluedroid( 1224): get_profile_interface hidhost
I/bt-btif ( 1224): btif_hh_get_interface
I/bt-btif ( 1224): init
D/bt-btif ( 1224): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
D/HeadsetStateMachine( 1224): Proxy object connected
I/BluetoothHealthServiceJni( 1224): classInitNative: succeeds
D/HealthService( 1224): Received start request. Starting profile...
I/bluedroid( 1224): get_profile_interface health
I/bt-btif ( 1224): btif_hl_get_interface
I/bt-btif ( 1224): init
D/bt-btif ( 1224): Process name (droid.bluetooth)
D/bt-btif ( 1224): btif_hl_soc_thread_init
D/bt-btif ( 1224): create_thread: entered
D/bt-btif ( 1224): create_thread: thread created successfully
I/LGBluetoothHealthServiceJni( 1224): classInitNative: succeeds
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
I/BluetoothPanServiceJni( 1224): classInitNative(L105): succeeds
D/bt-btif ( 1224): entered btif_hl_select_thread
D/bt-btif ( 1224): btif_hl_select_wakeup_init
D/bt-btif ( 1224): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1224): max_s=79 
D/bt-btif ( 1224): set curr_set = org_set 
D/BluetoothPan(  967): BluetoothPAN Proxy object connected
D/PanService( 1224): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1224): initializeNative(L110): pan
I/bluedroid( 1224): get_profile_interface pan
D/bt-btif ( 1224): stack_initialized = 0, btpan_cb.enabled:0
D/BluetoothTethering(  967): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/HeadsetPhoneState( 1224): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1224): Disconnected process message: 11
D/BluetoothAdapterService( 1224): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
I/LGBluetoothMapAdapter( 1224): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1224): BluetoothMapBinder()
D/BluetoothMapService( 1224): Received start request. Starting profile...
D/BluetoothMapService( 1224): start()
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
I/BtGatt.JNI( 1224): classInitNative(L685): classInitNative: Success!
D/BtGatt.DebugUtils( 1224): handleDebugAction() action=null
D/BtGatt.GattService( 1224): Received start request. Starting profile...
D/BtGatt.GattService( 1224): start()
I/bluedroid( 1224): get_profile_interface gatt
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.a,ndroid.bluetooth.btservice.AdapterService@430cd3c8
I/BluetoothSAPServiceJni( 1224): classInitNative(L170): succeeds
D/SapService( 1224): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1224): initializeNative(L175): sap
I/bluedroid( 1224): get_profile_interface sap
I/bt-btif ( 1224): btif_sc_get_interface
I/bt-btif ( 1224): init
D/bt-btif ( 1224): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1224): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1224): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1224): [BTUI] initSapManager
D/LgeBluetoothSimManager( 1451): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
V/BluetoothPbapReceiver( 1224): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1224): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1224): ***********state = 11
V/BluetoothFTPServiceJni( 1224): classInitNative
I/BluetoothFTPServiceJni( 1224): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
D/BluetoothFTPService( 1224): BluetoothFtpBinder()
D/**BluetoothFTPService( 1224): Received start request. Starting profile...
V/BluetoothFTPService( 1224): FTP-Server Service start
D/BluetoothPermissionRequest( 2548): onReceive
D/BluetoothFTPServiceJni( 1224): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1224): get_profile_interface ftp
I/bt-btif ( 1224): btif_fts_get_interface
I/bt-btif ( 1224): init
D/bt-btif ( 1224): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1224): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1224): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothManagerService(  967): Message: 20
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44f204b0:true
D/BluetoothAdapterService( 1224): Profile still not running:com.broadcom.bt.service.sap.SapService
D/LGBluetoothResetSettingReceiver( 2548): [BTUI] Loading JNI Library
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
E/BluetoothSettings_JNI( 2548): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/LGBluetoothResetSettingReceiver( 2548): return without doing reset settings.
D/BluetoothAdapterService( 1224): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1224): Profile still not running:com.broadcom.bt.service.sap.SapService
V/BluetoothMapService( 1224): Handler(): got msg=1
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1224): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1224): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1224): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1124914120)( 1224): Message: 1
D/BluetoothAdapterService(1124914120)( 1224): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1224): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1224): All profile services started.
D/BluetoothAdapterState( 1224): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1224): enable 1
I/bt-btif ( 1224): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1224): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/bt_hci_bdroid( 1224): init
I/bt_vendor( 1224): init
I/bt_vnd_conf( 1224): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1224): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1224): libbt-hci init returns 0
I/bt_hci_bdroid( 1224): bt_hc_worker_thread started
I/GKI_LINUX( 1224): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/ActivityManager(  967): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4240 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/HyLog   ( 4240): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4240): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4240): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AuthorizationBluetoothService( 1534): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  967): Killing 3787:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt_userial_vendor( 1224): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1224): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1224): device fd = 84 open
,D/bt_hwcfg( 1224): Chipset BCM4335A0
,D/bt_hwcfg( 1224): Target name = [BCM4335A0]
D/bt_hwcfg( 1224): Target name = [BCM4335]
I/bt_hwcfg( 1224): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1224): Applying 4335 AXI BRIDGE patch...
,I/bt_hwcfg( 1224): bt vendor lib: set UART baud 4000000
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4074): Thread[GAThread,5,main]: No campaign data found.
,D/wpa_supplicant( 4195): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4195): nl80211: driver param='use_multi_chan_concurrent=1'
,D/wpa_supplicant( 4195): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4195): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4195): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4195): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4195): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4195): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4195): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4195): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  967): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/bt_hwcfg( 1224): Releasing 4335 AXI BRIDGE lock
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/Tethering(  967): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbSettingsReceiver( 2548): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2548): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2548): [AUTORUN] sys.usb.state = boot,adb
,D/UsbSettingsReceiver( 2548): [AUTORUN] persist.sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2548): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/Config  ( 2548): getOperator() : OPEN
D/UsbSettingsControl( 2548): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2548): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 2548): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2548): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 2548): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsReceiver( 2548): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 2548): [AUTORUN] setTetherStatus() : status=false
D/wpa_supplicant( 4195): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4195): wlan0: RSN: flushing PMKID list in the driver
,D/wpa_supplicant( 4195): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4195): wlan0: Setting scan request: 0 sec 100000 usec
,D/wpa_supplicant( 4195): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4195): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4195): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4195): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4195): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4195): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4195): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4195): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4195): Using existing control interface directory.
I/wpa_supplicant( 4195): 0xb7e23cc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4195): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4195): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4195): lge_eap_carrier_var_init
D/wpa_supplicant( 4195): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4195): wlan0: Added interface wlan0
D/wpa_supplicant( 4195): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4195): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4195): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4195): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4195): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4195): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4195): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4195): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4195): update_config=1
D/wpa_supplicant( 4195): device_name='Thali Test's G2'
D/wpa_supplicant( 4195): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4195): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4195): persistent_reconnect=1
,D/wpa_supplicant( 4195): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
,D/wpa_supplicant( 4195): update_config=1
D/wpa_supplicant( 4195): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4195): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
D/wpa_supplicant( 4195): eapol_version=1
D/wpa_supplicant( 4195): ap_scan=1
,D/wpa_supplicant( 4195): fast_reauth=1
D/wpa_supplicant( 4195): p2p_disabled=0
D/wpa_supplicant( 4195): p2p_no_group_iface=0
I/wpa_supplicant( 4195): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4195): nl80211: RFKILL status not available
D/wpa_supplicant( 4195): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4195): nl80211: TDLS supported
D/wpa_supplicant( 4195): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4195): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4195): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4195): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4195): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4195): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e33c28
,D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4195): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4195): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4195): nl80211: Use separate P2P group interface
D/wpa_supplicant( 4195): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4195): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4195): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4195): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4195): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4195): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4195): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4195): nl80211: Added 802.11b mode based on 802.11g information
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4195): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4195): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4195): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4195): p2p0: State: DISCONNECTED -> INACTIVE
,I/bt_hwcfg( 1224): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1224): Settlement delay -- 100 ms
D/wpa_supplicant( 4195): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4195): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4195): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4195): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4195): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4195): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4195): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4195): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4195): Using existing control interface directory.
I/wpa_supplicant( 4195): 0xb7e33098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4195): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4195): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4195): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4195): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4195): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4195): [ITEC] USE NON-INET
I/wpa_supplicant( 4195): [ITEC] Open WIFLUS socket interface - DONE 24
I/wpa_supplicant( 4195): HY wiflus comm channel initialized
D/wpa_supplicant( 4195): P2P: Own listen channel: 1
I/wpa_supplicant( 4195): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4195): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4195): P2P: Add operating class 81
D/wpa_supplicant( 4195): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4195): P2P: Add operating class 115
D/wpa_supplicant( 4195): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 4195): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4195): p2p0: Added interface p2p0
D/wpa_supplicant( 4195): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4195): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4195): random: Got 16/20 bytes from /dev/random
D/wpa_supplicant( 4195): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( ,4195): random: Got 4/4 bytes from /dev/random
,D/wpa_supplicant( 4195): Get randomness: len=20 entropy=0
,D/wpa_supplicant( 4195): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4195): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: Starting AP scan for wildcard SSID
,D/wpa_supplicant( 4195): wlan0: nl80211: scan request
,D/wpa_supplicant( 4195): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiStateMachine(  967): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  967): invokeExitMethods: InitialState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  967): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131144
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): deferMessage: msg=131144
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131085
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): deferMessage: msg=131085
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131149
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): setSuspendOptimizations: 2 true
D/WifiStateMachine(  967): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131146
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131101,
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147457,
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): Supplicant connection established
D/WifiNative-wlan0(  967): doString: DRIVER MACADDR
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 4195): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER MACADDR'
D/wpa_supplicant( 4195): nl80211: Event message available
D/wpa_supplicant( 4195): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 4195): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  967):    returned Macaddr = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  967): MAC Addr from driver = 34:fc:ef:de:0a:e2
,D/WifiStateMachine(  967): setWifiState: enabled
D/WifiOffDelayIfNotUsed(  967): setPowerSaveActivated(false)
,D/WifiActivationWhileCharging(  967): unregister : we don't need to unregister
E/WifiStateMachine(  967): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  967): useWiFiOffloading() : false
E/WifiStateMachine(  967): CONFIG_LGE_WLAN_PATH : true
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiConfigStore(  967): Loading config and enabling all networks
,D/WifiNative-wlan0(  967): doString: LIST_NETWORKS
,D/WfdService( 1158): Waiting for WifiP2p enabling
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/WifiServiceExtension(  967): WIFI_STATE_CHANGED_ACTION [3]
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
,D/wpa_supplicant( 4195): wlan0: Control interface command 'LIST_NETWORKS'
,D/WifiNative-wlan0(  967):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  967): 0	NG700	any	
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 ssid
I/WifiServiceExtension(  967): batteryPsActivateMsgHandler : state:0 event:3
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 ssid'
,D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 bssid
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'bssid'
,D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 scan_ssid
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
,D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_key0
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
,D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'wep_key0'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_key1
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'wep_key1'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_key2
,D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'wep_key2'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
,D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4195): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 proto
,D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
,D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
,D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
,D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 group
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 group'
,D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='eap'
,D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'eap'
,D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='identity'
,D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'identity'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
,D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
,D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'password'
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 ca_cert
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'subject_match'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 engine'
,D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 engine_id
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
,D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'phase1'
D/WifiConfigStore(  967): ***WAPI : not WAPI
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4195): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4195): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,D/wpa_supplicant( 4195): CTRL_IFACE: Failed to get network variable 'private_key'
E/WifiConfigStore(  967): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/PCSuite ( 4196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/WifiNative-wlan0(  967): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'device_name'='g2_open_com'
,D/wpa_supplicant( 4195): device_name='g2_open_com'
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'manufacturer'='LGE'
,D/wpa_supplicant( 4195): manufacturer='LGE'
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'model_name'='LG-D802'
,D/wpa_supplicant( 4195): model_name='LG-D802'
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'model_number'='LG-D802'
D/wpa_supplicant( 4195): model_number='LG-D802'
,D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
,D/wpa_supplicant( 4195): serial_number='022678fb504e29b0'
,D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
,D/wpa_supplicant( 4195): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4195): config_methods='physical_display virtual_push_button keypad'
,D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET device_type 10-0050F204-5'
,D/wpa_supplicant( 4195): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,D/WifiNative-wlan0(  967):    returned true
,W/Settings( 3271): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  967): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  967): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=2,j=1
,D/LGDMClient( 2825): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=2
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=3
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  967): invokeEnterMethods: SupplicantStartedState
D/WifiNative-wlan0(  967): doBoolean: SCAN_INTERVAL 15
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4195): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 4195): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): invokeEnterMethods: DriverStartedStateExt
D/WifiStateMachine(  967): invokeEnterMethods: DriverStartedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
,D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/LGDMClient( 2825): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setDetailed state, old =IDLE and new state=DISCONNECTED
,D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
,D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-REMOVE 3
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4274 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): Attempting to reconnect to wifi network ..
D/WifiNative-wlan0(  967): doBoolean: RECONNECT
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 4195): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4195): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  967):    returned wpa_state=SCANNING
D/WifiNative-wlan0(  967): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  967): address=34:fc:ef:de:0a:e2
D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  967): handleScreenStateChanged: true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET ps 1'
,D/wpa_supplicant( 4195): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4195): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
,D/WifiP2pService(  967): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  967): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
D/CommandListener(  269): Setting iface cfg
D/WifiStateMachine(  967): invokeEnterMethods: ConnectModeState
D/CommandListener(  269): Trying to bring up p2p0
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131144
D/WifiMonitor(  967): WifiMonitorSingleton gotten
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiMonitor(  967): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131085
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132106
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  967): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4195): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
,E/wpa_supplicant( 4195): nWIFIDualbandAPConnection: 1
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132096
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  967): set CMD_DISCONNECT_RSSI_LVL : -100
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4195): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
E/wpa_supplicant( 4195): disconnect_rssi_lvl: -100
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  967): handleMessage: X
,V/WfdStateTracker( 1158): WfdStateTracker handleDirectStateChangedEvent: 2
,I/bt_hwcfg( 1224): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 1224): Setting local bd addr to 34:FC:EF:9D:93:0B
D/WifiP2pService(  967): P2pEnablingState
D/WifiP2pService(  967): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2p socket connection successful
D/WifiP2pService(  967): P2pEnabledState
D/WifiP2pService(  967): sending p2p connection changed broadcast
D/WifiNative-p2p0(  967): doBoolean: SET persistent_reconnect 1
D/WifiStateMachine(  967): handleMessage: E msg.what=143371
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4195): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4195): persistent_reconnect=1
D/wpa_supplicant( 4195): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: SET device_name Thali Test's G2
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4195): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4195): device_name='Thali Test's G2'
D/WifiNative-p2p0(  967):    returned true
D/WifiServiceExtension(  967): postfix byte check : 15
D/WifiNative-p2p0(  967): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4195): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4195): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4195): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4195): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4195): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4195): config_methods='virtual_push_button physical_display keypad'
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: P2P_SET conc_pref sta
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiP2pService(  967): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  967): before postfix = Thali Test's G2
D/WifiP2pService(  967): after postfix = Thali Test's G2
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4195): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4195): Single channel concurrency preference: sta
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doString: STATUS
D/wpa_supplicant( 4195): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-p2p0(  967):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  967): p2p_state=IDLE
D/WifiNative-p2p0(  967): wifi_display=1
D/WifiNative-p2p0(  967): ifname=p2p0
D/WifiNative-p2p0(  967): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  967): ifname=wlan0
D/WifiNative-p2p0(  967): address=34:fc:ef:de:0a:e2
D/WifiNative-p2p0(  967): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4195): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4195): P2P: Stopping find
D/wpa_supplicant( 4195): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4195): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4195): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: P2P_SERVICE_FLUSH
I/WfdStateTracker( 1158): handleP2pThisDeviceChanged
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4195): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doString: LIST_NETWORKS
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4195): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiNative-p2p0(  967):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  967): doBoolean: SAVE_CONFIG
D/HyLog   ( 4274): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4274): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4195): p2p0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 4195): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
D/HyLog   ( 4274): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiP2pService(  967): DeviceAddress: 36:fc:ef:de:0a:e2
I/bt_hwcfg( 1224): vendor lib fwcfg completed
I/bt-btif ( 1224): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/        ( 1224): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1224): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1224): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1224): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1224): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1224): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1224): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1224): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1224): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1224): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1224): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1224): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1224): BTE_InitTraceLevels -- TRC_SDP
I/        ( 1224): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1224): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1224): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1224): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1224): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1224): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
D/bt-btif ( 1224): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1224): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1224): bta_dm_sm_execute event:0x0
I/bt-btif ( 1224): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1224): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1224): bta_sys_sm_execute state:1, event:0x1
I/bt-btif ( 1224): bta_sys_hw_evt_enabled for 0
D/LGDMSGCM( 4274): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/wpa_supplicant( 4195): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4195): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiNative-p2p0(  967):    returned true
,E/WifiServiceExtension(  967): No p2p device connected
D/WifiP2pService(  967): sending p2p persistent groups changed broadcast
D/WifiP2pService(  967): InactiveState
D/WifiP2pService(  967): InactiveState{ when=-24ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-24ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): DefaultState{ when=-24ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=-24ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-24ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): DefaultState{ when=-24ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 4274): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/bt-btif ( 1224):  bta_sys_hw_btm_cback was called with parameter: 0
I/bt-btif ( 1224): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1224):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1224):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1224): ##################################
D/bt-btif ( 1224): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1224): ##################################
D/bt-btif ( 1224): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1224): BTM_SecRegister:p_cb_info->p_le_callback == 0x60ba94c5 
I/bt-smp  ( 1224): SMP_Register state=0
E/bt-btm  ( 1224): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60ba94c5 
D/bt-btif ( 1224): bta_gattc_register state 0
D/bt-btif ( 1224): bta_gattc_enable
I/bt-att  ( 1224): GATT_Register
D/bt-att  ( 1224): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1224): allocated gatt_if=3
D/bt-btif ( 1224): bta_dm_gattc_callback event = 0
D/bt-btif ( 1224): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1224): GATT_StartIf gatt_if=3
D/bt-att  ( 1224): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 1224): gatt_find_the_connected_bda found=0 found_idx=7
I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4292 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  967): Killing 3213:com.android.mms/u0a35 (adj 15): empty #17
,D/HyLog   ( 4292): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4292): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4292): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/LocationManagerService(  967): remove 439514f0
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
D/CountryDetector(  967): No listener is left
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/Wireless_Storage( 4292): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
V/[BNRBootReceiver]( 4043): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 4043): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,I/ActivityManager(  967): Killing 3271:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1534): onDestroy
,I/bt-btif ( 1224): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1224): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1224): bta_dm_sm_execute event:0x2
,D/bt-btif ( 1224): BTA is generating EIR
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 1224): Adding UUID=0x110C into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1224): nsc_mask: 0x6
D/bt-btif ( 1224): bta_av_co_audio_init
D/bt-btif ( 1224): bta_av_co_audio_init: 0
D/bt-btif ( 1224): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1224): getAccess buffer->st_uid:1000 buffer->st_gid:1028
,I/bt-btif ( 1224): FTP SERVER enabled with Root Path [/storage]
D/bt-btif ( 1224): Calling BTA_HhEnable
D/bt-btif ( 1224): bta_av_co_audio_init: 1
D/bt-btif ( 1224): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1224): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:4
I/bt-a2d  ( 1224): A2D_AddRecord uuid: 110a
I/bt-btif ( 1224): Adding UUID=0x110A into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
D/bt-btif ( 1224): rc_acp_handle:0 idx:1
D/bt-btif ( 1224): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1224): reg_audio: 0x1
D/bt-btif ( 1224): bta_ag_scb_alloc 1
I/bt-btif ( 1224): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:5
D/bt-btif ( 1224): bta_ag_add_record uuid: 1112
I/bt-btif ( 1224): Adding UUID=0x1112 into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00011400
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1224): bta_ag_add_record uuid: 111f
I/bt-btif ( 1224): Adding UUID=0x111F into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
D/bt-btif ( 1224): bta_fts_api_enable srm:1
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:7
I/bt-btif ( 1224): Adding UUID=0x1106 into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011440
D/bt-btif ( 1224): FTS:  SDP Registered (handle 0x00010006)
I/bt-btif ( 1224): bta_fts_ci_resume status:1
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:8
I/bt-btif ( 1224): Adding UUID=0x112D into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1224): bte_sap_evt: event=0
E/bt-btif ( 1224): bte_sap_evt: event=0
D/bt-btif ( 1224): bta_gattc_register state 2
I/bt-att  ( 1224): GATT_Register
D/bt-att  ( 1224): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 1224): allocated gatt_if=4
D/bt-btif ( 1224): bta_hh_gattc_callback event = 0
I/bt-att  ( 1224): GATT_StartIf gatt_if=4
D/bt-att  ( 1224): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 1224): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btif ( 1224): in add:1
D/bt-btif ( 1224): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1224): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1224): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1224): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1224): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1224): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1224): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1224): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1224): Remote device:b4:ce:f6:ab:a4:6a, size:18
,D/bt-btif ( 1224): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1224): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1224): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1224): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1224): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1224): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1224): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1224): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1224): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1224): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1224): Remote device:7c:f9:0e:34:8a:a0, size:18
,D/bt-btif ( 1224): Remote device:e0:db:10:14:e2:c0, size:18
I/bt-btif ( 1224): bta_dm_sm_execute event:0x9
D/bt-btif ( 1224): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1224): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1224): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1224): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1224): Remote device:38:94:96:b5:06:dc, size:18
I/bt-btif ( 1224): bta_dm_sm_execute event:0x9
,D/bt-btif ( 1224): Remote device:, size:128
E/bt-btif ( 1224): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
E/bt-btif ( 1224): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1224): out
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1224): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1224): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1224): in, bd addr:, prop type:16, len:4
E/bt-btif ( 1224): Unknow prop type:16
I/bt-btif ( 1224): btif_dm_get_adapter_property: type=0x10
D/bt-btif ( 1224): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:9 
,D/bt-btif ( 1224): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1224): btif_storage_get_adapter_property service_mask:0x120148
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1224): btif_storage_get_adapter_property property->type:3 devicemode 0
,I/bt-btif ( 1224): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothManagerService(  967): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  967): Stored Bluetooth name: Thali Test's G2
,E/BluetoothAdapterProperties( 1224): Property change not handled in Java land:16
,I/bt-btif ( 1224): btif_storage_load_bonded_devices: 2 bonded devices found
D/bt-btif ( 1224): in, bd addr:e0:db:10:14:e2:c0, prop type:1, len:249
D/bt-btif ( 1224): in, bd addr:e0:db:10:14:e2:c0, prop type:10, len:249
D/bt-btif ( 1224): in, bd addr:e0:db:10:14:e2:c0, prop type:4, len:4
D/bt-btif ( 1224): in, bd addr:e0:db:10:14:e2:c0, prop type:5, len:4
D/bt-btif ( 1224): in, bd addr:e0:db:10:14:e2:c0, prop type:3, len:512
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1224): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1224): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1224): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1224): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1224): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
D/bt-btif ( 1224): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512
,I/bt-btif ( 1224): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1224): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1224): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1224): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
I/bt-btif ( 1224): HC lib lpm enable=1 return 0
E/bt_hwcfg( 1224): hw_sco_config...
E/bt_hwcfg( 1224): SCO PCM configure {0, 4, 0, 0, 0}
I/bt-btif ( 1224): BTA_BrcmInit
E/bt-gki  ( 1224): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
,D/IOP_DB_BT( 1224): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 1224): db_open: db_open : handle 1623812652l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1224): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1224): db_query: result 1
I/        ( 1224): iop_db_open: iop_db_open status 0
D/bt-btif ( 1224): btsock initializing...
D/bt-btif ( 1224): in initialized:1
D/bt-btif ( 1224): ts[7].used:1
,D/bt-btif ( 1224): ts[6].used:0
D/bt-btif ( 1224): alloc_thread_slot ret:6
D/bt-btif ( 1224): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1224): h:6, thread id:1629055800
I/bt-btif ( 1224): BTA_JvEnable
D/bt-btif ( 1224): btsock successfully initialized
D/bt-btif ( 1224): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1224): unhandled event:0, slot id:0
,D/bt-btif ( 1224): jni_initialized = 1, btpan_cb.enabled:0
D/bt-btif ( 1224): Enabling PAN....
I/bt-btif ( 1224): HC lpm_result_cb 1
I/bt-btif ( 1224): local_role:3
D/bt-btif ( 1224): local_role:3
D/bt-btif ( 1224): btpan_role:0x3
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1224): Adding UUID=0x1116 into EIR
,D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1224): Adding UUID=0x1115 into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1224): Adding UUID=0x1116 into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1224): Removing UUID=0x1117 from EIR
D/bt-btif ( 1224): BTA is generating EIR
,I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1224): Adding UUID=0x1115 into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bte_conf( 1224): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1224): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
I/bt-btif ( 1224): bta_dm_sm_execute event:0x31
,D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1224): Adding UUID=0x1200 into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1224): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
I/bte_conf( 1224): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1224): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/bt-btif ( 1224): btif_dm_load_local_oob prop_oob = 3
I/bt-btif ( 1224): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1224): adapter_state_change_callback: Status is: 1
D/bt-btif ( 1224): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/BluetoothAdapterState( 1224): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1224): ScanMode =  20
,D/BluetoothAdapterProperties( 1224): State =  11
D/bt-btif ( 1224): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1224): btif_av_state_idle_handler devicemode: 0
D/BluetoothAdapterProperties( 1224): mDiscoverableTimeout =  120
I/bt-btif ( 1224): btif_set_adapter_property type: 7, len 4, 0x431364c8
D/bt-btif ( 1224): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 1224): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 1224): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
I/bt-btif ( 1224): File Transfer: Enable Complete
I/bt-btif ( 1224): HAL bt_fts_callbacks->operation_cmpl_cb
I/bt-btif ( 1224): set property scan mode : 1
I/bt-btif ( 1224): bta_dm_sm_execute event:0x3
I/bt-btif ( 1224): btif_in_storage_request_copy_cb
I/bt-btif ( 1224): btif_set_adapter_property type: 9, len 4, 0x43136520
I/bt-btif ( 1224): btif_in_storage_request_copy_cb
D/BluetoothFTPServiceJni( 1224): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothAdapterState( 1224): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 1224): Broadcasting updateAdapterState() to 1 receivers.
,I/BluetoothFTPService( 1224): onFtpServerEnabled: /storage
D/bt-btif ( 1224): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1224): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
D/bt-btif ( 1224): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
D/BluetoothManagerService(  967): Message: 60
D/bt-btif ( 1224): btif_hh_upstreams_evt--Loading added devices
D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  967): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/bt-btif ( 1224): Remote device:00:f4:6f:30:e0:6c, size:18
D/BluetoothPan(  967): onBluetoothStateChange(on) call bindService
D/bt-btif ( 1224): Remote device:f8:95:c7:87:3c:51, size:18
,D/bt-btif ( 1224): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1224): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1224): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1224): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1224): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1224): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1224): Remote device:b4:ce:f6:ab:a4:6a, size:18
,D/bt-btif ( 1224): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1224): Remote device:f8:cf:c5:d9:e5:61, size:18
V/BluetoothAdapterService( 1224): startPbapService
D/bt-btif ( 1224): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1224): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1224): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1224): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1224): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1224): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1224): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1224): Remote device:f8:95:c7:87:85:54, size:18
D/BluetoothHeadset( 1451): onBluetoothStateChange: up=true
D/bt-btif ( 1224): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1224): Remote device:e0:db:10:14:e2:c0, size:18
D/BluetoothHeadset( 1451): onBluetoothStateChange: up=true
D/bt-btif ( 1224): Remote device:34:fc:ef:11:b1:66, size:18
,D/bt-btif ( 1224): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1224): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1224): Remote device:58:2a:f7:ed:96:be, size:18
D/BluetoothHeadset( 1451): onBluetoothStateChange: up=true
D/BluetoothA2dp(  967): onBluetoothStateChange: up=true
D/BluetoothHeadset(  967): onBluetoothStateChange: up=true
D/bt-btif ( 1224): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1224): Remote device:, size:18
E/bt-btif ( 1224): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1224): BTA_PAN_ENABLE_EVT
D/BluetoothManagerService(  967): Bluetooth State Change Intent: 11 -> 12
D/bt-btif ( 1224): bta_pan_role:0x5
,D/BluetoothPanServiceJni( 1224): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/bt-btif ( 1224): execute storage request event : 2
I/bt-btif ( 1224): type: 7, len 4, 0x60aff0d2
D/bt-btif ( 1224): in, bd addr:, prop type:7, len:4
,I/bt-btif ( 1224): HAL bt_hal_cbacks->adapter_properties_cb
,D/LGBluetoothAPIService( 1158): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1158): Message: 1
D/LGBluetoothAPIService( 1158): MESSAGE_BOOT_COMPLETED
D/BluetoothManagerService(  967): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  967): Message: 40
D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/bt-btif ( 1224): execute storage request event : 2
I/bt-btif ( 1224): type: 9, len 4, 0x60aff086
D/bt-btif ( 1224): in, bd addr:, prop type:9, len:4
I/bt-btif ( 1224): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothMapService( 1224): onReceive
D/BluetoothMapService( 1224): STATE_ON
V/BluetoothMapService( 1224): Handler(): got msg=1
,D/BluetoothMapService( 1224): Map Service startRfcommSocketListener
I/BluetoothAdapterState( 1224): Entering On State
,D/BluetoothMapService( 1224): Map Service initSocket
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
D/LGBluetoothServiceAdapter( 1224): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1224): [BTUI]         global_name: Thali Test's G2
D/LGBluetoothServiceAdapter( 1224): [BTUI]         local_name: Thali Test's G2
I/LGBluetoothAPIService( 1158): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService(1124914120)( 1224): Get Bonded Devices being called
D/BluetoothAdapterService(1124914120)( 1224): Quiet mode Enabled = false
D/BluetoothAdapterService(1124914120)( 1224): Initiate auto connection on BT on...
D/BluetoothAdapterService( 1224): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/bt_h4   ( 1224): vendor lib postload completed
I/bt-btif ( 1224): HC postload_cb 0
D/BluetoothAdapterService( 1224): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@430cd3c8
W/BluetoothAdapter( 1224): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothPbapService( 1224): Pbap Service onCreate
V/BluetoothPbapService( 1224): Starting PBAP service
E/BluetoothServiceJni( 1224): SOCK FLAG = 1 ***********************
D/bt-btif ( 1224): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1224): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1224): BTA_JvCreateRecordByUser
D/bt-btif ( 1224): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1224): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1224): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1224): Adding UUID=0x1132 into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000484 04071440
D/bt-btif ( 1224): MAPSS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1224): BTA_JvRfcommStartServer
D/bt-btif ( 1224): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1224): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
D/LGBluetoothServiceAdapter( 1224): [BTUI] createSocketChannel FD=90 mFd=0
V/BluetoothMapService( 1224): Succeed to create listening socket 
D/BluetoothMapService( 1224): Accepting socket connection...
D/LGBluetoothPbapAdapter( 1224): [BTUI] getInstance : create
V/BluetoothPbapService( 1224): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 1224): state: 12
,D/LGBluetoothAPIServer( 1224): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1224): [BTUI] onBind()
,V/BluetoothPbapService( 1224): Handler(): got msg=1
V/BluetoothPbapService( 1224): Pbap Service startRfcommSocketListener
,D/LGBluetoothAPIService( 1158): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1158): Message: 100
D/LGBluetoothAPIService( 1158): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,V/BluetoothPbapService( 1224): Pbap Service initSocket
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapReceiver( 1224): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1224): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1224): ***********state = 12
,W/ContextImpl( 2548): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
W/BluetoothAdapter( 1224): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1224): SOCK FLAG = 1 ***********************
D/bt-btif ( 1224): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
D/bt-btif ( 1224): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1224): BTA_JvCreateRecordByUser
D/bt-btif ( 1224): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1224): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1224): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1224): Adding UUID=0x112F into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1224): PBS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1224): BTA_JvRfcommStartServer
D/bt-btif ( 1224): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1224): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1224): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothPbapService( 1224): Succeed to create listening socket 
V/BluetoothPbapService( 1224): Accepting socket connection...
D/LocalBluetoothProfileManager( 2548): Adding local A2DP profile
,D/BluetoothManagerService(  967): Message: 30
,D/LocalBluetoothProfileManager( 2548): Adding local HEADSET profile
,D/BluetoothManagerService(  967): Message: 30
W/ContextImpl( 2548): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
,D/BluetoothManagerService(  967): Message: 30
,D/BluetoothManagerService(  967): Message: 30
W/ContextImpl( 2548): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
W/ContextImpl( 2548): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
,D/LocalBluetoothProfileManager( 2548): Adding local MAP profile
D/BluetoothMap( 2548): Create BluetoothMap proxy object
,D/BluetoothManagerService(  967): Message: 30
W/ContextImpl( 2548): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
W/ContextImpl( 2548): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
,D/dalvikvm(  967): GC_EXPLICIT freed 23138K, 49% free 29570K/57676K, paused 3ms+7ms, total 124ms
,D/BluetoothManagerService(  967): Message: 30
,V/BluetoothPbapService( 1224): Pbap Service onBind
,D/LocalBluetoothProfileManager( 2548): LocalBluetoothProfileManager construction complete
,D/LGBluetoothUserBindClient( 2548): [BTUI] initUserBindClient
W/ContextImpl( 2548): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
,W/ContextImpl( 2548): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 2548): finishStartingService: stopping service
D/BluetoothA2dp( 2548): Proxy object connected
D/A2dpProfile( 2548): Bluetooth service connected
D/BluetoothHeadset( 2548): Proxy object connected
D/HeadsetProfile( 2548): Bluetooth service connected
D/BluetoothInputDevice( 2548): Proxy object connected
D/HidProfile( 2548): Bluetooth service connected
D/BluetoothPan( 2548): BluetoothPAN Proxy object connected
D/PanProfile( 2548): Bluetooth service connected
D/BluetoothMap( 2548): Proxy object connected
D/MapProfile( 2548): Bluetooth service connected
D/BluetoothMap( 2548): getConnectedDevices()
V/BluetoothMapService( 1224): getConnectedDevices()
D/BluetoothPbap( 2548): Proxy object connected
D/PbapServerProfile( 2548): Bluetooth service connected
D/LGBluetoothUserBindClient( 2548): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2548): onReceive
D/LGBluetoothFeatureConfig( 2548): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2548): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2548): return without doing reset settings.
V/BluetoothOppReceiver( 1224): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1224): [BTUI] startOppService()
,V/BluetoothOppManager( 1224): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 1224): isPrivacyLogsEnabled : true
V/BtOppService( 1224): onCreate
,D/LGBluetoothOppAdapter( 1224): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothOppNotification( 1224): send message
,V/BtOppService( 1224): Starting RfcommListener
D/BluetoothOppPreference( 1224): Dumping Names:  
D/BluetoothOppPreference( 1224): {}
D/BluetoothOppPreference( 1224): Dumping Channels:  
,D/BluetoothOppPreference( 1224): {}
V/BtOppService( 1224): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BtOppService( 1224): onStartCommand
,V/BluetoothOppNotification( 1224): new notify threadi!
,V/BluetoothOppNotification( 1224): send delay message
V/BtOppService( 1224): start RfcommListener
,V/BtOppService( 1224): Deleted complete outbound shares, number =  0
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 1224): RfcommListener started
,V/BtOppRfcommListener( 1224): Starting RFCOMM listener....
V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 1224): ContentObserver received notification
V/BtOppService( 1224): ContentObserver received notification
V/BtOppService( 1224): Deleted complete inbound failed shares, number = 0
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
W/BluetoothAdapter( 1224): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@43169b00 on behalf of 
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@431684a0 on behalf of 
E/BluetoothServiceJni( 1224): SOCK FLAG = 0 ***********************
D/bt-btif ( 1224): btsock_rfc_listen, service_name:OBEX Object Push
,D/bt-btif ( 1224): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1224): BTA_JvCreateRecordByUser
D/bt-btif ( 1224): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1224): name:OBEX Object Push, scn:12
D/bt-btif ( 1224): scn 12, service name OBEX Object Push
D/bt-sdp  ( 1224): SDP_CreateRecord ok, num_records:13
I/bt-btif ( 1224): Adding UUID=0x1105 into EIR
D/bt-btif ( 1224): BTA is generating EIR
I/bt-btif ( 1224): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1224): BTA_JvRfcommStartServer
D/bt-btif ( 1224): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
,D/bt-btif ( 1224): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
D/LGBluetoothServiceAdapter( 1224): [BTUI] createSocketChannel FD=97 mFd=92
V/BtOppRfcommListener( 1224): Started RFCOMM listener....
I/BtOppRfcommListener( 1224): Accept thread started.
V/BtOppRfcommListener( 1224): Accepting connection...
,D/AuthorizationBluetoothService( 1534): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1534): Proximity feature is not enabled.
V/BtOppService( 1224): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@4316bd48 on behalf of 
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BluetoothOppNotification( 1224): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@4316d050 on behalf of 
,V/BluetoothOppNotification( 1224): update too frequent, put in queue
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 1224): pendingUpdate is false keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@4316f508 on behalf of 
,V/BluetoothOppNotification( 1224): outbound: succ-0  fail-0
V/BluetoothOppNotification( 1224): outbound notification was removed.
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@43171280 on behalf of 
,V/BluetoothOppNotification( 1224): inbound: succ-0  fail-0
V/BluetoothOppNotification( 1224): inbound notification was removed.
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@43172968 on behalf of 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4195): EAPOL: disable timer tick
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4195): EAPOL: disable timer tick
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/BluetoothOppNotification( 1224): new notify threadi!
,V/BluetoothOppNotification( 1224): send delay message
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@431743f8 on behalf of 
,V/BluetoothOppNotification( 1224): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@43176030 on behalf of 
,V/BluetoothOppNotification( 1224): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1224): outbound notification was removed.
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@43177bc0 on behalf of 
,V/BluetoothOppNotification( 1224): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1224): inbound notification was removed.
,V/BluetoothOppProvider( 1224): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1224): created cursor android.database.sqlite.SQLiteCursor@43179168 on behalf of 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/AudioFlinger(  275): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  275): thread 0xb26dc008 type 0 TID 709 going to sleep
,E/BatteryObserver( 1158): usb Uevent not necessary.
V/AudioFlinger(  275): releaseWakeLock_l() AudioOut_3
V/AudioFlinger(  275): thread 0xb2571008 type 0 TID 1002 going to sleep
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 4195): nl80211: Event message available
D/wpa_supplicant( 4195): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4195): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4195): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4195): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 4195): nl80211: Survey data missing
D/wpa_supplicant( 4195): wlan0: BSS: Start scan result update 1
,D/wpa_supplicant( 4195): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: BSS: Add new id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: BSS: Add new id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: BSS: Add new id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: BSS: Add new id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: BSS: Add new id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: BSS: Add new id 7 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4195): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 4195): wlan0: New scan results available
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4195): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4195): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4195): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 4195): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 4195): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4195): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4195): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4195): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4195): WPS: AP[4] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4195): wlan0: Selecting BSS from priority group 1
,D/wpa_supplicant( 4195): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 4195): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 4195): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-55 wps
,D/wpa_supplicant( 4195): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4195): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4195): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4195): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4195): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4195): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4195): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4195): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
,D/wpa_supplicant( 4195): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7e255a8  current_ssid=0x0
D/wpa_supplicant( 4195): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC
E/wpa_supplicant( 4195): USIM:  scard_init function
D/wpa_supplicant( 4195): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 4195): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4195): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4195): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 4195): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 4195): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 4195): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4195): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4195): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4195): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4195): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4195): wlan0: Cancelling scan request
D/wpa_supplicant( 4195): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4195): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 4195): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 4195): RSN: PMKSA cache search - network_ctx=0xb7e255a8 try_opportunistic=0
D/wpa_supplicant( 4195): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4195): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 4195): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 4195): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4195): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 4195): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4195): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 4195): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 4195): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4195): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0,
D/wpa_supplicant( 4195): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 4195): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4195): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4195): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4195): nl80211: Set mode ifindex 23 iftype 2 (STATION)
,D/wpa_supplicant( 4195): nl80211: Unsubscribe mgmt frames handle 0xb7e24590 (mode change)
D/wpa_supplicant( 4195): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7e24590,
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
,D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590,
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4195): nl80211: Register frame type=0xd0 nl_handle=0xb7e24590
D/wpa_supplicant( 4195): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4195): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 4195):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195):   * freq=2412
D/wpa_supplicant( 4195):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4195):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4195):   * Auth Type 0
D/wpa_supplicant( 4195):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 a0:c5:62:7a:49:97]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 06:7c:34:12:7f:81]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 44:e9:dd:10:c0:ac]
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 4195): nl80211: Connect request send successfully
D/wpa_supplicant( 4195): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4195): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4195): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4195): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4195): RSN: Ignored PMKID candidate without preauth flag
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 4195): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 4195): nl80211: Event message available
D/wpa_supplicant( 4195): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4195): nl80211: Connect event
D/wpa_supplicant( 4195): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4195): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4195): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4195): wlan0: Association info event
D/wpa_supplicant( 4195): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4195): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4195): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4195): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4195): wlan0: freq=2412 MHz
D/wpa_supplicant( 4195): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 4195): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4195): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4195): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4195): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4195): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): scard is not null..
D/wpa_supplicant( 4195): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4195): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4195): TDLS: Remove peers on association
D/wpa_supplicant( 4195): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4195): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4195): EAPOL: enable timer tick
D/wpa_supplicant( 4195): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4195): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4195): wlan0: Cancelling scan request
D/wpa_supplicant( 4195): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 4195): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 66 65 78 f3 62 ab 23 8d 4b 91 f5 f4 26 d1 17 ...
,D/wpa_supplicant( 4195): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4195): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4195): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4195): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4195): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4195):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4195):   key_nonce - hexdump(len=32): 66 65 78 f3 62 ab 23 8d 4b 91 f5 f4 26 d1 17 90 3c 89 84 ba 70 48 6b ed 5c 23 db ab c5 36 9c e6
D/wpa_supplicant( 4195):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4195):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4195):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4195):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4195): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 66 65 78 f3 62 ab 23 8d 4b 91 f5 f4 26 d1 17 ...
D/wpa_supplicant( 4195): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4195): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 4195): Get randomness: len=32 entropy=9
D/wpa_supplicant( 4195): WPA: Renewed SNonce - hexdump(len=32): 95 d8 8c 2e 10 15 dc d1 cc 94 df ab 3a 3c e3 af 71 a1 c3 ce 1d ae ee af 16 a5 92 11 b8 5a f3 aa
D/wpa_supplicant( 4195): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): WPA: Nonce1 - hexdump(len=32): 95 d8 8c 2e 10 15 dc d1 cc 94 df ab 3a 3c e3 af 71 a1 c3 ce 1d ae ee af 16 a5 92 11 b8 5a f3 aa
D/wpa_supplicant( 4195): WPA: Nonce2 - hexdump(len=32): 66 65 78 f3 62 ab 23 8d 4b 91 f5 f4 26 d1 17 90 3c 89 84 ba 70 48 6b ed 5c 23 db ab c5 36 9c e6
D/wpa_supplicant( 4195): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4195): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4195): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4195): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4195): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4195): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4195): WPA: Derived Key MIC - hexdump(len=16): 2b 3a 6d 26 2c da e8 ad 51 41 dd 45 42 ab 1b d9
D/wpa_supplicant( 4195): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 95 d8 8c 2e 10 15 dc d1 cc 94 df ab 3a 3c e3 ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 4195): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 66 65 78 f3 62 ab 23 8d 4b 91 f5 f4 26 d1 17 ...
D/wpa_supplicant( 4195): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4195): wlan0:   EAPOL-Key type=2
,D/wpa_supplicant( 4195): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4195): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4195):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4195):   key_nonce - hexdump(len=32): 66 65 78 f3 62 ab 23 8d 4b 91 f5 f4 26 d1 17 90 3c 89 84 ba 70 48 6b ed 5c 23 db ab c5 36 9c e6
D/wpa_supplicant( 4195):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4195):   key_rsc - hexdump(len=8): 14 9a 00 00 00 00 00 00
D/wpa_supplicant( 4195):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4195):   key_mic - hexdump(len=16): d1 bd 30 78 e4 5e 92 a6 bd 57 e8 99 38 5b 08 8e
D/wpa_supplicant( 4195): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 66 65 78 f3 62 ab 23 8d 4b 91 f5 f4 26 d1 17 ...
D/wpa_supplicant( 4195): RSN: encrypted key data - hexdump(len=56): 13 6a 42 69 ab da b5 92 32 5f 73 53 b9 ab 10 aa f3 74 51 e5 7d 94 77 c4 40 fe 0d bd 6e 69 d1 fb ...
D/wpa_supplicant( 4195): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4195): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4195): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4195): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 6d 3b ...
D/wpa_supplicant( 4195): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4195): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4195): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4195): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4195): WPA: Derived Key MIC - hexdump(len=16): 5b 32 4d 3e 33 6e e8 e6 85 ad 6d e4 8a a2 db f6
D/wpa_supplicant( 4195): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4195): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7e24c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4195):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4195): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4195): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 4195): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4195): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 4195): WPA: RSC - hexdump(len=6): 14 9a 00 00 00 00
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f8103a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 4195):    broadcast key
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 4195): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4195): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4195): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4195): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 4195): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4195): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4195): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4195): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4195): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4195): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4195): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4195): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4195): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4195): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4195): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4195): EAPOL authentication completed successfully
D/wpa_supplicant( 4195): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4195): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4195): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): Network connection established
,D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4195): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4195): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  967):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  967): ssid=NG700
D/WifiNative-wlan0(  967): id=0
D/WifiNative-wlan0(  967): mode=station
D/WifiNative-wlan0(  967): pairwise_cipher=CCMP
D/WifiNative-wlan0(  967): group_cipher=CCMP
D/WifiNative-wlan0(  967): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  967): wpa_state=COMPLETED
D/WifiNative-wlan0(  967): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  967): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-30ms what=147462 obj=android.net.wifi.StateChangeResult@43608510 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): StoppedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/DhcpStateMachine(  967): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-28ms what=147462 obj=android.net.wifi.StateChangeResult@4340b378 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-29ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-8ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=196612
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-10ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4337 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,D/WifiService(  967): New client listening to asynchronous messages
,D/HyLog   ( 4337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4337): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4337): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4337): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4337): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4337): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4337): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4337): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4337): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/QRemote ( 4337): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4337): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/ActivityManager(  967): Killing 3982:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 4195): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
,E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
,D/WifiStateMachine(  967): handleMessage: X
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43b274a8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43b274a8 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4364 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/HyLog   ( 4364): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4364): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4364): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.441406 Y: -0.399841 Z: 9.799271 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441406 .y:-0.399841 .z:9.799271
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Babel   ( 4364): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4364): MmsConfig.loadMmsSettings
,I/MediaCodecList( 4364): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 4364): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4364): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4364): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 4364): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4364): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 4364): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4364): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4364): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/Settings( 4364): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BaseRuntimeLoader( 4364): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4364): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4364): MmsConfig.loadFromResources
,E/Babel   ( 4364): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4364): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.453598 Y: -0.402939 Z: 9.824753 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453598 .y:-0.402939 .z:9.824753
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/LGRssiData( 4364): [loadRssi] File not exist 
V/LGRssiData( 4364): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4364): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  967): Killing 4015:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,V/TelephonyAutoProfiling( 4364): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4364): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4364): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/WifiStateMachine(  967): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  967): handleMessage: X
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  967): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/DhcpStateMachine(  967): RunningState
D/WifiStateMachine(  967): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4195): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4195): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 4195): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
,D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=0 connState=2
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/WifiStateMachine(  967): handleMessage: X
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1158): handleWifiStateChangedEvent: 1
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/QRemote ( 4337): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/QRemote ( 4337): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
V/        (  269): RouteController
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
V/        (  269): RouteController
D/QRemote ( 4337): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4337): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/        (  269): RouteController
V/        (  269): RouteController
,I/PCSuite ( 4196): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,V/        (  269): RouteController
,D/PCSuite ( 4196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4337): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 4337): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4337): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4337): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,V/        (  269): RouteController
,V/        (  269): RouteController
,V/        (  269): RouteController
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  269): RouteController
,D/QCNEA   (  473): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  473): |CAC| updateWlanNetCfgInfo
,D/QCNEA   (  473): |CAC| updateNetCfgInfo
V/QCNEA   (  473): |CAC| *********************************************
V/QCNEA   (  473): |CAC|                   Netconfig               
V/QCNEA   (  473): |CAC| *********************************************
V/QCNEA   (  473): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  473): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  473): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  473): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  473): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  473): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  473): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  473): |CAC| *********************************************
D/QCNEA   (  473): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  473): |CAC| net type = 1
V/QCNEA   (  473): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  473): |CAC| Received ssid= NG700
V/QCNEA   (  473): |CAC| 	ssid           =NG700
V/QCNEA   (  473): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  473): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  473): |CAC| *********************************************
D/QCNEA   (  473): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  473): |CAC| dispatching netcfgupdate for wlan
,D/QCNEA   (  473): |CAC| dispatchNetCfg: updating:0xb84158dc
D/libc    (  269): _dns_getaddrinfo: iptype =1
D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/libc    (  269): _dns_getaddrinfo: iptype =1
D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/wpa_supplicant( 4195): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4195): EAPOL: disable timer tick
,D/GpsLocationProvider(  967): calling native_inject_xtra_data
E/LocSvc_afw(  967): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  967): V/length: 59687
E/LocSvc_eng(  967):   data: 0x65ffd008
E/LocSvc_utils_q(  967): D/msg_q_snd: Sending message with handle = 0x7101B008
E/LocSvc_utils_ll(  967): D/linked_list_add: Adding to list data_obj = 0x7101B008
E/LocSvc_utils_q(  967): D/msg_q_snd: Finished Sending message with handle = 0x7101B008
,E/LocSvc_utils_ll(  967): D/linked_list_remove: Removing from list
E/LocSvc_afw(  967): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
E/LocSvc_utils_q(  967): D/msg_q_rcv: Received message 0x7101B008 rv = 0
E/LocSvc_eng(  967): V/length: 59687
E/LocSvc_eng(  967):   data: 0x65ffd008
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 59687
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/59, len = 1024, total injected = 0
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
,E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/59, len = 1024, total injected = 1024
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
,E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/59, len = 1024, total injected = 2048
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/59, len = 1024, total injected = 3072
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/59, len = 1024, total injected = 4096
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/59, len = 1024, total injected = 5120
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
,E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/59, len = 1024, total injected = 6144
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/59, len = 1024, total injected = 7168
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
,E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/59, len = 1024, total injected = 8192
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/59, len = 1024, total injected = 9216
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/59, len = 1024, total injected = 10240
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/59, len = 1024, total injected = 11264
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/59, len = 1024, total injected = 12288
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/59, len = 1024, total injected = 13312
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/59, len = 1024, total injected = 14336
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/59, len = 1024, total injected = 15360
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/59, len = 1024, total injected = 16384
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/59, len = 1024, total injected = 17408
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/59, len = 1024, total injected = 18432
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/59, len = 1024, total injected = 19456
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/59, len = 1024, total injected = 20480
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/59, len = 1024, total injected = 21504
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/59, len = 1024, total injected = 22528
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/59, len = 1024, total injected = 23552
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/59, len = 1024, total injected = 24576
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/59, len = 1024, total injected = 25600
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/59, len = 1024, total injected = 26624
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/59, len = 1024, total injected = 27648
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/59, len = 1024, total injected = 28672
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/59, len = 1024, total injected = 29696
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/59, len = 1024, total injected = 30720
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/59, len = 1024, total injected = 31744
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
,E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/59, len = 1024, total injected = 32768
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/59, len = 1024, total injected = 33792
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
,E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/59, len = 1024, total injected = 34816
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/59, len = 1024, total injected = 35840
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/59, len = 1024, total injected = 36864
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/GpsLocationProvider(  967): NTP server returned: 1452596533894 (Tue Jan 12 12:02:13 CET 2016) reference: 113704 certainty: 41 system time offset: 557
E/LocSvc_afw(  967): V/Entering int loc_inject_time(GpsUtcTime, int64_t, int) line 446 
E/LocSvc_eng(  967): I/===> int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1910 
E/LocSvc_eng(  967): V/time: 1452596533894
E/LocSvc_eng(  967):   timeReference: 113704
E/LocSvc_eng(  967):   uncertainty: 41
E/LocSvc_utils_q(  967): D/msg_q_snd: Sending message with handle = 0x609F2DF0
E/LocSvc_utils_ll(  967): D/linked_list_add: Adding to list data_obj = 0x609F2DF0
,E/LocSvc_utils_q(  967): D/msg_q_snd: Finished Sending message with handle = 0x609F2DF0
E/LocSvc_eng(  967): V/Exiting int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1917 0
E/LocSvc_afw(  967): V/Exiting int loc_inject_time(GpsUtcTime, int64_t, int) line 452 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/59, len = 1024, total injected = 37888
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/59, len = 1024, total injected = 38912
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/59, len = 1024, total injected = 39936
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/59, len = 1024, total injected = 40960
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/59, len = 1024, total injected = 41984
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/59, len = 1024, total injected = 43008
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/59, len = 1024, total injected = 44032
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53,
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/59, len = 1024, total injected = 45056
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/59, len = 1024, total injected = 46080
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/59, len = 1024, total injected = 47104
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/59, len = 1024, total injected = 48128
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/59, len = 1024, total injected = 49152
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/59, len = 1024, total injected = 50176
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/59, len = 1024, total injected = 51200
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/59, len = 1024, total injected = 52224
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/59, len = 1024, total injected = 53248
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/59, len = 1024, total injected = 54272
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/59, len = 1024, total injected = 55296
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/59, len = 1024, total injected = 56320
,E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/59, len = 1024, total injected = 57344
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58368
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 58/59, len = 1024, total injected = 58368
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 59392
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 59/59, len = 295, total injected = 59392
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 103, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69eaa728,
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 53, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 59687
,E/LocSvc_MsgTask(  967): D/MsgTask::loop() 26 listening ...
E/LocSvc_utils_q(  967): D/msg_q_rcv: Waiting on message
E/LocSvc_utils_ll(  967): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  967): D/msg_q_rcv: Received message 0x609F2DF0 rv = 0
E/LocSvc_eng(  967): V/time: 1452596533894
E/LocSvc_eng(  967):   timeReference: 113704
E/LocSvc_eng(  967):   uncertainty: 41
E/LocSvc_ApiV02(  967): V/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):436]: uncertainty = 41
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x69eaa728, ind_id 56, req_id 56 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 56
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=56, len = 16
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 56, len = 16,
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 104, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=56 buf_len=7 pCallbackData = 0x69eaa728
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 56 is a resp size = 4
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69eaa728, resp id = 56, client cookie ptr = 0x69eaa780
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x69eaa728 ind_id = 56 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 56 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 4 
,E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_MsgTask(  967): D/MsgTask::loop() 27 listening ...
,E/LocSvc_utils_q(  967): D/msg_q_rcv: Waiting on message,
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/WifiStateMachine(  967): handleMessage: X
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4139): Test app app.js loaded
I/jxcore-log( 4139): 
,I/chromium( 4139): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Choreographer( 4139): Skipped 403 frames!  The application may be doing too much work on its main thread.
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/        (  967): Setting time of day to sec=1452596536
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  967): MasterInitialState.processMessage what=3
,W/        (  967): Unable to set rtc to 1452596536: Invalid argument
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_SET
,I/SecureClockService( 1158): Intent.ACTION_TIME_CHANGED 
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452596536551, nextTick: 43481, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452596536553, nextTick: 43479, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,I/MusicWidget( 2098): intentReceiver onReceive() action::android.intent.action.TIME_SET
,I/MusicWidget( 2098): beingMusicWidget_4x2() result::false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/QCNEA   (  473): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WeatherService( 1872): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:2:16
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/MusicWidget( 2098): beingMusicWidget_Lock() result::false
I/MusicWidget( 2098): beingMusicWidget_Quick() result::false
D/WeatherService( 1872): 2 : requestRefreshAppWidget, isUpdateStart : false
I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 12
D/UpdateThreadPoolManager( 1872): 2 : This is isUpdating : false
D/WeatherService( 1872): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1872): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1872): 2 : Map key string is -2
I/MusicWidget( 2098): beingMusicWidget_4x1() result::true
I/MusicWidget( 2098): performViewUpdater handleMessage() msg.what::0
D/lim     ( 1872): 2 : time = 12:02
I/WeatherReflect( 1872): Model Name : LG-D802
D/WeatherTheme( 1872): 2 : Different view - status_min_formatted : 00 != 02
D/WeatherTheme( 1872): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1872): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1872): 2 : Fixed theme : optimus
D/WeatherTheme( 1872): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
I/MusicWidget( 2098): beingMusicWidget_4x1() result::true
I/MusicWidget( 2098): performUpdate()_4x1
I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 12
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/MusicWidget( 2098): status::mounted
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WeatherService( 1872): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:2:16
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,I/MusicWidget( 2098): defaultAppWidget()_4x1
,I/MusicWidget( 2098): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
,I/MusicWidget( 2098): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2098): appWidgetViewUpdate()_4x1
,I/MusicWidget( 2098): linkButtons()_4x1
,I/MusicWidget( 2098): pushUpdate()_4x1
,I/MusicWidget( 2098): performViewUpdater handleMessage() msg.what::3
,I/MusicWidget( 2098): beingMusicWidget_Quick() result::false
,I/ConfigFetchService( 1941): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1941): running network task: configservice_periodic
,E/WakeLock( 1941): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1941): launchTask
,I/ConfigService( 1534): onCreate
I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3629): onReceive
D/AppUp4:CustFacade( 3629): Context : android.app.ReceiverRestrictedContext@430bcf00
D/AppUp4:CustFacade( 3629): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3629): isOpenOperator : true
,D/AppUp4:CustFacade( 3629): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 3629): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3629): begin check event
I/AppUp4:CustModeStarterReceiver( 3629): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3629): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3629): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3629): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 3629): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3629): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4496 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/GoogleURLConnFactory( 1534): Using platform SSLCertificateSocketFactory
,D/HyLog   ( 4496): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4496): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4496): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4512 uid=10063 gids={50063, 3003, 1028, 1015}
,D/HyLog   ( 4512): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4512): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4512): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4496): DownloadService onCreate
,D/EAS     ( 4056): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4056): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/MusicWidget( 2098): performViewUpdater handleMessage() msg.what::1
,D/eas_req ( 4056): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/MusicWidget( 2098): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2098): beingMusicWidget_Lock() result::false
,I/DownloadManager( 4496): in removeSpuriousFiles
,I/ActivityManager(  967): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=4533 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
W/linker  ( 4056): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
V/DownloadManager( 4496): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430e5f40 on behalf of 4496
I/DownloadManager( 4496): in trimDatabase
D/HtmlEditor( 4056): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4056): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4056): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/dalvikvm( 4056): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4056): register_HtmlEditor, Success
D/HtmlEditor( 4056): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4056): register_HtmlEditorTimer, Success
D/HtmlEditor( 4056): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4056): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4056): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4056): register_HtmlEditorFont, Success
D/HtmlEditor( 4056): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4056): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4056): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4056): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4056): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4056): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4056): JNI_OnLoad Success
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430e7730 on behalf of 4496
I/HubEmail( 4056): JNI_OnLoad()
I/HubEmail( 4056): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4056): registerNatives()
I/HubEmail( 4056): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4056): registerNativeMethods()
I/HubEmail( 4056): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
V/DownloadManager( 4496): DownloadService onStartCommand
V/DownloadManager( 4496): DownloadService onStartCommand
V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430eb090 on behalf of 4496
W/Settings( 4056): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430ef0e8 on behalf of 4496
D/HyLog   ( 4533): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4533): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4533): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4496): DownloadService onDestroy
,D/DelayedSyncController( 4512): Delaying sync.
,I/ConversationSkinProvider( 4533): skin provider oncreate
,D/dalvikvm( 1534): GC_EXPLICIT freed 1197K, 28% free 17912K/24832K, paused 2ms+6ms, total 31ms
I/ActivityManager(  967): Killing 3648:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): Killing 4074:com.google.android.apps.docs/u0a73 (adj 15): empty #17
E/[MMS]   ( 4533): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,W/BaseRuntimeLoader( 4533): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4533): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
W/BaseRuntimeLoader( 4533): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4533): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 4533): MmsSettings: loadxmlstring=open_eu_mms_config
D/[MMS]   ( 4533): MmsSettings: Matching Xml Data file name = 2131034168
,W/DriveInitializer( 1941): Background init thread started
,I/ConfigFetchService( 1941): service connected
,D/ConfigFetchService( 1941): ConfigApi connection successful.
,E/Auth.Api.Credentials( 1941): [CredentialSyncAdapter] Unknown sync event.
,D/[MMS]   ( 4533): MmsSettings: [LGE]parseDTMF() file doesn't exist
,D/[MMS]   ( 4533): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 4533): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_char = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_priority = [1]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 4533): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 4533): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   del_old = [1]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 4533): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 4533): MmsSettings: [LGE]   attachement_storage = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 4533): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_creation_invisible = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_priority_invisible = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   attach_location = [1]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   hide_sync_header_update = [1]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 4533): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   china_feature_set = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 4533): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   message_poster = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 4533): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   smsc_readonly = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 4533): MmsSettings: [LGE]   mms_callback = [0]
,D/[MMS]   ( 4533): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
,E/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 4533): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 4533): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,I/[MMS]   ( 4533): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 4533): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  279): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  279): qmi_init:  Created client handle b7369f48
,E/Diag_Lib(  279): qmi_client [279] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  279): qmi_client [279] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  279): Sending signal ...... to read cmd data 
E/Diag_Lib(  279): qmi error code.........:0
E/Diag_Lib(  279): qmi sys error code.........:0
D/DRM_Adap(  279): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  279): Setting the api flag to : 1
,E/Diag_Lib(  279): qmi_client [279] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  279): qmi_client [279] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  279):  API Flag .............. 1 
E/Diag_Lib(  279):  Message ID ............... 37 
E/Diag_Lib(  279): qmi_service_release called, user_handle=20200
E/Diag_Lib(  279): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  279): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  279): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  279): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  279): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  279): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  279): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  279): qmi_client [279] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  279): qmi_client [279] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  279): Sending signal ...... to read cmd data 
E/Diag_Lib(  279): qmi error code.........:0
E/Diag_Lib(  279): qmi sys error code.........:0
D/DRM_Adap(  279): drmLibGetIMEI: success getting IMEI
,D/LGDRM   (  279): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  279): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  279): qmi_init:  Created client handle b7369f60
E/Diag_Lib(  279): qmi_client [279] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  279): qmi_client [279] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  279): Sending signal ...... to read cmd data 
E/Diag_Lib(  279): qmi error code.........:0
E/Diag_Lib(  279): qmi sys error code.........:0
D/DRM_Adap(  279): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
,E/Diag_Lib(  279): Setting the api flag to : 1
,E/Diag_Lib(  279): qmi_client [279] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  279): qmi_client [279] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  279):  API Flag .............. 1 
,E/Diag_Lib(  279):  Message ID ............... 37 
E/Diag_Lib(  279): qmi_service_release called, user_handle=20200
E/Diag_Lib(  279): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  279): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  279): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  279): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  279): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  279): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  279): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  279): qmi_client [279] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  279): qmi_client [279] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  279): Sending signal ...... to read cmd data 
E/Diag_Lib(  279): qmi error code.........:0
E/Diag_Lib(  279): qmi sys error code.........:0
D/DRM_Adap(  279): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  279): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 4533): isDrmV1 =true
,V/DrmWrapper( 4533): isDrmV2 =false
,W/DriveInitializer( 1941): Awaiting to be initialized
,D/dalvikvm(  967): GC_EXPLICIT freed 2313K, 49% free 29558K/57676K, paused 4ms+14ms, total 115ms
,V/MmsConfig( 4533): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 4533): [setMmsEnabledWhenDataDisabled]enabled=true
,V/MmsConfigStaticVar( 4533): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 4533): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 4533): Contact init()_Create new insatnce
,D/Batterystats( 1941): User is not opted-in to Usage & Diagnostics.
,I/MessagingNotification( 4533): registerLEDObserver
,I/MessagingNotification( 4533): registerLEDObserver REGISTER
,V/MmsConfig( 4533): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
,I/LOG_TAG ( 4533): registerContactDBChangeObserver
,I/LgeMiscReceiver( 4533): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4533): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4533): networkInfo.isConnected() = false
D/CountryDetector(  967): The first listener is added
,E/ActivityThread( 4533): Failed to find provider info for com.lge.ims.provider.uc
V/LGRssiData( 4533): [loadRssi] File not exist 
V/LGRssiData( 4533): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4533): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 4533): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4533): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4533): [getValue] FEATURE key : vzw_roaming_state, value : null
D/dalvikvm( 1941): GC_CONCURRENT freed 1211K, 23% free 19203K/24832K, paused 3ms+5ms, total 41ms
,I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4578 uid=10052 gids={50052, 3003}
,I/ActivityManager(  967): Killing 3697:com.android.vending/u0a50 (adj 15): empty #17
,W/DriveInitializer( 1941): Background init thread ended
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4578): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4578): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4578): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocationManagerService(  967): getProviders()=[passive, gps]
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocationManagerService(  967): request 4395fe40 passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
V/LGRssiData( 4578): [loadRssi] File not exist 
,V/LGRssiData( 4578): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4578): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4578): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4578): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4578): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4578): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4578): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/DelayedSyncController( 4512): Delaying sync.
V/TelephonyAutoProfiling( 4578): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4578): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 4578): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4578): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4578): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4578): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4601 uid=10066 gids={50066, 4002, 3003, 1028}
,D/dalvikvm(  273): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,D/HyLog   ( 4601): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4601): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4601): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1941): Checking schedule, now: 1452596537261 next: 1452528645153
,I/CheckinService( 1941): active receiver: enabled
I/ActivityManager(  967): Killing 1859:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
E/BatteryObserver( 1158): usb Uevent not necessary.
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,I/CheckinService( 1941): Preparing to send checkin request
,I/EventLogService( 1941): Accumulating logs since 1452596235801
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/DrmBroadcastReceiver( 4601): Receive CONNECTIVITY_ACTION
,D/LGDMClient( 2825): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  967): Killing 4274:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,D/LGDMClient( 2825): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2825): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,E/LGDMClient( 2825): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2825): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2825): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2825): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/NFS     ( 4292): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4292): CONNECT : WIFI_CONNECT
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4616 uid=10104 gids={50104, 3003, 1028, 1015}
,D/HyLog   ( 4616): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4616): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4616): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 4616): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinRequestBuilder( 1941): Checkin reason type: 8 attempt count: 1
D/WifiService(  967): New client listening to asynchronous messages
E/ActivityThread( 1941): Failed to find provider info for com.google.android.wearable.settings
,W/BaseRuntimeLoader( 1941): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1941): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1941): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1941): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/WebViewChromium( 4616): Binding Chromium to the main looper Looper (main, tid 1) {4309ccd8}
,I/chromium( 4616): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4616): Initializing chromium process, renderers=0
,W/chromium( 4616): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4616): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4616): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4616): Remote Branch: 
I/Adreno-EGL( 4616): Local Patches: 
I/Adreno-EGL( 4616): Reconstruct Branch: 
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 4616): Starting up...
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1941): awaiting user notification for token
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4394f298: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/ActivityManager(  967): Killing 4043:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 3679): GC_FOR_ALLOC freed 754K, 16% free 20915K/24832K, paused 17ms, total 17ms
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/iu.SyncManager( 1941): SYNC; picasa accounts
,I/dalvikvm-heap( 3679): Grow heap (frag case) to 26.507MB for 4099024-byte allocation
I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/NetworkLogImpl( 1941): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1941): num queued entries: 0
I/iu.UploadsManager( 1941): num updated entries: 0
,I/iu.SyncManager( 1941): NEXT; no task
,D/dalvikvm( 3679): GC_CONCURRENT freed 36K, 14% free 24894K/28836K, paused 3ms+3ms, total 19ms
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4659 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4659): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4659): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4659): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4659): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4659): VFY: replacing opcode 0x60 at 0x000b
,I/ActivityManager(  967): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4672 uid=10010 gids={50010, 3003, 1028, 4002}
D/dalvikvm( 4659): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4659): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4659): VFY: replacing opcode 0x62 at 0x005e
I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,I/GcmGroups( 1941): Failed to subscribe to group.
I/GcmGroups( 1941): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1941): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1941): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1941): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1941): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1941): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1941): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1941): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1941): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1941): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1941): 	at android.os.Looper.loop(Looper.java:136)
I/GcmGroups( 1941): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/MultiDex( 4659): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4659): install
,I/GcmGroups( 1941): Groups upload failed, retrying in 24000:00:00
,I/MultiDex( 4659): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4659): loading existing secondary dex files
,I/MultiDex( 4659): load found 3 secondary dex files
,I/MultiDex( 4659): install done
,D/HyLog   ( 4672): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4672): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4672): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4659): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4659): VFY: unable to resolve instance field 61
D/dalvikvm( 4659): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4659): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4659): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4659): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4659): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4659): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4659): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4659): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4659): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4659): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430a4360
,D/dalvikvm( 4659): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430a4360
,D/dalvikvm( 4659): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430a4360, skipping init
,D/dalvikvm( 4659): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430a4360
D/dalvikvm( 4659): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430a4360
,V/JNIHelp ( 4659): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
E/OpenGL ES Test( 4672): localeFound retString == en_US
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
,E/OpenGL ES Test( 4672): localeFound retString == en_US
,D/ALBootInit( 4672): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 4672): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4672): [setNextAlert] start
,D/Alarms  ( 4672): [setNextAlert] (1)
,D/dalvikvm( 4659): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430a4360
D/dalvikvm( 4659): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x430a4360
D/dalvikvm( 4659): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430a4360
D/dalvikvm( 4659): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x430a4360
,D/Alarms  ( 4672):  minTime  = 0
,D/Alarms  ( 4672):  -- OK multi -- 0
E/jeny.kim( 4672): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4672): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4672): setStatusBarIcon : false
,D/Alarms  ( 4672): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,D/WorldClockReceiver( 4672): ====action==>android.intent.action.TIME_SET
,E/OpenGL ES Test( 4672): getCurrentLocale == en_US
E/OpenGL ES Test( 4672): localeFound retString == en_US
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
E/OpenGL ES Test( 4672): localeFound retString == en_US
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
,E/OpenGL ES Test( 4672): localeFound retString == en_US
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
,E/OpenGL ES Test( 4672): localeFound retString == en_US
,E/OpenGL ES Test( 4672): isExistDatabase = false
I/CommonUtil( 4672): BUILD Country: EU
E/OpenGL ES Test( 4672): loadMapCityData() -- S
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
E/OpenGL ES Test( 4672): localeFound retString == en_US
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
,E/OpenGL ES Test( 4672): localeFound retString == en_US
,E/OpenGL ES Test( 4672): loadMapCityData() - While S
,I/ProviderInstaller( 4659): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 1534): GC_EXPLICIT freed 1003K, 28% free 17883K/24832K, paused 1ms+3ms, total 24ms
,E/OpenGL ES Test( 4672): loadMapCityData() - While E
,E/OpenGL ES Test( 4672): loadMapCityData() -- E
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
E/OpenGL ES Test( 4672): localeFound retString == en_US
E/OpenGL ES Test( 4672): getCurrentLocale == en_US
,E/OpenGL ES Test( 4672): localeFound retString == en_US
,I/dalvikvm( 4659): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4659): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4659): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4659): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x0201
,E/OpenGL ES Test( 4672): [updateWidgetDST] backup_cityInfoList is null >>>>
,I/ActivityManager(  967): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4692 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4240:com.lge.settings.easy/1000 (adj 15): empty #17
,D/HyLog   ( 4692): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4692): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4692): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,D/GCM     ( 1534): Connected
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1534): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Config  ( 4692): LGCalendar ver.4.2.6
I/Config  ( 4692): start check model
,I/Config  ( 4692): start check native_ca
,E/Config  ( 4692): [setCountryAndOperator] Operator=OPEN, Country=EU
,D/dalvikvm(  967): GC_EXPLICIT freed 1409K, 49% free 29514K/57676K, paused 2ms+6ms, total 107ms
,D/CalendarWidget( 4692): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,I/InitNotificationRingtoneService( 4692): Start InitializeAlertRingtoneService.onHandleIntent
,D/WVCdm   (  275): Instantiating CDM.
,I/WVCdm   (  275): Level3 Library Nov 20 2013 18:09:31
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/dalvikvm( 4659): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.a.a
W/dalvikvm( 4659): VFY: unable to resolve virtual method 299: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x0013
I/ActivityManager(  967): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4712 uid=10016 gids={50016, 3003, 1028, 1015}
,D/DrmWidevineDash(  275): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/QSEECOMAPI: (  275): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  275): App is not loaded in QSEE
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,I/InitNotificationRingtoneService( 4692): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 4692): Found default schedule notification : Schedule.ogg(id:42)
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/InitNotificationRingtoneService( 4692): set default noti to content://media/internal/audio/media/42
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/InitNotificationRingtoneService( 4692): End InitializeAlertRingtoneService.onHandleIntent
D/HyLog   ( 4712): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4712): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4712): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,W/dalvikvm( 4659): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4659): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,W/dalvikvm( 4659): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 4659): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4659): VFY: unable to resolve virtual method 727: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x00bb
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,I/GoogleURLConnFactory( 4659): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  275): Loaded image: APP id = 2
,D/DrmWidevineDash(  275): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fee000
,E/DrmWidevineDash(  275): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fee000
,I/CalendarProvider2( 4712): Created com.android.providers.calendar.CalendarAlarmManager@430bec10(com.android.providers.calendar.CalendarProvider2@430b5ab8)
,E/DataScheduler( 4659): isDataSchedulerEnabled():false
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/DrmWidevineDash(  275): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  275): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  275): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  275): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  275): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  275): CdmEngine::OpenSession
,D/DrmWidevineDash(  275): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  275): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  275): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
I/ActivityManager(  967): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4743 uid=10043 gids={50043, 3003, 1028, 1015}
I/ActivityManager(  967): Killing 4364:com.google.android.talk/u0a77 (adj 15): empty #17
,D/DrmWidevineDash(  275): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetDeviceID...
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/DrmWidevineDash(  275): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateNonce. SID = 1
D/HyLog   ( 4743): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4743): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4743): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,D/DrmWidevineDash(  275): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  275): PrepareKeyRequest: nonce=2920175673
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
,E/TASKS   ( 4743): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/TASKS_APP_WIDGET( 4743): onReceive() #################################################
,I/TASKS   ( 4743): getCurrentThemeInfo START #############################
I/TASKS   ( 4743): com.lge.launcher2.theme.optimus
I/TASKS   ( 4743): com.lge.task
I/TASKS   ( 4743): getCurrentThemeInfo END #############################
I/TASKS   ( 4743): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4743): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4743): intentAction : android.intent.action.TIME_SET
,I/ActivityManager(  967): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4761 uid=10122 gids={50122}
,I/ActivityManager(  967): Killing 4196:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/HyLog   ( 4761): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4761): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4761): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 4761): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x430a7f20, skipping init
,D/TimeService( 4761): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452596538233
D/        ( 4761): TimeServiceNative: User Time to be set is 1452596538233
D/QC-time-services( 4761): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4761): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4761): Lib:time_genoff_operation: pargs->ts_val = 1452596538233
D/QC-time-services( 4761): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  482): Daemon: Connection accepted:time_genoff
D/QC-time-services(  482): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452596538233
D/QC-time-services(  482): Daemon:genoff_opr: Base = 2, val = 1452596538233, operation = 0
D/QC-time-services(  482): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/19/70 22:46:44
D/QC-time-services(  482): Daemon:Value read from RTC seconds = 12005204000
,D/QC-time-services(  482): Daemon:new time 1452596538233 
D/QC-time-services(  482): Daemon: delta 1440591334233 genoff 1440591334233 
D/QC-time-services(  482): Daemon:genoff_persistent_update: Writing genoff = 1440591334233 to memory
D/QC-time-services(  482): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  482): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  482): Updating the TOD offset
D/QC-time-services(  482): Daemon:genoff_persistent_update: Writing genoff = 1440591334233 to memory
D/QC-time-services(  482): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  482): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  482): Daemon:Update to modem bit set
D/QC-time-services(  482): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  482): Daemon: Base = 2, Value being sent to MODEM = 1136631738233
,E/QC-time-services( 4761): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  482): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  482): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 0
,I/ActivityManager(  967): Killing 4337:com.lge.qremote/u0a96 (adj 15): empty #17
I/WVCdm   (  275): CdmEngine::CloseSession
D/DrmWidevineDash(  275): calling OEMCrypto_CloseSession. SID = 1
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
D/DrmWidevineDash(  275): OEMCrypto_CloseSession returns 0
,I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3629): onReceive
D/AppUp4:CustFacade( 3629): Context : android.app.ReceiverRestrictedContext@430bcf00
D/AppUp4:CustFacade( 3629): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3629): isOpenOperator : true
,D/AppUp4:CustFacade( 3629): isPhone : true
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
I/LicenseContentProvider( 2946): start selecting data
D/SIMObserver( 2946): simInfo1
I/AppUp4:EulaManager( 3629): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3629): begin check event
I/AppUp4:CustModeStarterReceiver( 3629): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/DownloadManager( 4496): DownloadService onCreate
I/DownloadManager( 4496): in removeSpuriousFiles
V/DownloadManager( 4496): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430f6640 on behalf of 4496
D/EAS     ( 4056): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4056): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4496): in trimDatabase
V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430f8348 on behalf of 4496
,V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430fa080 on behalf of 4496
I/LgeMiscReceiver( 4533): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4533): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4533): networkInfo.isConnected() = true
,D/PhoneState( 4533): setPdpRejectCasuse : false
,W/Settings( 4056): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4578): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4578): onReceive CONNECTIVITY_CHANGE networkType=1
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/DrmBroadcastReceiver( 4601): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4601): 1  network is available. Sync DRM Time with NTP
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,V/DownloadManager( 4496): DownloadService onDestroy
,V/DrmService( 4601): Service onCreate
,D/DrmService( 4601): Received new request = 2
,D/LGDMClient( 2825): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/WifiController(  967): battery changed pluggedType: 2
I/DrmSntpClient( 4601): Start Sync process
D/DrmSntpClient( 4601): Server : 0
E/DataScheduler( 4601): isDataSchedulerEnabled():false
D/libc    (  269): _dns_getaddrinfo: iptype =1
D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/LGDMClient( 2825): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2825): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4782 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
E/LGDMClient( 2825): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2825): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2825): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2825): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4782): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4782): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4782): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4292): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4292): CONNECT : WIFI_CONNECT
,D/dalvikvm( 3679): GC_FOR_ALLOC freed 8K, 14% free 24889K/28836K, paused 10ms, total 10ms
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/dalvikvm-heap( 3679): Grow heap (frag case) to 30.388MB for 4099024-byte allocation
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/LGDrmService( 4601): _DRM_ServiceGet() : Bind lgdrm service
I/LGDRM   (  279): [DRM] SET TIME : YR=2016, MON=1, DAY=12
,I/LGDRM   (  279): [DRM] SET TIME : HR=11, MIN=2, SEC=18
,I/DrmSntpClient( 4601): Synched,
D/DrmService( 4601): Completed !! request = 2
,D/DrmService( 4601): Request count = 0
,V/DrmService( 4601): Service onDestroy
I/ActivityManager(  967): Killing 3663:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/dalvikvm( 3679): GC_CONCURRENT freed 4K, 13% free 28892K/32840K, paused 6ms+3ms, total 33ms
,D/dalvikvm( 3679): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/dalvikvm-heap( 3679): Grow heap (frag case) to 34.297MB for 4099024-byte allocation
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/WeatherAncestor( 1872): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:2:18
,D/UpdateThreadPoolManager( 1872): 2 : This is isUpdating : false
,D/Weather_cast( 1872): 2 : Request from alarm is Canceled
I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
D/WeatherAncestor( 1872): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:2:18
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WeatherService( 1872): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
D/WeatherQuickCover( 1872): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1872): 2 : Utils getTopActivity com.lge.launcher2 / false
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AuthorizationBluetoothService( 1534): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1534): Proximity feature is not enabled.
D/Weather.Utils( 1872): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1872): 2 : shouldTimeTickRegistered : false
,V/GmsCoreStatsServiceLauncher( 1941): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,I/ActivityManager(  967): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4799 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,E/Ads     ( 1941): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,D/LocationInitializer( 1941): Restart initialization of location
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4812 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/HyLog   ( 4799): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4799): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4799): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4812): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4812): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4812): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4799): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4799): VFY: replacing opcode 0x60 at 0x000b
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
,D/dalvikvm( 4799): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4799): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4799): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4799): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4799): install
,I/MultiDex( 4799): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4799): loading existing secondary dex files
,I/MultiDex( 4799): load found 3 secondary dex files
,W/ActivityThread(  967): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/MultiDex( 4799): install done
,D/dalvikvm( 4799): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4799): VFY: unable to resolve instance field 61
,D/dalvikvm( 4799): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4799): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4799): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4799): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4799): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4799): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4799): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4799): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4799): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4799): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430ab430
D/dalvikvm( 4799): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430ab430
,D/dalvikvm( 4799): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430ab430, skipping init
,D/dalvikvm( 4659): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43423e90
D/dalvikvm( 4659): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43423e90
,D/dalvikvm( 4659): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43423e90, skipping init
,D/dalvikvm( 4799): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430ab430
,D/dalvikvm( 4799): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430ab430
,V/JNIHelp ( 4799): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/MediaCodecList( 4812): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 4812): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4812): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4812): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 4812): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4812): MmsConfig.loadMmsSettings
,I/Babel   ( 4812): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4812): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 4812): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/dalvikvm( 4799): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430ab430
,D/dalvikvm( 4799): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x430ab430
D/dalvikvm( 4799): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430ab430
D/dalvikvm( 4799): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x430ab430
,W/BaseRuntimeLoader( 4812): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4812): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4812): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 4812): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4812): MmsConfig.loadFromResources
,W/Settings( 4812): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 4812): canonicalizeMccMnc: invalid mccmnc nullnull
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/Babel   ( 4812): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
V/LGRssiData( 4812): [loadRssi] File not exist 
V/LGRssiData( 4812): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4812): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4812): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4812): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4812): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3629): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3629): onReceive
D/AppUp4:CustFacade( 3629): Context : android.app.ReceiverRestrictedContext@430bcf00
D/AppUp4:CustFacade( 3629): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3629): isOpenOperator : true
,D/AppUp4:CustFacade( 3629): isPhone : true
,I/LicenseContentProvider( 2946): start selecting data
,D/SIMObserver( 2946): simInfo1
,I/AppUp4:EulaManager( 3629): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3629): begin check event
,I/AppUp4:CustModeStarterReceiver( 3629): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4496): DownloadService onCreate
D/EAS     ( 4056): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4056): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4496): in removeSpuriousFiles
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430fe208 on behalf of 4496
,I/DownloadManager( 4496): in trimDatabase
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@430ff900 on behalf of 4496
I/LgeMiscReceiver( 4533): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4533): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4533): networkInfo.isConnected() = true
,D/PhoneState( 4533): setPdpRejectCasuse : false
,W/Settings( 4056): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4578): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4578): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ProviderInstaller( 4799): Installed default security provider GmsCore_OpenSSL
,D/LGDMClient( 2825): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMSGCM( 4782): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2825): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 4292): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4292): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2825): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4782): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43101db0 on behalf of 4496
E/LGDMClient( 2825): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2825): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2825): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2825): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4496): DownloadService onDestroy
,D/dalvikvm( 3679): GC_CONCURRENT freed 7K, 10% free 33211K/36844K, paused 2ms+3ms, total 22ms
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/WVCdm   (  275): CdmEngine::OpenSession
,D/DrmWidevineDash(  275): calling OEMCrypto_OpenSession...
,D/CalendarWidget( 4692): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4692): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
D/DrmWidevineDash(  275): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  275): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
I/dalvikvm( 4799): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
,W/dalvikvm( 4799): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
D/TASKS_APP_WIDGET( 4743): onReceive() #################################################
,D/dalvikvm( 4799): VFY: replacing opcode 0x6e at 0x003f
I/TASKS   ( 4743): getCurrentThemeInfo START #############################
I/TASKS   ( 4743): com.lge.launcher2.theme.optimus
I/TASKS   ( 4743): com.lge.task
I/TASKS   ( 4743): getCurrentThemeInfo END #############################
I/TASKS   ( 4743): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4743): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4743): intentAction : com.lge.task.APPWIDGET_UPDATE
,D/WearableService( 4799): callingUid 10006, callindPid: 4799
E/dalvikvm( 4799): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4799): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 4799): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 4799): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/DrmWidevineDash(  275): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GetDeviceID...
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1534): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1534): Proximity feature is not enabled.
D/DrmWidevineDash(  275): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateNonce. SID = 1
,V/GmsCoreStatsServiceLauncher( 1941): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  275): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  275): PrepareKeyRequest: nonce=1466089621
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
I/dalvikvm( 4799): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4799): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4799): VFY: replacing opcode 0x6e at 0x000d
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  275): calling OEMCrypto_GenerateRSASignature. SID = 1
I/dalvikvm( 4799): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4799): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4799): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1941): Restart initialization of location
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
D/CalendarWidget( 4692): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4692): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,E/MDM     ( 1426): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1426): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DrmWidevineDash(  275): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  275): CdmEngine::CloseSession
,D/DrmWidevineDash(  275): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  275): OEMCrypto_CloseSession returns 0
,W/Settings( 4659): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4659): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/Babel   ( 4812): UserRecoverableAuthException.
,E/Babel   ( 4812): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4812): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4812): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4812): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4812): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4812): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4812): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4812): Error getting auth token
,E/Babel   ( 4812): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4812): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4812): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4812): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4812): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4812): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4812): Account registration failedRedacted-21
,E/Babel   ( 4812): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4812): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4812): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4812): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4812): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4812): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,I/Babel   ( 4812): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4812): Account sign in complete with state 106account: Redacted-21
,D/dalvikvm( 4855): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 4659): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4659): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 94ms
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4659): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4659): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4659): Remote Branch: 
I/Adreno-EGL( 4659): Local Patches: 
I/Adreno-EGL( 4659): Reconstruct Branch: 
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43aaa040: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,E/Babel   ( 4812): Unexpected exception while authenticating.
,E/Babel   ( 4812): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4812): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4812): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4812): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4812): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4812): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4812): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4812): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4812): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 9010K, 13% free 68356K/78436K, paused 34ms, total 34ms
,I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4659): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4659): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4659): Remote Branch: 
I/Adreno-EGL( 4659): Local Patches: 
I/Adreno-EGL( 4659): Reconstruct Branch: 
,I/CalendarProvider2( 4712): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4712): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4692): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4692): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/CalendarWidget( 4692): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 4692): Beginning updateAlertNotification
,D/AlertService( 4692): No fired or scheduled alerts
,D/CalendarWidget( 4692): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4692): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
I/ActivityManager(  967): Killing 4672:com.lge.clock/u0a10 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=4863 uid=10050 gids={50050, 3003, 1028, 1015}
,D/dalvikvm(  273): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+5ms, total 22ms
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 4659): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4659): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4659): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4659): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4659): Remote Branch: 
I/Adreno-EGL( 4659): Local Patches: 
I/Adreno-EGL( 4659): Reconstruct Branch: 
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  967): GC_EXPLICIT freed 1685K, 49% free 29617K/57676K, paused 2ms+6ms, total 92ms
,D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4863): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 4863): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 4863): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4863): VFY: replacing opcode 0x6e at 0x000b
,I/CheckinRequestBuilder( 1941): Classify the device as Phone.
,D/Finsky  ( 4863): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4863): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 4863): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4863): VFY: replacing opcode 0x6e at 0x004f
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/BaseRuntimeLoader( 4863): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4863): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4863): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4863): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 4863): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4863): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4863): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4863): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4863): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4863): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 4863): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4863): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4863): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 4863): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4863): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 4863): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43106e90 on behalf of 4863
,I/dalvikvm( 4863): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4863): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4863): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 4863): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 4863): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4863): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 4863): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4863): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4863): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4863): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1941): GC_CONCURRENT freed 1629K, 22% free 19558K/24832K, paused 2ms+3ms, total 32ms
,I/dalvikvm( 4863): Total arena pages for JIT: 11
,I/dalvikvm( 4863): Total arena pages for JIT: 12
I/dalvikvm( 4863): Total arena pages for JIT: 13
,I/dalvikvm( 4863): Total arena pages for JIT: 14
,I/CheckinTask( 1941): Sending checkin request (11735 bytes)
,D/Finsky  ( 4863): [423] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4863): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  967): Killing 4761:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinResponseProcessor( 1941): From server: 2 gservices updates and 0 deletes
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/CertBlacklister(  967): Certificate blacklist changed, updating...
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CertBlacklister(  967): Certificate blacklist updated
,I/GservicesProvider( 1534): main difference update completed
,I/ActivityManager(  967): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4928 uid=10003 gids={50003, 3003, 2001}
,I/CheckinRequestBuilder( 1941): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1941): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4928): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4928): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 4928): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4928): Update started
,D/DownloadManager( 4496): DB Update : deleted 1
,V/DownloadManager( 4496): DownloadService onCreate
,I/DownloadManager( 4496): in removeSpuriousFiles
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 4863): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4310f1e0 on behalf of 4496
D/dalvikvm( 4863): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4863): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4863): VFY: replacing opcode 0x62 at 0x0037
,V/DownloadManager( 4496): initiating download with UID 10003
I/DownloadManager( 4496): in trimDatabase
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43113520 on behalf of 4496
V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43115980 on behalf of 4496
,V/DownloadManager( 4496): processing inserted download 221
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:190
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43119018 on behalf of 4496
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DownloadManager( 4496): DB Update : status 192
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4311d670 on behalf of 4496
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4311d8a0 on behalf of 4496
V/DownloadManager( 4496): processing updated download 221, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4311faa8 on behalf of 4496
,E/UpdateRequestReceiver( 4928): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/DownloadManager( 4496): Download 221 starting
,I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,W/ContextImpl( 4928): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,D/DownloadManager( 4496): fileSize : -1state.mContinuingDownload :false
,I/UpdateFetcherService( 4928): Update started
,D/DownloadManager( 4496): DB Update : deleted 1
,D/dalvikvm( 1534): GC_EXPLICIT freed 1614K, 28% free 17929K/24832K, paused 2ms+3ms, total 31ms
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43129f18 on behalf of 4496
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,V/DownloadManager( 4496): initiating download with UID 10003
,V/DownloadManager( 4496): processing updated download 221, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,W/Finsky  ( 4863): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x44bfd4b8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,V/DownloadManager( 4496): DownloadService onStartCommand
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4313b640 on behalf of 4496
W/CheckinRequestBuilder( 1941): awaiting user notification for token
E/DataScheduler( 4496): isDataSchedulerEnabled():false
D/libc    (  269): _dns_getaddrinfo: iptype =1
D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4313f350 on behalf of 4496
V/DownloadManager( 4496): processing updated download 221, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43140fc0 on behalf of 4496
V/DownloadManager( 4496): processing inserted download 222
V/LFT     ( 4496): isReadyToDownload mId, mStatus=222:190
V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43143118 on behalf of 4496
D/DownloadManager( 4496): DB Update : status 192
I/CheckinRequestBuilder( 1941): Classify the device as Phone.
I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431453d0 on behalf of 4496
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431473c8 on behalf of 4496
I/DownloadManager( 4496): Download 222 starting
E/UpdateRequestReceiver( 4928): Received malformed URL while handling Gservices.CHANGED_ACTION
V/DownloadManager( 4496): processing updated download 221, status: 192
I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
E/UpdateRequestReceiver( 4928): Received malformed URL while handling Gservices.CHANGED_ACTION
V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
E/UpdateRequestReceiver( 4928): Received malformed URL while handling Gservices.CHANGED_ACTION
D/DownloadManager( 4496): fileSize : -1state.mContinuingDownload :false
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4314a300 on behalf of 4496
V/DownloadManager( 4496): processing updated download 222, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=222:192
V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4314f2e8 on behalf of 4496
I/ActivityManager(  967): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4977 uid=10009 gids={50009, 3003}
,D/HyLog   ( 4977): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4977): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4977): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinTask( 1941): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1941): Checking schedule, now: 1452596540682 next: 1453173936665
,I/CheckinService( 1941): active receiver: disabled
,I/DownloadManager( 4496): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4496): Content-Disposition: null
V/DownloadManager( 4496): Content-Length: -1
V/DownloadManager( 4496): Content-Location: null
V/DownloadManager( 4496): Content-Type: text/plain
V/DownloadManager( 4496): ETag: null
V/DownloadManager( 4496): Transfer-Encoding: chunked
V/DownloadManager( 4496): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4496): Min update size = 16384
,V/DownloadManager( 4496): getting filename from uri
,I/DownloadManager( 4496): in verifySpace, destination: 5, path: 10152015-sms-metadata.txt, length: 0
V/DownloadManager( 4496): keeping extension
,V/DownloadManager( 4496): target file: /cache/10152015-sms-metadata.txt
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431698a0 on behalf of 4496
,D/DownloadManager( 4496): DB Update : title 10152015-sms-metadata.txt
D/DownloadManager( 4496): DB Update : mimetype text/plain
D/DownloadManager( 4496): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4496): DB Update : total_bytes -1
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,W/BaseRuntimeLoader( 4977): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43182e70 on behalf of 4496
,W/BaseRuntimeLoader( 4977): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/BaseRuntimeLoader( 4977): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4977): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/LGDrmService( 4496): _DRM_ServiceGet() : Bind lgdrm service
,V/DownloadManager( 4496): processing updated download 221, status: 192
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431ac908 on behalf of 4496
,D/DownloadManager( 4496): DB Update : current_bytes 383
,D/DownloadManager( 4496): DB Update : total_bytes 383
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4863): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/DownloadManager( 4496): processing updated download 222, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=222:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431b8508 on behalf of 4496
,I/CheckinService( 1941): Checking schedule, now: 1452596540761 next: 1453173936665
,I/CheckinService( 1941): active receiver: disabled
,V/LFT     ( 4496): notifyThroughDatabase after updateDB  id :  222, mstatus : 192, largemode : 0, settingMode : 0
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 4496): notifyThroughDatabase start id : 222 name : /cache/10152015-sms-metadata.txt status : 200
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431bc5b0 on behalf of 4496
,V/DownloadManager( 4496): processing updated download 221, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431bd8f8 on behalf of 4496
,D/DownloadManager( 4496): DB Update : numfailed 0
D/DownloadManager( 4496): DB Update : method 0
,D/DownloadManager( 4496): DB Update : lastmod 1452596540780
D/DownloadManager( 4496): DB Update : mimetype text/plain
D/DownloadManager( 4496): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4496): DB Update : status 200
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431c1610 on behalf of 4496
,V/DownloadManager( 4496): processing updated download 222, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=222:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4496): Download 222 finished with status SUCCESS
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431c5488 on behalf of 4496
,D/DownloadManager( 4496): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 4496): checkStatusUpdate return true mID : mStatus = 222 : 200 => 200
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431ca250 on behalf of 4496
,V/DownloadManager( 4496): processing updated download 221, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@431cd4c0 on behalf of 4496
,D/dalvikvm(  967): GC_EXPLICIT freed 1254K, 49% free 29713K/57676K, paused 2ms+7ms, total 95ms
,I/ContactAccountLoggerTas( 2623): canRun() : Opted Out
,I/Search.GservicesUpdateTask( 2623): Updating Gservices keys
,I/ContactAccountLoggerTas( 2623): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2623): canRun() : Opted Out
,W/Search.LoginHelper( 2623): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2623): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2623): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2623): canRun() : Opted Out
,I/CheckinService( 1941): Checking schedule, now: 1452596540934 next: 1453173936665
,I/CheckinService( 1941): active receiver: disabled
,I/SystemUpdateService( 1941): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1941): onCreate
,D/SystemUpdateService( 1941): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/SystemEventReceiver( 1941): Received GSERVICES_CHANGED broadcast
,I/SystemUpdateService( 1941): cancelUpdate (empty URL)
,I/SystemUpdateService( 1941): active receiver: disabled
,I/OcrUtils( 1941): Updating ocr activity enabled=false
,D/GCM     ( 1534): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1426): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,D/SystemUpdateService( 1941): onDestroy
,I/GCoreUlr( 1426): DispatchingService.onCreate()
,W/ActivityThread( 4496): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/dalvikvm( 1534): GC_EXPLICIT freed 690K, 28% free 17917K/24832K, paused 6ms+3ms, total 35ms
,I/GCoreUlr( 1426): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/dalvikvm( 1534): null clazz in OP_INSTANCE_OF, single-stepping
,I/DownloadManager( 4496): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4496): Content-Disposition: null
,V/DownloadManager( 4496): Content-Length: -1
V/DownloadManager( 4496): Content-Location: null
V/DownloadManager( 4496): Content-Type: text/plain
V/DownloadManager( 4496): ETag: null
V/DownloadManager( 4496): Transfer-Encoding: chunked
V/DownloadManager( 4496): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4496): Min update size = 16384
V/DownloadManager( 4496): getting filename from uri
,I/DownloadManager( 4496): in verifySpace, destination: 5, path: 08202014-metadata.txt, length: 0
V/DownloadManager( 4496): keeping extension
V/DownloadManager( 4496): target file: /cache/08202014-metadata.txt
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432c1cb0 on behalf of 4496
,D/DownloadManager( 4496): DB Update : title 08202014-metadata.txt
D/DownloadManager( 4496): DB Update : mimetype text/plain
,D/DownloadManager( 4496): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 4496): DB Update : total_bytes -1
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432c4770 on behalf of 4496
,I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 4496): processing updated download 221, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432c69d0 on behalf of 4496
,D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): DB Update : current_bytes 384
,D/DownloadManager( 4496): DB Update : total_bytes 384
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 4496): notifyThroughDatabase after updateDB  id :  221, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 4496): notifyThroughDatabase start id : 221 name : /cache/08202014-metadata.txt status : 200
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432d38a8 on behalf of 4496
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432d4e80 on behalf of 4496
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DownloadManager( 4496): DB Update : numfailed 0
D/DownloadManager( 4496): DB Update : method 0
D/DownloadManager( 4496): DB Update : lastmod 1452596541137
D/DownloadManager( 4496): DB Update : mimetype text/plain
,D/DownloadManager( 4496): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 4496): DB Update : status 200
,V/DownloadManager( 4496): processing updated download 221, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=221:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432d78b0 on behalf of 4496
,I/DownloadManager( 4496): Download 221 finished with status SUCCESS
D/DownloadManager( 4496): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 4496): checkStatusUpdate return true mID : mStatus = 221 : 200 => 200
,V/DownloadManager( 4496): DownloadService onDestroy
,I/Auth    ( 1534): [DefaultAuthDelegateService] Use browser flow? false
I/ActivityManager(  967): Killing 2946:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,I/ActivityThread( 3629): Removing dead content provider:android.content.ContentProviderProxy@430f91c8
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,W/Finsky  ( 4863): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4863): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4863): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4863): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,I/ActivityManager(  967): Killing 3629:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/GCoreUlr( 1426): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,E/ThermalEngine(  292): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/GCoreUlr( 1426): Unbound from all location providers
,D/dalvikvm( 1941): GC_EXPLICIT freed 1150K, 22% free 19458K/24832K, paused 2ms+3ms, total 39ms
,I/GCoreUlr( 1426): DispatchingService.onDestroy()
,I/GCoreUlr( 1426): Unbound from all location providers
,D/dalvikvm( 1534): GC_EXPLICIT freed 278K, 28% free 17904K/24832K, paused 1ms+3ms, total 21ms
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 222; sort is lastmod DESC.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432dc6c8 on behalf of 4928
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 222; sort is lastmod DESC.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432dfe60 on behalf of 4928
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/ContextImpl( 4928): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 4496): initiating download with UID 10003
,V/DownloadManager( 4496): DownloadService onCreate
,I/DownloadManager( 4496): in removeSpuriousFiles
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432e53f8 on behalf of 4496
I/DownloadManager( 4496): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 4496): in removeSpuriousFiles, preserving file /cache/10152015-sms-metadata.txt
,I/DownloadManager( 4496): in trimDatabase
V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432e7258 on behalf of 4496
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432e8ae8 on behalf of 4496
,V/DownloadManager( 4496): processing inserted download 221
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 4496): processing inserted download 222
,V/DownloadManager( 4496): processing inserted download 223
V/LFT     ( 4496): isReadyToDownload mId, mStatus=223:190
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432edb90 on behalf of 4496
,D/DownloadManager( 4496): DB Update : status 192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 221; sort is lastmod DESC.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432f1bb0 on behalf of 4928
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 221; sort is lastmod DESC.
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432f7038 on behalf of 4496
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432f7760 on behalf of 4928
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432f8448 on behalf of 4496
,W/ContextImpl( 4928): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/DownloadManager( 4496): Download 223 starting
,I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 4496): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 4496): processing updated download 223, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=223:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@432fde20 on behalf of 4496
,V/DownloadManager( 4496): initiating download with UID 10003
,V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4330a7d8 on behalf of 4496
,V/DownloadManager( 4496): processing updated download 223, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=223:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4330cb90 on behalf of 4496
,V/DownloadManager( 4496): processing inserted download 224
V/LFT     ( 4496): isReadyToDownload mId, mStatus=224:190
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4330ece0 on behalf of 4496
,D/DownloadManager( 4496): DB Update : status 192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43310f38 on behalf of 4496
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433136e0 on behalf of 4496
,I/DownloadManager( 4496): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4496): Content-Disposition: null
V/DownloadManager( 4496): Content-Length: -1
I/DownloadManager( 4496): Download 224 starting
V/DownloadManager( 4496): Content-Location: null
V/DownloadManager( 4496): Content-Type: text/plain
V/DownloadManager( 4496): ETag: null
I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 4496): Transfer-Encoding: chunked
,V/DownloadManager( 4496): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4496): Min update size = 16384
V/DownloadManager( 4496): getting filename from uri
I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 4496): in verifySpace, destination: 5, path: 10152015-sms-blacklist.txt, length: 0
V/DownloadManager( 4496): keeping extension
V/DownloadManager( 4496): target file: /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 4496): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433192d0 on behalf of 4496
,D/DownloadManager( 4496): DB Update : title 10152015-sms-blacklist.txt
D/DownloadManager( 4496): DB Update : mimetype text/plain
D/DownloadManager( 4496): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 4496): DB Update : total_bytes -1
,V/DownloadManager( 4496): processing updated download 223, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=223:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4331da10 on behalf of 4496
,I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 4496): processing updated download 224, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=224:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4331faa8 on behalf of 4496
D/LGDRM   (  279): [DRM] Part_DetectType() : Buffer contains XML Prologue
,D/LGDRM   (  279): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4332b4e0 on behalf of 4496
D/DownloadManager( 4496): DB Update : current_bytes 13383
,D/DownloadManager( 4496): DB Update : total_bytes 13383
,V/DownloadManager( 4496): processing updated download 223, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=223:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 4496): notifyThroughDatabase after updateDB  id :  223, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 4496): notifyThroughDatabase start id : 223 name : /cache/10152015-sms-blacklist.txt status : 200
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4332ea80 on behalf of 4496
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43330900 on behalf of 4496
,V/DownloadManager( 4496): processing updated download 224, status: 192
D/DownloadManager( 4496): DB Update : numfailed 0
D/DownloadManager( 4496): DB Update : method 0
D/DownloadManager( 4496): DB Update : lastmod 1452596541555
D/DownloadManager( 4496): DB Update : mimetype text/plain
,D/DownloadManager( 4496): DB Update : _data /cache/10152015-sms-blacklist.txt
D/DownloadManager( 4496): DB Update : status 200
V/LFT     ( 4496): isReadyToDownload mId, mStatus=224:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4496): Download 223 finished with status SUCCESS
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 223; sort is lastmod DESC.
,I/DownloadManager( 4496): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 4496): Content-Disposition: null
V/DownloadManager( 4496): Content-Length: -1
V/DownloadManager( 4496): Content-Location: null
V/DownloadManager( 4496): Content-Type: text/plain
V/DownloadManager( 4496): ETag: null
V/DownloadManager( 4496): Transfer-Encoding: chunked
V/DownloadManager( 4496): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4496): Min update size = 16384
V/DownloadManager( 4496): getting filename from uri
I/DownloadManager( 4496): in verifySpace, destination: 5, path: 08202014-pins.txt, length: 0
,V/DownloadManager( 4496): keeping extension
,V/DownloadManager( 4496): target file: /cache/08202014-pins.txt
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,D/dalvikvm(  967): GC_EXPLICIT freed 746K, 49% free 29707K/57676K, paused 3ms+6ms, total 88ms
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43340450 on behalf of 4928
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43390738 on behalf of 4496
D/DownloadManager( 4496): DB Update : title 08202014-pins.txt
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@4333c7e0 on behalf of 4496
D/DownloadManager( 4496): DB Update : mimetype text/plain
D/DownloadManager( 4496): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 4496): DB Update : total_bytes -1
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 223; sort is lastmod DESC.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43396f40 on behalf of 4928
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@43397998 on behalf of 4496
,I/DownloadManager( 4496): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
W/ContextImpl( 4928): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
V/DownloadManager( 4496): processing updated download 224, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=224:192
,D/DownloadManager( 4496): transferData threadNum : -1
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433a4508 on behalf of 4496
,I/UpdateFetcherService( 4928): Update downloaded, starting installation
,D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
,I/UpdateFetcherService( 4928): Started installation
D/DownloadManager( 4496): transferData threadNum : -1
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433a6e50 on behalf of 4496
D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): DB Update : current_bytes 32768
,D/DownloadManager( 4496): DB Update : deleted 1
V/DownloadManager( 4496): processing updated download 224, status: 192
,V/LFT     ( 4496): isReadyToDownload mId, mStatus=224:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433ab750 on behalf of 4496
,V/DownloadManager( 4496): downloaded 32768 for https://www.gstatic.com/android/config_update/08202014-pins.txt
,D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
,D/DownloadManager( 4496): transferData threadNum : -1
D/DownloadManager( 4496): transferData threadNum : -1
,V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433af398 on behalf of 4496
,D/DownloadManager( 4496): DB Update : current_bytes 39938
,D/DownloadManager( 4496): DB Update : total_bytes 39938
,D/DownloadManager( 4496): deleteFileIfExists() deleting /cache/10152015-sms-metadata.txt
,V/LFT     ( 4496): notifyThroughDatabase after updateDB  id :  224, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 4496): notifyThroughDatabase start id : 224 name : /cache/08202014-pins.txt status : 200
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433b4540 on behalf of 4496
D/DownloadManager( 4496): DB Update : numfailed 0
,D/DownloadManager( 4496): DB Update : method 0
D/DownloadManager( 4496): DB Update : lastmod 1452596541712
D/DownloadManager( 4496): DB Update : mimetype text/plain
D/DownloadManager( 4496): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 4496): DB Update : status 200
,D/DownloadManager( 4496): deleteFileIfExists() deleting /cache/10152015-sms-blacklist.txt
,I/DownloadManager( 4496): Download 224 finished with status SUCCESS
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 224; sort is lastmod DESC.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433bae60 on behalf of 4928
,V/DownloadManager( 4496): processing updated download 224, status: 192
V/LFT     ( 4496): isReadyToDownload mId, mStatus=224:192
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433bc580 on behalf of 4496
,D/DownloadManager( 4496): checkStatusUpdate current status 192 is changed to 200
D/DownloadManager( 4496): checkStatusUpdate return true mID : mStatus = 224 : 200 => 200
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 224; sort is lastmod DESC.
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433bff20 on behalf of 4928
,V/DownloadManager( 4496): DownloadService onDestroy
,W/ContextImpl( 4928): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4928): Update downloaded, starting installation
,I/UpdateFetcherService( 4928): Started installation
,D/DownloadManager( 4496): DB Update : deleted 1
,V/DownloadManager( 4496): DownloadService onCreate
,I/DownloadManager( 4496): in removeSpuriousFiles
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4496): DownloadService onStartCommand
,V/DownloadManager( 4496): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433c4cd8 on behalf of 4496
,V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433c69e0 on behalf of 4496
,I/DownloadManager( 4496): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
,I/DownloadManager( 4496): in removeSpuriousFiles, preserving file /cache/08202014-pins.txt
I/DownloadManager( 4496): in trimDatabase
,V/DownloadManager( 4496): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4496): created cursor android.database.sqlite.SQLiteCursor@433c9908 on behalf of 4496
V/DownloadManager( 4496): processing inserted download 221
,D/DownloadManager( 4496): deleteFileIfExists() deleting /cache/08202014-metadata.txt
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,V/DownloadManager( 4496): processing inserted download 224
,D/DownloadManager( 4496): deleteFileIfExists() deleting /cache/08202014-pins.txt
I/ConfigUpdateInstallReceiver(  967): Not installing, new version is <= current version
,V/DownloadManager( 4496): DownloadService onDestroy
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1158): GC_CONCURRENT freed 2867K, 11% free 25442K/28488K, paused 2ms+3ms, total 41ms
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4616): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Killing 4056:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): Killing 4812:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Killing 4533:com.android.mms/u0a35 (adj 15): empty #17
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/CountryDetector(  967): No listener is left
,I/LocationManagerService(  967): remove 4395fe40
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.451706 Y: -0.415695 Z: 9.798645 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451706 .y:-0.415695 .z:9.798645
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449326 Y: -0.405701 Z: 9.793549 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449326 .y:-0.405701 .z:9.793549
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3679): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
,V/ConfigFetchTask( 1941): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XaOfjsGqKMvwYtjS6uR6VYrrYsx3V8yeV7vVUh64Q9-sTMH2ZUGKwaM_R3TRZZIJTu4QhRilRKVTJHqzAmKCZji0UF-aI1lm3fPmCdYk3jhvx4aVMTZ6yPU1LIlWbYhPZyy_dIvzWToObDu-hb5NtKp3ZE5xkn-A12gjiNlzgGbSYY4HSzXD2dzG1jkVpWyz_v2_3q3Cf6o4_N9ZKMupfdDspsd6KwNE9BzGj8sqr5N7eiXjA
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GoogleURLConnFactory( 1941): Using platform SSLCertificateSocketFactory
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ConfigFetchTask( 1941): updating config table for com.google.android.gms
,I/ConfigFetchService( 1941): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1941): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1941): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1941): fetch service done; releasing wakelock
,I/ConfigFetchService( 1941): self-hosted config:fetch_interval = 43200
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  967): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5077 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/SlideAside( 3545): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
I/SlideAside( 3545): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
E/SlideAside( 3545): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/SlideAside( 3545): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/administrator(  967): Handling package changes for user 0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
D/HyLog   ( 5077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5077): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ConfigFetchService( 1941): stopping self
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4  ( 5077):  AppBoxContentProvider onCreate
,W/AppUp4  ( 5077):  [AppBoxDatabaseHelper] construct
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
,I/AppUp4  ( 5077):  setFingerPrint start
,I/AppUp4  ( 5077):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 5077):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 5077):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5077): AppBoxApplication onCreate()
,D/AppBoxBlacklist( 5077): ConfigFile is not exist. /cust/config/appmanager.cfg
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/PackageParser( 5077): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/AppUp4:Utils( 5077): [getPackageName] uri : package:com.google.android.talk
,D/AppUp4  ( 5077): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5077): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
D/PackageParser( 5077): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
D/administrator(  967): Handling package changes for user 0
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4:CustModeStarterReceiver( 5077): onReceive
,D/AppUp4:CustFacade( 5077): Context : android.app.ReceiverRestrictedContext@430b5160
D/AppUp4:CustFacade( 5077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5077): isOpenOperator : true
,D/AppUp4:CustFacade( 5077): isPhone : true
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  967): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=5112 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5112): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5112): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5112): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/LicenseContentProvider( 5112): start selecting data
,W/BaseRuntimeLoader( 5112): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5112): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5112): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5112): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 5112): simInfo1
,I/VacuumService( 1534): Vacuum at: now=1452596547725 tag=VacuumService
,I/AppUp4:EulaManager( 5077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5077): begin check event
D/AppUp4:Utils( 5077): [getPackageName] uri : package:com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 5077): Event For Nothing, skip.
,I/GoogleURLConnFactory( 1534): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1534): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1534): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1534): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1534): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1534): No account for auth token provided
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5127 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): Killing 4601:com.lge.drmservice/u0a66 (adj 15): empty #17
I/ActivityManager(  967): Killing 4512:com.android.chrome/u0a63 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5127): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5127): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5127): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/libc    (  269): _dns_getaddrinfo: iptype =1
D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4195): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
,V/GmsNetworkLocationProvi( 1426): DISABLE
,I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5127): BUILD Country: EU
,I/SystemConfig( 5127): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4782:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5144 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,I/SystemConfig( 5127): systemFeature RCS result false
,D/SystemConfig( 5127): refreshRcsSupport() :false
D/HyLog   ( 5144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5144): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,I/ActivityManager(  967): Killing 4292:com.lge.wireless_storage/u0a101 (adj 15): empty #17
I/IcingCorporaProvider( 2623): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1941): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/IcingCorporaProvider( 2623): UpdateCorporaTask done [took 29 ms] updated apps [took 29 ms] 
I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5162 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/HyLog   ( 5162): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5162): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5162): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PeopleContactsSync( 1941): CP2 sync disabled
,W/Uploader( 1534): No account for auth token provided
,I/Babel   ( 5162): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5162): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5162): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5162): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5162): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5162): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 5162): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5162): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5162): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5162): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5162): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5162): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5162): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5162): MmsConfig.loadFromResources
,E/Babel   ( 5162): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5162): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5162): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 5077): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 5077): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5077): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5077): onReceive
D/AppUp4:CustFacade( 5077): Context : android.app.ReceiverRestrictedContext@430b5160
D/AppUp4:CustFacade( 5077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5077): isOpenOperator : true
,D/AppUp4:CustFacade( 5077): isPhone : true
I/LicenseContentProvider( 5112): start selecting data
,V/LGRssiData( 5162): [loadRssi] File not exist 
V/LGRssiData( 5162): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5162): [loadFeatureFromXml] *** start feature loading from xml
,D/SIMObserver( 5112): simInfo1
,I/AppUp4:EulaManager( 5077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5077): begin check event
D/AppUp4:Utils( 5077): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5077): Event For Nothing, skip.
,V/TelephonyAutoProfiling( 5162): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5162): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5162): [getValue] FEATURE key : vzw_roaming_state, value : null
,W/Uploader( 1534): No account for auth token provided
,I/IcingCorporaProvider( 2623): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1941): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1941): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  967): Delaying start of: ServiceRecord{44596988 u0 com.google.android.gms/.wearable.service.WearableControlService}
,W/Uploader( 1534):  no longer exists, so no auth token.
,I/Icing   ( 1941): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  967): Killing 4616:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,D/dalvikvm( 1941): GC_CONCURRENT freed 1818K, 21% free 19621K/24832K, paused 2ms+3ms, total 44ms
,I/IcingCorporaProvider( 2623): UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1464): GC_CONCURRENT freed 1539K, 7% free 25439K/27280K, paused 1ms+1ms, total 13ms
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) },
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/dalvikvm(  967): Total arena pages for JIT: 15
,W/PackageSettings(  967): Skipping PackageSetting{43578d70 com.example.hello/10312} due to missing metadata
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1534): onDestroy
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5162): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4863): [423] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4863): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm(  967): GC_CONCURRENT freed 2936K, 49% free 29968K/57676K, paused 4ms+8ms, total 100ms
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9432 usec
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.445984 Y: -0.385529 Z: 9.815079 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445984 .y:-0.385529 .z:9.815079
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.443253 Y: -0.394455 Z: 9.834641 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457672 Y: -0.404434 Z: 9.810226 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.443253 .y:-0.394455 .z:9.834641
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  410): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
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
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.455139 Y: -0.405945 Z: 9.805954 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455139 .y:-0.405945 .z:9.805954
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.444046 Y: -0.410950 Z: 9.824005 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444046 .y:-0.410950 .z:9.824005
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457504 Y: -0.413834 Z: 9.827408 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457504 .y:-0.413834 .z:9.827408
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.455139 Y: -0.408859 Z: 9.820709 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455139 .y:-0.408859 .z:9.820709
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4518edb8)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
,D/SurfaceFlinger(  272): Screen released, type=0 flinger=0xb8781450
,D/qdhwcomposer(  272): hwc_blank: Blanking display: 0
I/WindowManager(  967): No lock screen! windowToken=null
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.444748 Y: -0.407501 Z: 9.806854 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444748 .y:-0.407501 .z:9.806854
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4195): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 4195): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4195): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 4195): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
,V/SRS_Proc(  275): ParamSet string: screen_state=on
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=on
V/voice   (  275): voice_set_parameters: enter: screen_state=on
,V/voice   (  275): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{438773d0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.447235 Y: -0.404099 Z: 9.804550 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447235 .y:-0.404099 .z:9.804550
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherAncestor( 1872): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:2:38
,E/SlideAside( 3545): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,I/SlideAside( 3545): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/UpdateThreadPoolManager( 1872): 2 : This is isUpdating : false
D/WeatherAncestor( 1872): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:2:38
,D/WeatherService( 1872): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1872): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1872): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1158): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1158): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1158): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 231, B = 231,
,D/qdlights( 1158): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1158): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1158): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  272): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 390ms
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1158): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1158): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1158): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1158): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1158): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1158): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1158): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1158): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452596559065, nextTick: 20967, mDrawingTime: 0
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1158): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1158): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1158): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 21, B = 21
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452596559125, nextTick: 20906, mDrawingTime: 1
,D/qdlights( 1158): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 15, B = 15
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=4
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WeatherService( 1872): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:2:39
,D/WeatherService( 1872): 2 : ACTION screen on
,D/WeatherService( 1872): 2 : shouldTimeTickRegistered : false
,D/GsmSST  ( 1451): Emergency Service
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,D/WeatherService( 1872): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:2:39
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.441559 Y: -0.404388 Z: 9.808029 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441559 .y:-0.404388 .z:9.808029
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
,I/LGImmersionVibrator(  967): Vibrator off
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiStateMachine(  967): handleScreenStateChanged: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/UsbSettings( 2548): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2548): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2548): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2548): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/wpa_supplicant( 4195): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 4195): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  275): ParamSet string: screen_state=off
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
D/WifiController(  967): CMD_SCREEN_OFF 
D/WifiController(  967): shouldWifiStayAwake TRUE
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
,I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
,D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1476): setPowerMode; state=2
D/EmotionalLed( 1158): RESTART MSG
D/VolumeVibrator( 1158): clear
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43a63818 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b168b8 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/wpa_supplicant( 4195): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1872): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:2:39
,D/WeatherService( 1872): 2 : ACTION screen off
,D/WeatherService( 1872): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:2:39
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
E/Parcel  (  473): Reading a NULL string not supported here.
,E/Parcel  (  473): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1476): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1476): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/NfcService( 1476): NFC-C OFF
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
,I/Sensors (  410): sns_pwr.c(320):releasing wakelock
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  292): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452596576869939724; DSPS: 5273442; Offset: 1452596415937261502
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452596580047, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452596580052, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452596596871483207; DSPS: 5928852; Offset: 1452596415937279106
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452596616872804552; DSPS: 6584256; Offset: 1452596415937257677
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  967): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/rmt_storage(  484): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb84bb178
I/rmt_storage(  484): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  484): wakelock acquired: 1, error no: 42
,I/rmt_storage(  484): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1202998728)
,I/rmt_storage(  484): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  484): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  484): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1202998728) wakelock released: 1, error no: 0
I/rmt_storage(  484): 
I/rmt_storage(  484): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb84bb178
,E/Diag_Lib(  692): [IMS_FATAL]| 2912 | 697 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452596636874511577; DSPS: 7239672; Offset: 1452596415937255718
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452596640053, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452596640055, nextTick: 59971, mDrawingTime: 3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452596656876191985; DSPS: 7895087; Offset: 1452596415937257659
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452596676878564843; DSPS: 8550524; Offset: 1452596415937280664
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1452596696880415200; DSPS: 9205945; Offset: 1452596415937269449
,I/jxcore-log( 4139): --= Surplus to requirements =--
I/jxcore-log( 4139): 
,I/jxcore-log( 4139): ****TEST TOOK:  ms ****
I/jxcore-log( 4139): 
,I/jxcore-log( 4139): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4139): 
,D/AndroidRuntime( 5441): 
D/AndroidRuntime( 5441): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5441): CheckJNI is OFF
,D/dalvikvm( 5441): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5441): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5441): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5441): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5441): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5441): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5441): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5441): failed to load memtrack module: -2
,D/AndroidRuntime( 5441): Calling main entry com.android.commands.pm.Pm
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  967): Killing 4139:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
I/MDM     (  967):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  967):   Force finishing activity ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4357cac0 stackId=0, 1 tasks}
,V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} (in existing)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4357cac0 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4574e510 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4357cac0 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/WindowState(  967): WIN DEATH: Window{44579038 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  967): Client connection lost with reason: 4
,W/PackageSettings(  967): Skipping PackageSetting{43578d70 com.example.hello/10312} due to missing metadata
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1451): getIsInUseVoLTE : false
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4357cac0 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,D/AppUp4:Utils( 5077): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 5077): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,I/AppUp4  ( 5077):  isExcludedPackage  packagename = com.test.thalitest
,I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5459 uid=10090 gids={50090}
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
E/SlideAside( 3545): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3545): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AppUp4  ( 5077):  isExcludedPackage TRUE : com.test.thalitest
,W/System.err( 2609): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 2609): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
,D/dalvikvm( 2623): GC_EXPLICIT freed 5778K, 27% free 18258K/24832K, paused 2ms+2ms, total 141ms
W/System.err( 2609): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2609): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2609): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2609): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2609): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2609): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2609): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2609): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2609): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2609): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2609): 	at dalvik.system.NativeStart.main(Native Method)
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,W/GeofencerStateMachine( 1426): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  967): GC_EXPLICIT freed 1219K, 49% free 29908K/57672K, paused 3ms+13ms, total 145ms
,D/HyLog   ( 5459): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5459): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5459): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  967): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5485 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/InputMethodManagerService(  967): IME STATUS OFF
,W/Binder  ( 1310): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1310): java.lang.NullPointerException
W/Binder  ( 1310): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1310): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1310): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1310): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4139 uid 10304
D/administrator(  967): Handling package changes for user 0
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/LockScreenSettings( 5459): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1142): createShortcutInfo...
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mms"
,D/HyLog   ( 5485): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5485): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5485): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{43527030 u0 com.lge.launcher2/.Launcher t1} time:279009
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1142): handleShortcutListChanged...
,I/ActivityManager(  967): Killing 4743:com.lge.task/u0a43 (adj 15): empty #17
D/[BNRAppListMgrReceiver]( 5485): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1142): createShortcutInfo...
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
,D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4357cac0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10304 #1
I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
I/InteractionManagerConfigurator(  967): com.test.thalitest isn't inclued in dragdropPackageList
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1142): createShortcutInfo...
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
D/VoicemailCleanupService( 1819): Cleaning up data for package: com.test.thalitest
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5499 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1489): GC_CONCURRENT freed 5651K, 9% free 60778K/66612K, paused 3ms+3ms, total 23ms
,D/dalvikvm( 1489): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/HyLog   ( 5499): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5499): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5499): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 4231K, 10% free 71247K/78436K, paused 24ms, total 24ms
,D/dalvikvm(  967): GC_EXPLICIT freed 699K, 49% free 29932K/57672K, paused 4ms+25ms, total 202ms
,D/KeyguardModel( 1142): handleShortcutListChanged...
,I/LGEmail ( 5499): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
I/ActivityManager(  967): Killing 4712:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4357cac0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/LGEmail ( 5499): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:6.30.33]
E/LGEmail ( 5499): Email Not Started (at LGEmailContentProvider.java query 509)[v:6.30.33]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/AndroidRuntime( 5441): Shutting down VM
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,D/dalvikvm( 5441): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,D/LGEmail ( 5499): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,W/BaseRuntimeLoader( 5499): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5499): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5499): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5499): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageChangeReceiver( 5499): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/PackageIntentReceiver( 2548): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 2548): Receive package name : com.test.thalitest
,D/HideNavigationAppsReceiver( 2548): Delete mPackageMame : com.test.thalitest
,I/ActivityManager(  967): Killing 4692:com.android.calendar/u0a15 (adj 15): empty #17
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/IcingCorporaProvider( 2623): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/ActivityManager(  967): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5521 uid=10073 gids={50073, 3003, 1028, 1015}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4357cac0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5521): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5521): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5521): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@430a2060 time:279306
,D/dalvikvm(  273): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+3ms, total 33ms
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 25ms
,I/IcingCorporaProvider( 2623): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
,D/dalvikvm(  273): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 25ms
,E/SQLiteDatabase( 5521): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5521): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5521): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5521): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5521): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5521): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5521): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5521): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5521): 	at aJh.a(Scopes.java:65)
E/SQLiteDatabase( 5521): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5521): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteDatabase( 5521): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteDatabase( 5521): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5521): 	at aGr.a(GellyInjector.java:117)
E/SQLiteDatabase( 5521): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5521): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5521): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteDatabase( 5521): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteDatabase( 5521): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 5521): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 5521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5521): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5521): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 5521): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5521): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5521): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 5521): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 5521): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 5521): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5521): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 5521): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 5521): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5521): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5521): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5521): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5521): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5521): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5521): 	at aJh.a(Scopes.java:65)
E/SQLiteOpenHelper( 5521): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5521): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteOpenHelper( 5521): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteOpenHelper( 5521): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5521): 	at aGr.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5521): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5521): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5521): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteOpenHelper( 5521): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteOpenHelper( 5521): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 5521): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 5521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5521): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 5521): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 5521): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5521): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5521): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 5521): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 5521): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5521): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5521): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5521): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5521): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5521): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5521): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5521): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5521): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5521): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5521): 	at azE.a(Suppliers.java:125)
E/SQLiteDatabase( 5521): 	at ahj.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5521): threadid=11: thread exiting with uncaught exception (group=0x42064e48)
,I/Process ( 5521): Sending signal. PID: 5521 SIG: 9
E/AndroidRuntime( 5521): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5521): Process: com.google.android.apps.docs, PID: 5521
E/AndroidRuntime( 5521): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 5521): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 5521): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5521): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5521): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5521): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5521): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5521): 	at azE.a(Suppliers.java:125)
E/AndroidRuntime( 5521): 	at ahj.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  967): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  967): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  967): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  967): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  967): 	... 5 more
I/ActivityManager(  967): Process com.google.android.apps.docs (pid 5521) has died.
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4357cac0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
E/SQLiteLog( 2609): (3850) statement aborts at 15: [INSERT INTO t001(f006,f003,f002,f005,f004) VALUES (?,?,?,?,?)] disk I/O error
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/SQLiteDatabase( 2609): Error inserting f006=-1 f003= f002=1452596699766 f005=5521 f004=20
E/SQLiteDatabase( 2609): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2609): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2609): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2609): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2609): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2609): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2609): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2609): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2609): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2609): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2609): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2609): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2609): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2609): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2609): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2609): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)

```
