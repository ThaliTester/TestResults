#### Test 50388019c82294c_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1941): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1941): launchTask
W/dalvikvm( 1941): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1941): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UbvT5-_R7uQtkUQg-bW-cl25aIb3BCw9MrV4H11HWe0IO2yNa4NcM83_HjECm87fLOJnaetgtu2GrYKrEhojsuCy4OFy-03uigdMgPprWaJHNCxQBTtT8pnmN9YO7AVVmsTQVRqr5wyue1RVlYRNO5c3Q8pg_s8q_UpnuNS6B3kB8Pr1j4Gndze0LVYnY2sm1sH2Yp
I/GoogleURLConnFactory( 1941): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1941): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1941): Failed to find package metadata for com.example.hello
D/Vision  ( 1941): No vision deps
D/libc    (  266): _dns_getaddrinfo: iptype =0
D/libc    (  266): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
--------- beginning of /dev/log/system
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1941): CP2 sync disabled
E/DataScheduler( 1941): isDataSchedulerEnabled():false
D/libc    (  266): _dns_getaddrinfo: iptype =0
D/libc    (  266): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1941): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/ConfigFetchService( 1941): fetch service done; releasing wakelock
I/ConfigFetchService( 1941): stopping self
I/dalvikvm( 1941): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1941): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1941): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
W/GAV2    ( 3813): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  965): Killing 3384:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432609d0 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2}
I/ActivityManager(  965): Waited long enough for: ServiceRecord{430fe8f0 u0 com.lge.slideaside/.MainService}
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1941): GC_CONCURRENT freed 1601K, 26% free 18437K/24832K, paused 3ms+6ms, total 45ms
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/Icing   ( 1941): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/Icing   ( 1941): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1941): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 3877): 
D/AndroidRuntime( 3877): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3877): CheckJNI is OFF
D/dalvikvm( 3877): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3877): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3877): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3877): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3877): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 3877): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/dalvikvm( 1158): GC_CONCURRENT freed 1262K, 6% free 25438K/26876K, paused 2ms+1ms, total 86ms
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/memtrack( 3877): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3877): failed to load memtrack module: -2
D/AndroidRuntime( 3877): Calling main entry com.android.commands.am.Am
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3877
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432609d0 stackId=1, 2 tasks}
D/PermissionCache(  269): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (115 us)
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  965): GC_FOR_ALLOC freed 1276K, 12% free 27456K/31020K, paused 66ms, total 66ms
I/dalvikvm-heap(  965): Grow heap (frag case) to 29.809MB for 856096-byte allocation
D/dalvikvm(  965): GC_FOR_ALLOC freed 52K, 12% free 28243K/31860K, paused 63ms, total 63ms
I/dalvikvm-heap(  965): Grow heap (frag case) to 30.578MB for 856096-byte allocation
I/CheckinService( 1941): Done disabling old GoogleServicesFramework version
D/AndroidRuntime( 3877): Shutting down VM
D/UsbSettingsControl( 2506): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2506): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{432609d0 stackId=1, 2 tasks}
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  965): startService SlideAside
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432609d0 stackId=1, 2 tasks}
D/dalvikvm( 3877): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 4ms
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{42805b78 u0 com.example.hello/.MainActivity t3}
I/SlideAside( 3469): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  965): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3910 uid=10311 gids={50311, 3003, 3001, 3002}
I/SlideAside( 3469): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3469): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{42805b78 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/HyLog   ( 3910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3910): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 3910): Binding Chromium to the background looper Looper (main, tid 1) {42812d50}
I/chromium( 3910): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3910): Initializing chromium process, renderers=0
W/chromium( 3910): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3910): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3910): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3910): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3910): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3910): Remote Branch: 
I/Adreno-EGL( 3910): Local Patches: 
I/Adreno-EGL( 3910): Reconstruct Branch: 
I/dalvikvm( 3910): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3910): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3910): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3910): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3910): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3910): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3910): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3910): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3910): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3910): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3910): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3910): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3910): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3910): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3910): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3910): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3910): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3910): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3910): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3910): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 3910): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3910): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3910): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3910): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,D/OpenGLRenderer( 3910): Enabling debug mode 0
,W/AwContents( 3910): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  965): Displayed com.example.hello/.MainActivity: +363ms
,I/ActivityManager( 3910): Timeline: Activity_idle id: android.os.BinderProxy@42814428 time:44204
,I/chromium( 3910): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3910): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1840): 2 : TimeTick Intent has been received, Time(hour:min:sec) 18:43:0
D/WeatherService( 1840): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1840): 2 : SDK version : 19
,D/WeatherQuickCover( 1840): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1840): 2 : Utils getTopActivity com.lge.launcher2 / false
D/Weather.Utils( 1840): 2 : Utils getTopActivity com.lge.easyhome / false
D/WeatherService( 1840): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1840): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1840): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 18:43:0
,D/JsMessageQueue( 3910): Set native->JS mode to OnlineEventsBridgeMode
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1447782180034, nextTick: 59999, mDrawingTime: 0
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1447782180034, nextTick: 59999, mDrawingTime: 0
,D/dalvikvm( 3910): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x428184e8
,D/dalvikvm( 3910): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x428184e8
,D/jxcore_app_log( 3910): JniHelper::setJavaVM(0x416d7838), pthread_self() = 1627132688
,D/JX-Cordova( 3910): jxcore cordova android initializing
,W/jxcore-log( 3910): Initializing JXcore engine
,W/jxcore-log( 3910): JXcore engine is ready
,W/jxcore-log( 3910): Starting JXcore engine
,I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{42805b78 u0 com.example.hello/.MainActivity t3} time:44585
D/ActivityManager(  965): no-history finish of ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{43268978 ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2 f}
,D/UsbSettings( 2506): [AUTORUN] onStop()
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42805b78 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,W/jxcore-log( 3910): Platform android
W/jxcore-log( 3910): 
,W/jxcore-log( 3910): Process ARCH arm
W/jxcore-log( 3910): 
,I/jxcore-log( 3910): JXcore Cordova bridge is ready!
I/jxcore-log( 3910): 
,W/jxcore-log( 3910): JXcore engine is started
,I/chromium( 3910): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 3910): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore-log( 3910): >> LGE-LG-D802
E/jxcore-log( 3910): 
,I/jxcore-log( 3910): Total memory 1943035904
I/jxcore-log( 3910): 
I/jxcore-log( 3910): Free memory 478212096
I/jxcore-log( 3910): 
I/jxcore-log( 3910): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3910): 
,I/jxcore-log( 3910): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3910): 
,I/jxcore-log( 3910): userPath [ 'www' ]
I/jxcore-log( 3910): 
,I/jxcore-log( 3910): Size 1080 1776
I/jxcore-log( 3910): 
,I/jxcore-log( 3910): Screen Brightness 255
I/jxcore-log( 3910): 
,E/jxcore-log( 3910): Dummy Error Log.
E/jxcore-log( 3910): 
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 3910): getBuffer is called!!!!
I/jxcore-log( 3910): 
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3813): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1547): onDestroy
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.572540 Y: -0.388199 Z: 9.730179 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.572540 .y:-0.388199 .z:9.730179
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.557404 Y: -0.349838 Z: 9.730804 
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.551865 Y: -0.349838 Z: 9.746307 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.557404 .y:-0.349838 .z:9.730804
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/ActivityManager(  965): Killing 3345:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432609d0 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42805b78 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@430b5800:true
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  965): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  965): Message: 2
D/WifiService(  965): New client listening to asynchronous messages
,D/WifiService(  965): setWifiEnabled: false pid=3910, uid=10311
E/WifiService(  965): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3910): ****TEST TOOK:  5048  ms ****
I/jxcore-log( 3910): 
,I/jxcore-log( 3910): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3910): 
I/WifiService(  965): setWifiEnabled startWifiDelaySendMsg true
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/AndroidRuntime( 3963): 
D/AndroidRuntime( 3963): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3963): CheckJNI is OFF
,D/dalvikvm( 3963): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3963): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 3963): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3963): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3963): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3963): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 3963): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3963): failed to load memtrack module: -2
,D/AndroidRuntime( 3963): Calling main entry com.android.commands.pm.Pm
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  965): Killing 3910:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  965): Force removing ActivityRecord{42805b78 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{42805b78 u0 com.example.hello/.MainActivity t3 f} (removed from history)
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{42805b78 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  965):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432609d0 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  965): moveHomeStack:
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
,I/WindowState(  965): WIN DEATH: Window{4355c158 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  965): Client connection lost with reason: 4
,W/PackageSettings(  965): Skipping PackageSetting{42cbaf38 com.test.thalitest/10304} due to missing metadata
,V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  965): resumeTopActivityLocked: Resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/UsbSettings( 2506): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/ActivityManager(  965): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,D/KeyguardModel( 1144): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0,
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/PackageManager(  965):   Scheme: "sms"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
E/SlideAside( 3469): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
D/AppUp4:Utils( 3570): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3570): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3469): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
I/AppUp4  ( 3570):  isExcludedPackage  packagename = com.example.hello
V/UsbSettings( 2506): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2506): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2506): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/dalvikvm( 2578): GC_EXPLICIT freed 3727K, 28% free 17915K/24832K, paused 2ms+2ms, total 57ms
D/AppUp4  ( 3570):  isExcludedPackage TRUE : com.example.hello
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  965):   Scheme: "smsto"
W/System.err( 2563): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 2563): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2563): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2563): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2563): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2563): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2563): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2563): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
,W/System.err( 2563): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2563): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2563): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2563): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2563): 	at dalvik.system.NativeStart.main(Native Method)
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/[BNRAppListMgrReceiver]( 3332): android.intent.action.PACKAGE_REMOVED : com.example.hello
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  965): GC_EXPLICIT freed 991K, 11% free 29153K/32700K, paused 3ms+7ms, total 121ms
,D/dalvikvm(  965): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{4327e570 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
,D/administrator(  965): Handling package changes for user 0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageChangeReceiver( 3793): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
,D/VoicemailCleanupService( 1802): Cleaning up data for package: com.example.hello
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
D/PackageIntentReceiver( 2506): Not supported Hotkey customization function 
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,D/HideNavigationAppsReceiver( 2506): Receive package name : com.example.hello
D/HideNavigationAppsReceiver( 2506): Delete mPackageMame : com.example.hello
D/KeyguardModel( 1144): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/ActivityManager(  965): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4003 uid=10090 gids={50090}
,D/BackupManagerService(  965): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  965): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  965): com.example.hello isn't inclued in dragdropPackageList
V/BackupManagerService(  965): removePackageParticipantsLocked: uid=10311 #1
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/IcingCorporaProvider( 2578): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
D/HyLog   ( 4003): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4003): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4003): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
I/ActivityManager(  965): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4016 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/dalvikvm(  270): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,I/LockScreenSettings( 4003): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/dalvikvm( 1144): GC_FOR_ALLOC freed 6618K, 13% free 68670K/78500K, paused 40ms, total 41ms
,D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 14ms
,D/HyLog   ( 4016): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4016): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4016): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1144): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1144): createShortcutInfo...
,D/dalvikvm(  270): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
D/KeyguardModel( 1144): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1144): createShortcutInfo...
D/KeyguardModel( 1144): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1144): createShortcutInfo...
D/KeyguardModel( 1144): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1144): createShortcutInfo...
D/dalvikvm( 1489): GC_CONCURRENT freed 5394K, 9% free 61086K/66672K, paused 2ms+3ms, total 29ms
,D/dalvikvm( 1489): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/KeyguardModel( 1144): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1144): createShortcutInfo...
,D/KeyguardModel( 1144): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1144): createShortcutInfo...
,D/KeyguardModel( 1144): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1144): createShortcutInfo...
D/KeyguardModel( 1144): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1144): createShortcutInfo...
,D/KeyguardModel( 1144): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1144): createShortcutInfo...
,W/ContextImpl( 4016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
D/KeyguardModel( 1144): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1144): createShortcutInfo...
D/dalvikvm(  965): GC_EXPLICIT freed 472K, 11% free 29206K/32700K, paused 5ms+14ms, total 233ms
,D/AndroidRuntime( 3963): Shutting down VM
,D/dalvikvm( 3963): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 1ms+0ms, total 2ms
,D/KeyguardModel( 1144): handleShortcutListChanged...
,D/KeyguardModel( 1144): handleShortcutListChanged...
,I/dalvikvm( 3643): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3643): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3643): VFY: replacing opcode 0x6e at 0x0013
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/ActivityManager(  965): Killing 3290:com.google.android.music:main/u0a107 (adj 15): empty #17
,I/ActivityManager(  965): Killing 2081:android.process.media/u0a23 (adj 15): empty #17
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/NetworkScheduler.SchedulerReceiver( 1547): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1547): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/IcingCorporaProvider( 2578): UpdateCorporaTask done [took 161 ms] updated apps [took 160 ms] 
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
,F/ActivityManager(  965): Service ServiceRecord{4320b220 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{431ad4a8 3290:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  965): Service ServiceRecord{43209c48 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{431ad4a8 3290:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
D/PackageBroadcastService( 1941): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1941): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/WeatherAncestor( 1840): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:43:6
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
D/UpdateThreadPoolManager( 1840): 2 : This is isUpdating : false
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
D/WeatherQuickCover( 1840): 2 : quick cover state : opened : 0
D/WeatherService( 1840): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1840): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1840): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1840): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1840): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1840): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:43:6
D/PackageIntentReceiver( 2506): Not supported Hotkey customization function 
D/WeatherService( 1840): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1840): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1840): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1840): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1840): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  965): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4043 uid=10065 gids={50065, 1028, 4002}
D/WeatherService( 1840): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1840): 2 : requestRefreshAppWidget, isUpdateStart : false
I/LocationSettingsChecker( 1941): Removing dialog suppression flag for package com.example.hello
D/UpdateThreadPoolManager( 1840): 2 : This is isUpdating : false
D/WeatherService( 1840): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1840): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1840): 2 : Map key string is -2
D/lim     ( 1840): 2 : time = 18:43
I/WeatherReflect( 1840): Model Name : LG-D802
D/WeatherTheme( 1840): 2 : Different view - status_min_formatted : 42 != 43
D/WeatherTheme( 1840): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1840): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1840): 2 : Fixed theme : optimus
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/WeatherTheme( 1840): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1840): 2 : quick cover state : opened : 0
D/HyLog   ( 4043): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4043): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4043): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/Weather.Utils( 1840): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1840): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1840): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ActivityManager(  965): Delaying start of: ServiceRecord{431ba068 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
I/ConfigService( 1547): onCreate
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/Documents( 4043): Loading roots for com.android.externalstorage.documents
I/ConfigFetchService( 1941): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/BaseAppContext( 1941): Using Auth Proxy for data requests.
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,D/GOOGLEHELP_CompatibleDatabase( 1941): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1941): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1941): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1941): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1941): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1941): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1941): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1941): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1941): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/ActivityManager(  965): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4060 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  965): Killing 3746:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/GOOGLEHELP_CompatibleDatabase( 1941): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1941): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1941): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1941): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  965): Killing 3762:com.google.android.partnersetup/u0a9 (adj 15): empty #17
W/BaseAppContext( 1941): Using Auth Proxy for data requests.
I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1} time:51291
I/ConfigFetchService( 1941): service connected
,I/Icing   ( 1941): doRemovePackageData com.example.hello
D/HyLog   ( 4060): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4060): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4060): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/PeopleContactsSync( 1941): CP2 sync disabled
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,D/ExternalStorage( 4060): After updating volumes, found 1 active roots
,D/Documents( 4043): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 4043): Loading roots for com.android.providers.downloads.documents
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
I/ActivityManager(  965): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4076 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
D/HyLog   ( 4076): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4076): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4076): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): Killing 3202:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bce840 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43005730 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Delaying start of: ServiceRecord{43167ba0 u0 com.android.providers.downloads/.DownloadService}
,D/Documents( 4043): Loading roots for com.android.providers.media.documents
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@4280ffb0 time:51418
,D/Documents( 4043): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 4043): Update found 7 roots in 220ms
,D/Documents( 4043): Loading roots for com.android.externalstorage.documents
D/Documents( 4043): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4043): Used cached roots for com.android.providers.media.documents
D/Documents( 4043): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4043): Update found 7 roots in 6ms
,W/DriveInitializer( 1941): Background init thread started
,W/DriveInitializer( 1941): Awaiting to be initialized
,E/SQLiteLog( 1941): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock112] disk I/O error
E/DocListDatabase( 1941): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1941): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1941): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1941): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/DocListDatabase( 1941): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/DocListDatabase( 1941): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1941): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/DocListDatabase( 1941): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1941): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1941): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 1941): Background init thread ended
,W/dalvikvm( 1941): threadid=21: thread exiting with uncaught exception (group=0x417d2e48)
,E/SQLiteLog( 1941): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1941): disk I/O error (code 3850)
E/DriveAsyncService( 1941): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1941): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1941): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/DriveAsyncService( 1941): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1941): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1941): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1941): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1941): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1941): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1941): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1941): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1941): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1941): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 1941): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1941): Process: com.google.android.gms, PID: 1941
E/AndroidRuntime( 1941): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1941): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/AndroidRuntime( 1941): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1941): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 1941): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/DropBoxManagerService(  965): Can't write: system_app_crash
E/DropBoxManagerService(  965): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  965): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  965): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  965): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  965): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  965): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  965): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  965): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  965): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  965): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  965): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  965): 	... 5 more
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
,E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
,E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!,
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted,
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
,E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
,E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!,
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted,
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
,E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
,E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
,E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  269): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  269): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  269): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  269): MdpData failed to play
E/qdoverlay(  269): == Dump MdpData start ==
E/qdoverlay(  269): == Dump OvFD fd=56 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  269): mOvData msmfb_overlay_data id=8
E/qdoverlay(  269): data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
E/qdoverlay(  269): == Dump MdpData end ==
E/qdhwcomposer(  269): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  269): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  269): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  269): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  269): hwc_set_primary: display commit fail for 0 dpy!
,V/DownloadManager( 4076): DownloadService onCreate

```
