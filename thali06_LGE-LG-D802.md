#### Test 57348078846ce9d_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/ChimeraCfgMgr( 1976): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1976): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1976): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1976): No vision deps
I/PeopleContactsSync( 1976): CP2 sync disabled
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/dalvikvm( 1976): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
W/dalvikvm( 1976): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1976): VFY: replacing opcode 0x6e at 0x000e
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
W/BaseAppContext( 1976): Using Auth Proxy for data requests.
W/BaseAppContext( 1976): Using Auth Proxy for data requests.
E/DataScheduler( 1976): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1976): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1976): fetch service done; releasing wakelock
I/ConfigFetchService( 1976): stopping self
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1976): Using Auth Proxy for data requests.
W/BaseAppContext( 1976): Using Auth Proxy for data requests.
W/BaseAppContext( 1976): Using Auth Proxy for data requests.
W/BaseAppContext( 1976): Using Auth Proxy for data requests.
,W/GAV2    ( 4095): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  967): Killing 3513:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1976): GC_CONCURRENT freed 1635K, 27% free 18365K/24832K, paused 2ms+4ms, total 33ms
D/ChimeraCfgMgr( 1976): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1976): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4141): 
D/AndroidRuntime( 4141): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4141): CheckJNI is OFF
D/dalvikvm( 4141): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4141): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4141): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4141): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4141): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4141): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/memtrack( 4141): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4141): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1976): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4141): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4141
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (208 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2}
D/Icing   ( 1976): Loaded CLD2 Version V2.0 - 20141016
D/UsbSettingsControl( 2563): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2563): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{432fcb30 stackId=1, 2 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
D/AndroidRuntime( 4141): Shutting down VM
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/dalvikvm( 4141): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 11ms
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4165 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3571): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3571): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3571): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4165): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Icing   ( 1976): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4165): Binding Chromium to the background looper Looper (main, tid 1) {4285e738}
I/chromium( 4165): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4165): Initializing chromium process, renderers=0
W/chromium( 4165): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4165): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4165): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4165): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4165): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4165): Remote Branch: 
I/Adreno-EGL( 4165): Local Patches: 
I/Adreno-EGL( 4165): Reconstruct Branch: 
I/dalvikvm( 4165): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4165): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4165): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4165): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4165): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4165): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4165): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4165): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4165): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4165): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4165): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4165): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4165): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4165): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4165): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4165): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4165): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4165): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4165): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4165): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4165): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4165): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4165): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4165): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4165): Enabling debug mode 0
W/AwContents( 4165): nativeOnDraw failed; clearing to background color.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +358ms
W/AwContents( 4165): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  967): IME STATUS OFF
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/ActivityManager( 4165): Timeline: Activity_idle id: android.os.BinderProxy@4285fff8 time:110734
D/WifiController(  967): battery changed pluggedType: 2
D/JsMessageQueue( 4165): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4165): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428640d8
D/dalvikvm( 4165): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428640d8
D/jxcore_app_log( 4165): JniHelper::setJavaVM(0x4172b838), pthread_self() = 1637407552
I/chromium( 4165): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3} time:111152
D/UsbSettings( 2563): [AUTORUN] onStop()
D/ActivityManager(  967): no-history finish of ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{42dda9d0 ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4165): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4165): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/dalvikvm( 4165): GC_CONCURRENT freed 2681K, 12% free 21971K/24832K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 4165): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4165): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 329K, 11% free 22338K/24832K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 24.029MB for 42652-byte allocation
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 104K, 11% free 22345K/24876K, paused 23ms, total 23ms
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 125K, 11% free 22365K/24876K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 24.106MB for 95956-byte allocation
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 178K, 11% free 22400K/24972K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 24.186MB for 143930-byte allocation
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 253K, 11% free 22447K/25116K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 24.300MB for 215890-byte allocation
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 366K, 12% free 22521K/25328K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 24.475MB for 323830-byte allocation
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 566K, 12% free 22641K/25648K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 24.748MB for 485740-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 862K, 13% free 22818K/26124K, paused 45ms, total 45ms
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 1143K, 12% free 23060K/26124K, paused 23ms, total 24ms
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 189K, 12% free 23020K/26124K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 25.696MB for 1092904-byte allocation
,D/dalvikvm( 4165): GC_CONCURRENT freed 1815K, 14% free 23472K/27192K, paused 3ms+3ms, total 39ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 198K, 15% free 23375K/27192K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 26.564MB for 1639352-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4165): GC_CONCURRENT freed 1863K, 17% free 24002K/28796K, paused 1ms+5ms, total 41ms
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 1022K, 17% free 23965K/28796K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 27.921MB for 2459024-byte allocation
,D/dalvikvm( 4165): GC_CONCURRENT freed 310K, 16% free 26327K/31200K, paused 2ms+3ms, total 36ms
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.573517 Y: -0.353546 Z: 9.824341 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.584610 Y: -0.356873 Z: 9.852097 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.573517 .y:-0.353546 .z:9.824341
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.565063 Y: -0.346466 Z: 9.794235 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565063 .y:-0.346466 .z:9.794235
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 4190K, 20% free 25006K/31200K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4165): Grow heap (frag case) to 30.111MB for 3688532-byte allocation
,D/dalvikvm( 4165): GC_CONCURRENT freed 342K, 19% free 28494K/34804K, paused 2ms+14ms, total 57ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  967): battery changed pluggedType: 2
,D/dalvikvm( 4165): GC_FOR_ALLOC freed 4374K, 25% free 26114K/34804K, paused 27ms, total 27ms
W/jxcore-log( 4165): Initializing JXcore engine
W/jxcore-log( 4165): JXcore engine is ready
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4165): GC_CONCURRENT freed 423K, 17% free 28907K/34804K, paused 3ms+1ms, total 28ms
D/dalvikvm( 4165): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 4165): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/jxcore-log( 4165): Starting JXcore engine
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/jxcore-log( 4165): Platform android
W/jxcore-log( 4165): 
W/jxcore-log( 4165): Process ARCH arm
W/jxcore-log( 4165): 
I/jxcore-log( 4165): JXcore Cordova bridge is ready!
I/jxcore-log( 4165): 
W/jxcore-log( 4165): JXcore engine is started
,I/jxcore-log( 4165): Toggling radios to true
I/jxcore-log( 4165): 
D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43483a38:true
D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  967): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  967): Message: 1
,D/BluetoothManagerService(  967): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  967): New client listening to asynchronous messages
,D/WifiService(  967): setWifiEnabled: true pid=4165, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/BluetoothAdapterService( 1219): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1116271360)( 1219): onCreate
D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43163d50:true
,D/BluetoothAdapterState( 1219): make
I/bluedroid( 1219): init ready=0
D/bt-btif ( 1219): in initialized:0
D/bt-btif ( 1219): root, p->name:Bluedroid, child/value:0x60665288, bytes:160
,D/bt-btif ( 1219): p->used:0, type:0, p->flag:0
,I/BluetoothAdapterState( 1219): Entering OffState
D/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiStateMachine(  967): processMsg: InitialState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): setting operational mode to 1
D/WifiStateMachine(  967): handleMessage: E msg.what=131083
,D/WifiStateMachine(  967): processMsg: InitialState
E/WifiHW  (  967): Wifi MAC Address = 34:fc:ef:de:0a:e2
,I/jxcore-log( 4165): Radios toggled
I/jxcore-log( 4165): 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiService(  967): disconnect pid=4165, uid=10304
,D/WifiService(  967): reconnect pid=4165, uid=10304
E/WifiHW  (  967): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  967): ": cur_etheraddr=34:fc:ef:de:0a:e2
I/jxcore-log( 4165): My device name is: LGE-LG-D802
I/jxcore-log( 4165): 
D/SoftapController(  264): Softap fwReload - Ok
I/bte_conf( 1219): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring down wlan0
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/btif_config_util( 1219): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
W/BT_PROF ( 1219): set profile trace flags 0x0
D/BTIF_CORE( 1219): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 1219):  [BTUI] Load_abtddress
D/bt-btif ( 1219): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
D/bt-btif ( 1219): Got prior random BDA 34:FC:EF:9D:93:0B
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiMonitor(  967): WifiMonitorSingleton gotten
D/lge_bdaddr_loader( 4241): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 4241): [BTUI] bluetooth_load_bdaddress
D/lge_bdaddr_loader( 4241): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
,E/lge_bdaddr_loader( 4241): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4241): [BTUI] bdaddr_loader ::: END
D/WifiStateMachine(  967): setWifiState: enabling
,E/WifiStateMachine(  967): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  967): useWiFiOffloading() : false
E/WifiStateMachine(  967): CONFIG_LGE_WLAN_PATH : true
,D/WifiStateMachine(  967): Supplicant start successful
,V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiMonitor(  967): WifiMonitorSingleton gotten
D/WifiMonitor(  967): startMonitoring(wlan0) with mConnected = false
,D/WifiMonitor(  967): connecting to supplicant
,I/WifiServiceExtension(  967): WIFI_STATE_CHANGED_ACTION [2]
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4245 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,D/wpa_supplicant( 4244): wpa_supplicant v2.1-devel-4.4.2
D/wpa_supplicant( 4244): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4244): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 4244): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4244): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4244): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4244): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4244): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4244): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4244): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4244): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4244): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4244): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4244): disable_scan_offload=1
D/wpa_supplicant( 4244): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4244): update_config=1
D/wpa_supplicant( 4244): device_name='g2_open_com'
D/wpa_supplicant( 4244): manufacturer='LGE'
D/wpa_supplicant( 4244): model_name='LG-D802'
D/wpa_supplicant( 4244): model_number='LG-D802'
D/wpa_supplicant( 4244): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4244): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4244): p2p_disabled=1
D/wpa_supplicant( 4244): p2p_no_group_iface=1
D/wpa_supplicant( 4244): Line: 15 - start of a new network block
D/wpa_supplicant( 4244): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4244): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4244): key_mgmt: 0x2
,D/wpa_supplicant( 4244): priority=1 (0x1)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bluedroid( 1219): get_profile_interface socket
I/GKI_LINUX( 1219): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1219): btif task starting
D/bt-btif ( 1219): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1219): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1219): btif_get_adapter_property 2
I/bt-btif ( 1219): btif_get_adapter_property 1
I/bt-btif ( 1219): execute storage request event : 3
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:2 
,I/bt-btif ( 1219): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 1219): execute storage request event : 3
D/BluetoothAdapterService(1116271360)( 1219): onBind
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1219): in, bd addr:, prop type:1, len:512
I/bt-btif ( 1219): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothManagerService(  967): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  967): Message: 40
,D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  967): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  967): Stored Bluetooth name: Thali Test's G2
,I/bluedroid( 1219): config_hci_snoop_log
D/BluetoothManagerService(  967): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  967): Broadcasting onBluetoothServiceUp() to 8 receivers.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 4245): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4245): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4245): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1219): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BluetoothAdapterService(1116271360)( 1219): Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1219): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterState( 1219): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 1219): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  967): Message: 60
D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  967): Bluetooth State Change Intent: 10 -> 11
,D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(1116271360)( 1219): processStart()
D/wpa_supplicant( 4244): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4244): Priority group 1
D/wpa_supplicant( 4244):    id=0 ssid='NG700'
,D/wpa_supplicant( 4244): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
D/wpa_supplicant( 4244): disable_scan_offload=1
D/wpa_supplicant( 4244): Priority group 1
,D/wpa_supplicant( 4244):    id=0 ssid='NG700'
I/wpa_supplicant( 4244): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4244): nl80211: RFKILL status not available
D/wpa_supplicant( 4244): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4244): nl80211: TDLS supported
D/wpa_supplicant( 4244): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4244): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4244): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4244): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4244): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4244): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4244): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 0a 11
D/BluetoothAdapterService(1116271360)( 1219): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1219): make
,D/BluetoothAdapterService( 1219): setAdapterService(): set to: null
,D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/LGBluetoothServiceAdapter( 1219): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/LGBluetoothServiceAdapter( 1219): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 1219): [BTUI] register observer for LG device name DB
,I/BluetoothBondStateMachine( 1219): StableState(): Entering Off State
,D/PCSuite ( 4245): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,E/BluetoothAdapterService( 1219): File transfer profiels supported!!
,I/ActivityManager(  967): Killing 3405:com.google.android.music:main/u0a107 (adj 15): empty #17
W/BluetoothAdapterService( 1219): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
D/BluetoothHeadset(  967): Proxy object connected
D/BluetoothHeadset( 1448): Proxy object connected
D/BluetoothHeadset( 1448): Proxy object connected
D/BluetoothHeadset( 1448): Proxy object connected
D/BrcmHeadsetService( 1219): Received start request. Starting profile...
I/Brcm_BluetoothHeadsetServiceJni( 1219): classInitNative: succeeds
D/HeadsetStateMachine( 1219): make
E/BluetoothAdapterService( 1219): File transfer profiels supported!!
D/LGBluetoothXmlHandler( 2563): dvice configuraion start
D/LGBluetoothXmlHandler( 2563): startDocument!
D/LGBluetoothXmlHandler( 2563): startElement - elet = Device
W/BluetoothAdapterService( 1219): Starting service com.android.bluetooth.a2dp.A2dpService
E/BluetoothAdapterService( 1219): File transfer profiels supported!!
D/LGBluetoothXmlHandler( 2563): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2563): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2563): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2563): startElement - elet = OPP_DIRECTORY_BLUETOOTH
D/LGBluetoothXmlHandler( 2563): endDocument!
W/BluetoothAdapterService( 1219): Starting service com.android.bluetooth.hid.HidService
E/BluetoothAdapterService( 1219): File transfer profiels supported!!
I/LGBluetoothHeadsetServiceJni( 1219): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 1219): Version 1.5
W/BluetoothAdapterService( 1219): Starting service com.android.bluetooth.hdp.HealthService
I/bluedroid( 1219): get_profile_interface handsfree
I/bt-btif ( 1219): btif_hf_get_interface
I/bt-btif ( 1219): init
D/bt-btif ( 1219): btif_enable_service: current services:0x40
E/BluetoothAdapterService( 1219): File transfer profiels supported!!
V/AudioPolicyService(  270): getOutput()
V/AudioPolicyManagerBase(  270): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  270): getOutput() returns output 2
V/AudioSystem( 1219): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  270): registerClient() client 0xb732c6c8, pid 1219
V/AudioFlinger(  270): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  270): thread 0xb26a7008 type 0 TID 913 waking up
V/AudioFlinger(  270): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  270): thread 0xb253c008 type 0 TID 1002 waking up
W/BluetoothAdapterService( 1219): Starting service com.android.bluetooth.pan.PanService
V/AudioFlinger(  270): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  270): processConfigEvents() remaining events 1
V/AudioFlinger(  270): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  270): processConfigEvents() remaining events 1
V/AudioFlinger(  270): PlaybackThread::audioConfigChanged_l, thread 0xb26a7008, event 0, param 0
V/AudioSystem(  270): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  270): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1219): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1219): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioSystem(  967): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  967): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  270): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem( 1448): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1448): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  270): PlaybackThread::audioConfigChanged_l, thread 0xb253c008, event 0, param 0
V/AudioSystem(  270): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  270): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  270): acquireWakeLock_l() AudioOut_3 status 0
V/AudioSystem(  967): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  967): ioConfigChanged() open,ing already existing output! 3
V/AudioSystem( 1627): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1627): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1219): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1219): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1448): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1448): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1219): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1219): sampleRate 0, channelMask 0x1, format 1
V/AudioTrack( 1219): streamType 8
V/AudioTrack( 1219): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1627): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1627): ioConfigChanged() opening already existing output! 3
V/AudioPolicyService(  270): checkPlayCondition().. streamType = 8
V/AudioPolicyManagerBase(  270): checkPlayCondition()... stream = 8, bResult = 0
V/AudioTrack( 1219): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/HeadsetStateMachine( 1219): Enter Disconnected: -2
D/HeadsetPhoneState( 1219): [BTUI] listenForPhoneState : start = false
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/LGBluetoothHfpManager( 1219): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1219): [BTUI] change sampling rate to 8000 when device is disconnected
E/AudioSystem( 1219): AudioSystem::setParameters()...keyValue bt_samplerate=8000
V/AudioFlinger(  270): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1219
D/BluetoothA2dp(  967): Proxy object connected
V/SRS_Proc(  270): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  270): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  270): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/A2dpService( 1219): Received start request. Starting profile...
E/BluetoothAdapterService( 1219): File transfer profiels supported!!
I/BluetoothA2dpServiceJni( 1219): classInitNative: succeeds
D/A2dpStateMachine( 1219): make
W/BluetoothAdapterService( 1219): Starting service com.android.bluetooth.map.BluetoothMapService
I/bluedroid( 1219): get_profile_interface a2dp
I/bt-btif ( 1219): btif_av_get_interface
I/bt-btif ( 1219): init
I/bt-btif ( 1219): ## A2DP START MEDIA TASK ##
I/GKI_LINUX( 1219): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1219): UIPC_Init
I/bt-btif ( 1219): ### uipc_main_init ###
D/bt-btif ( 1219): UIPC_Open : ch_id 0, p_cback 60afab25
I/bt-btif ( 1219): SETUP CHANNEL SERVER 0
E/BluetoothAdapterService( 1219): File transfer profiels supported!!
I/bt-btif ( 1219): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1219): created socket fd 70
I/bt-btif ( 1219): ADD SERVER FD TO ACTIVE SET 70
I/bt-btif ( 1219): UIPC SEND WAKE UP
I/bt-btif ( 1219): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1219): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1219): btif_enable_service: current services:0x48
D/bt-btif ( 1219): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1219): ## ON A2DP IDLE ##
W/BluetoothAdapterService( 1219): Starting service com.android.bluetooth.gatt.GattService
D/bt-btif ( 1219): UIPC_Close : ch_id 1
I/bt-btif ( 1219): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1219): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1219): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/BluetoothAVRCP1.3ServiceJni( 1219): classInitNativeAVRCP
V/Avrcp   ( 1219): make
D/A2dpStateMachine( 1219): Enter Disconnected: -2
E/BluetoothAdapterService( 1219): File transfer profiels supported!!
W/BluetoothAdapterService( 1219): Starting service com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService( 1219): File transfer profiels supported!!
D/LGBluetoothAvrcpManager( 1219): [BTUI] initAvcrpManager
W/BluetoothAdapterService( 1219): Starting service com.broadcom.bt.service.ftp.FTPService
D/LGBluetoothAvrcpManager( 1219): [BTUI] initPlayStatus() : isMusicActive = false
D/LGBluetoothAvrcpAdapter( 1219): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1219): initNativeAVRCP
I/bluedroid( 1219): get_profile_interface avrcp
I/bt-btif ( 1219): btif_rc_get_interface
I/bt-btif ( 1219): ## init ##
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
V/BluetoothPbapReceiver( 1219): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1219): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1219): ***********state = 11
I/BluetoothHidServiceJni( 1219): classInitNative: succeeds
D/dalvikvm( 1219): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/HidService( 1219): Received start request. Starting profile...
I/bluedroid( 1219): get_profile_interface hidhost
I/bt-btif ( 1219): btif_hh_get_interface
I/bt-btif ( 1219): init
D/bt-btif ( 1219): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
I/BluetoothHealthServiceJni( 1219): classInitNative: succeeds
I/BluetoothAdapterState( 1219): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HealthService( 1219): Received start request. Starting profile...
D/BluetoothPermissionRequest( 2563): onReceive
I/bluedroid( 1219): get_profile_interface health
I/bt-btif ( 1219): btif_hl_get_interface
I/bt-btif ( 1219): init
D/bt-btif ( 1219): Process name (droid.bluetooth)
D/bt-btif ( 1219): btif_hl_soc_thread_init
D/bt-btif ( 1219): create_thread: entered
D/bt-btif ( 1219): create_thread: thread created successfully
I/LGBluetoothHealthServiceJni( 1219): classInitNative: succeeds
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/bt-btif ( 1219): entered btif_hl_select_thread
D/bt-btif ( 1219): btif_hl_select_wakeup_init
D/bt-btif ( 1219): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1219): max_s=79 
D/bt-btif ( 1219): set curr_set = org_set 
D/HeadsetStateMachine( 1219): Proxy object connected
I/BluetoothPanServiceJni( 1219): classInitNative(L105): succeeds
D/BluetoothPan(  967): BluetoothPAN Proxy object connected
D/PanService( 1219): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1219): initializeNative(L110): pan
I/bluedroid( 1219): get_profile_interface pan
D/bt-btif ( 1219): stack_initialized = 0, btpan_cb.enabled:0
D/BluetoothManagerService(  967): Message: 20
D/BluetoothTethering(  967): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4508fa58:true
I/dalvikvm(  967): Jit: resizing JitTable from 8192 to 16384
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
D/LGBluetoothResetSettingReceiver( 2563): [BTUI] Loading JNI Library
D/BluetoothAdapterService( 1219): Profile still not running:com.broadcom.bt.service.sap.SapService
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/HeadsetPhoneState( 1219): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1219): Disconnected process message: 11
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
I/LGBluetoothMapAdapter( 1219): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1219): BluetoothMapBinder()
D/BluetoothMapService( 1219): Received start request. Starting profile...
D/BluetoothMapService( 1219): start()
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
I/BtGatt.JNI( 1219): classInitNative(L685): classInitNative: Success!
D/BtGatt.DebugUtils( 1219): handleDebugAction() action=null
E/BluetoothSettings_JNI( 2563): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/LGBluetoothResetSettingReceiver( 2563): return without doing reset settings.
D/BtGatt.GattService( 1219): Received start request. Starting profile...
D/BtGatt.GattService( 1219): start()
I/bluedroid( 1219): get_profile_interface gatt
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
I/BluetoothSAPServiceJni( 1219): classInitNative(L170): succeeds
F/ActivityManager(  967): Service ServiceRecord{431f7b80 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4333b430 3405:com.google.android.music:main/u0a107} not same as in map: null
D/SapService( 1219): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1219): initializeNative(L175): sap
I/bluedroid( 1219): get_profile_interface sap
I/bt-btif ( 1219): btif_sc_get_interface
I/bt-btif ( 1219): init
D/bt-btif ( 1219): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1219): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1219): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1219): [BTUI] initSapManager
,F/ActivityManager(  967): Service ServiceRecord{431f5620 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4333b430 3405:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/LgeBluetoothSimManager( 1448): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
V/BluetoothFTPServiceJni( 1219): classInitNative
I/BluetoothFTPServiceJni( 1219): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/BluetoothFTPService( 1219): BluetoothFtpBinder()
D/**BluetoothFTPService( 1219): Received start request. Starting profile...
V/BluetoothFTPService( 1219): FTP-Server Service start
D/BluetoothFTPServiceJni( 1219): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1219): get_profile_interface ftp
I/bt-btif ( 1219): btif_fts_get_interface
I/bt-btif ( 1219): init
D/bt-btif ( 1219): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1219): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1219): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1219): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1219): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1219): Profile still not running:com.broadcom.bt.service.sap.SapService
V/BluetoothMapService( 1219): Handler(): got msg=1
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1219): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1219): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1219): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1116271360)( 1219): Message: 1
D/BluetoothAdapterService(1116271360)( 1219): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1219): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1219): All profile services started.
D/BluetoothAdapterState( 1219): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1219): enable 1
I/bt-btif ( 1219): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1219): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/bt_hci_bdroid( 1219): init
I/bt_vendor( 1219): init
I/bt_vnd_conf( 1219): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/GKI_LINUX( 1219): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt_vnd_conf( 1219): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1219): libbt-hci init returns 0
,I/bt_hci_bdroid( 1219): bt_hc_worker_thread started
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/ActivityManager(  967): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4286 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 4286): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4286): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4286): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,D/AuthorizationBluetoothService( 1566): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  967): Killing 2141:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm(  967): GC_CONCURRENT freed 987K, 52% free 29539K/61100K, paused 3ms+6ms, total 98ms
,I/bt_userial_vendor( 1219): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1219): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1219): device fd = 84 open
,D/bt_hwcfg( 1219): Chipset BCM4335A0
,D/bt_hwcfg( 1219): Target name = [BCM4335A0]
D/bt_hwcfg( 1219): Target name = [BCM4335]
I/bt_hwcfg( 1219): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1219): Applying 4335 AXI BRIDGE patch...
,I/bt_hwcfg( 1219): bt vendor lib: set UART baud 4000000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4095): Thread[GAThread,5,main]: No campaign data found.
,D/wpa_supplicant( 4244): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4244): nl80211: driver param='use_multi_chan_concurrent=1'
,D/wpa_supplicant( 4244): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4244): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4244): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4244): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4244): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4244): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4244): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4244): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  967): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  967): sendTetherStateChangedBroadcast 1, 0, 0
,D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2563): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2563): [AUTORUN] sys.usb.state = boot,adb
,D/UsbSettingsReceiver( 2563): [AUTORUN] persist.sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,W/SocketClient(  264): write error (Broken pipe)
I/Config  ( 2563): getOperator() : OPEN
D/UsbSettingsControl( 2563): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2563): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 2563): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 2563): [AUTORUN] setTetherStatus() : status=false
,D/wpa_supplicant( 4244): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4244): wlan0: RSN: flushing PMKID list in the driver
,D/wpa_supplicant( 4244): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4244): wlan0: Setting scan request: 0 sec 100000 usec
,I/bt_hwcfg( 1219): Releasing 4335 AXI BRIDGE lock
,D/wpa_supplicant( 4244): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4244): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4244): WPS: Set UUID for interface wlan0
,D/wpa_supplicant( 4244): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4244): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4244): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4244): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 4244): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4244): Using existing control interface directory.
I/wpa_supplicant( 4244): 0xb8200cc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4244): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4244): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4244): lge_eap_carrier_var_init
D/wpa_supplicant( 4244): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4244): wlan0: Added interface wlan0
D/wpa_supplicant( 4244): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4244): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4244): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4244): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4244): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4244): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4244): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4244): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4244): update_config=1
D/wpa_supplicant( 4244): device_name='Thali Test's G2'
D/wpa_supplicant( 4244): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4244): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4244): persistent_reconnect=1
,D/wpa_supplicant( 4244): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4244): update_config=1
D/wpa_supplicant( 4244): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4244): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
D/wpa_supplicant( 4244): eapol_version=1
D/wpa_supplicant( 4244): ap_scan=1
,D/wpa_supplicant( 4244): fast_reauth=1
D/wpa_supplicant( 4244): p2p_disabled=0
D/wpa_supplicant( 4244): p2p_no_group_iface=0
I/wpa_supplicant( 4244): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4244): nl80211: RFKILL status not available
D/wpa_supplicant( 4244): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4244): nl80211: TDLS supported
D/wpa_supplicant( 4244): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4244): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4244): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4244): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4244): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4244): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8210c28
,D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/wpa_supplicant( 4244): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4244): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4244): nl80211: Use separate P2P group interface
D/wpa_supplicant( 4244): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4244): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4244): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4244): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4244): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4244): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4244): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4244): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 4244): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4244): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4244): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4244): p2p0: State: DISCONNECTED -> INACTIVE
,D/wpa_supplicant( 4244): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4244): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4244): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4244): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4244): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4244): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4244): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4244): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4244): Using existing control interface directory.
I/wpa_supplicant( 4244): 0xb8210098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4244): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4244): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4244): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4244): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4244): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4244): [ITEC] USE NON-INET
I/wpa_supplicant( 4244): [ITEC] Open WIFLUS socket interface - DONE 24
,I/wpa_supplicant( 4244): HY wiflus comm channel initialized
D/wpa_supplicant( 4244): P2P: Own listen channel: 11
,I/wpa_supplicant( 4244): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4244): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4244): P2P: Add operating class 81
D/wpa_supplicant( 4244): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4244): P2P: Add operating class 115
,D/wpa_supplicant( 4244): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 4244): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4244): p2p0: Added interface p2p0
D/wpa_supplicant( 4244): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4244): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 4244): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4244): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4244): wlan0: nl80211: scan request
,D/wpa_supplicant( 4244): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 4244): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4244): random: Got 18/20 bytes from /dev/random
D/wpa_supplicant( 4244): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4244): random: Got 2/2 bytes from /dev/random
D/wpa_supplicant( 4244): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4244): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4244): nl80211: Event message available
D/wpa_supplicant( 4244): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 4244): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  967): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  967): invokeExitMethods: InitialState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  967): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131146
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131144
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): deferMessage: msg=131144
D/WifiStateMachine(  967): handleMessage: X
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
D/WifiStateMachine(  967): handleMessage: E msg.what=131101
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147457
D/WifiStateMachine(  967): processMsg: SupplicantStartingState
D/WifiStateMachine(  967): Supplicant connection established
D/WifiNative-wlan0(  967): doString: DRIVER MACADDR
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER MACADDR'
I/bt_hwcfg( 1219): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1219): Settlement delay -- 100 ms
D/WifiNative-wlan0(  967):    returned Macaddr = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  967): MAC Addr from driver = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  967): setWifiState: enabled
,D/WifiOffDelayIfNotUsed(  967): setPowerSaveActivated(false)
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiActivationWhileCharging(  967): unregister : we don't need to unregister
E/WifiStateMachine(  967): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  967): useWiFiOffloading() : false
E/WifiStateMachine(  967): CONFIG_LGE_WLAN_PATH : true
I/WifiServiceExtension(  967): WIFI_STATE_CHANGED_ACTION [3]
D/WfdService( 1156): Waiting for WifiP2p enabling
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/PCSuite ( 4245): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/WifiServiceExtension(  967): batteryPsActivateMsgHandler : state:0 event:3
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
D/WifiConfigStore(  967): Loading config and enabling all networks
D/WifiNative-wlan0(  967): doString: LIST_NETWORKS
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4244): wlan0: Control interface command 'LIST_NETWORKS'
D/WifiNative-wlan0(  967):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  967): 0	NG700	any	
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 ssid
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 bssid
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'bssid'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 scan_ssid
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_key0
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'wep_key0'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_key1
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'wep_key1'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_key2
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'wep_key2'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4244): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 proto
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 group
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'eap'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'identity'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'password'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 ca_cert
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'subject_match'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 engine_id
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'phase1'
D/WifiConfigStore(  967): ***WAPI : not WAPI
D/WifiNative-wlan0(  967): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4244): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4244): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4244): CTRL_IFACE: Failed to get network variable 'private_key'
E/WifiConfigStore(  967): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  967): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'device_name'='g2_open_com'
D/wpa_supplicant( 4244): device_name='g2_open_com'
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'manufacturer'='LGE'
D/wpa_supplicant( 4244): manufacturer='LGE'
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'model_name'='LG-D802'
D/wpa_supplicant( 4244): model_name='LG-D802'
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'model_number'='LG-D802'
D/wpa_supplicant( 4244): model_number='LG-D802'
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
D/wpa_supplicant( 4244): serial_number='022678fb504e29b0'
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4244): config_methods='physical_display virtual_push_button keypad'
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  967): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=2,j=1
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=2
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=3
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  967): invokeEnterMethods: SupplicantStartedState
D/WifiNative-wlan0(  967): doBoolean: SCAN_INTERVAL 15
W/Settings( 3315): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4244): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 4244): wlan0: Setting scan interval: 15 sec
D/LGDMClient( 2851): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): invokeEnterMethods: DriverStartedStateExt
D/WifiStateMachine(  967): invokeEnterMethods: DriverStartedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setDetailed state, old =IDLE and new state=DISCONNECTED
D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-REMOVE 3
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): Attempting to reconnect to wifi network ..
,D/WifiNative-wlan0(  967): doBoolean: RECONNECT
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 4244): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4244): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiNative-wlan0(  967):    returned wpa_state=SCANNING
D/WifiNative-wlan0(  967): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  967): address=34:fc:ef:de:0a:e2
D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  967): handleScreenStateChanged: true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 4244): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  967):    returned true
,D/WifiP2pService(  967): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up p2p0
D/LGDMClient( 2851): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/WifiMonitor(  967): WifiMonitorSingleton gotten
,D/WifiMonitor(  967): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  967): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  967): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectModeState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131144
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131085
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132106
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  967): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4244): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
E/wpa_supplicant( 4244): nWIFIDualbandAPConnection: 1
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132096
,D/WifiStateMachine(  967): processMsg: DisconnectedState
V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_DISCONNECT_RSSI_LVL : -100
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4244): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
E/wpa_supplicant( 4244): disconnect_rssi_lvl: -100
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-p2p0(  967): doBoolean: SET persistent_reconnect 1
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiP2pService(  967): P2pEnablingState
D/WifiP2pService(  967): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2p socket connection successful
D/WifiP2pService(  967): P2pEnabledState
I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4311 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/WifiP2pService(  967): sending p2p connection changed broadcast
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=143371
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4244): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4244): persistent_reconnect=1
D/wpa_supplicant( 4244): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: SET device_name Thali Test's G2
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4244): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4244): device_name='Thali Test's G2'
D/WifiNative-p2p0(  967):    returned true
D/WifiServiceExtension(  967): postfix byte check : 15
D/WifiNative-p2p0(  967): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4244): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4244): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4244): P2P: New SSID postfix: -Thali Test's G2
,D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4244): p2p0: Control interface command 'SET device_type 10-0050F204-5'
,D/wpa_supplicant( 4244): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4244): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4244): config_methods='virtual_push_button physical_display keypad'
,D/WifiNative-p2p0(  967):    returned true
D/WifiNative-p2p0(  967): doBoolean: P2P_SET conc_pref sta
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4244): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4244): Single channel concurrency preference: sta
D/WifiNative-p2p0(  967):    returned true
,D/WifiNative-p2p0(  967): doString: STATUS
,D/wpa_supplicant( 4244): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiP2pService(  967): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  967): before postfix = Thali Test's G2
,D/WifiP2pService(  967): after postfix = Thali Test's G2
D/WifiNative-p2p0(  967):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  967): p2p_state=IDLE
D/WifiNative-p2p0(  967): wifi_display=1
D/WifiNative-p2p0(  967): ifname=p2p0
D/WifiNative-p2p0(  967): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  967): ifname=wlan0
D/WifiNative-p2p0(  967): address=34:fc:ef:de:0a:e2
I/WfdStateTracker( 1156): handleP2pThisDeviceChanged
,D/WifiNative-p2p0(  967): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4244): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4244): P2P: Stopping find
D/wpa_supplicant( 4244): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4244): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4244): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiNative-p2p0(  967):    returned true
,D/WifiNative-p2p0(  967): doBoolean: P2P_SERVICE_FLUSH
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4244): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  967):    returned true
,D/WifiNative-p2p0(  967): doString: LIST_NETWORKS
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4244): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiNative-p2p0(  967):    returned network id / ssid / bssid / flags
,D/WifiNative-p2p0(  967): doBoolean: SAVE_CONFIG
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4244): p2p0: Control interface command 'SAVE_CONFIG'
,D/wpa_supplicant( 4244): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
D/WifiP2pService(  967): DeviceAddress: 36:fc:ef:de:0a:e2
,D/HyLog   ( 4311): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4311): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4311): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ConfigService( 1566): onDestroy
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4244): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4244): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WifiNative-p2p0(  967):    returned true
,E/WifiServiceExtension(  967): No p2p device connected
,D/LGDMSGCM( 4311): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiP2pService(  967): sending p2p persistent groups changed broadcast
D/WifiP2pService(  967): InactiveState
D/WifiP2pService(  967): InactiveState{ when=-17ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-17ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): DefaultState{ when=-17ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=-17ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-17ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): DefaultState{ when=-17ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 4311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4330 uid=10101 gids={50101, 1028, 1015, 3003}
,I/bt_hwcfg( 1219): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 1219): Setting local bd addr to 34:FC:EF:9D:93:0B
I/ActivityManager(  967): Killing 3844:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/HyLog   ( 4330): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4330): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4330): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/bt_hwcfg( 1219): vendor lib fwcfg completed
,I/bt-btif ( 1219): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/        ( 1219): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1219): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1219): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1219): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1219): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1219): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1219): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1219): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1219): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 1219): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1219): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1219): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1219): BTE_InitTraceLevels -- TRC_SDP
I/        ( 1219): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1219): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1219): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1219): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1219): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1219): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
D/bt-btif ( 1219): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1219): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1219): bta_dm_sm_execute event:0x0
I/bt-btif ( 1219): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1219): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1219): bta_sys_sm_execute state:1, event:0x1
,I/bt-btif ( 1219): bta_sys_hw_evt_enabled for 0
,I/Wireless_Storage( 4330): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
,V/[BNRBootReceiver]( 4060): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BNRAndroBeam( 4060): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/bt-btif ( 1219):  bta_sys_hw_btm_cback was called with parameter: 0
I/bt-btif ( 1219): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1219):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1219):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1219): ##################################
D/bt-btif ( 1219): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1219): ##################################
D/bt-btif ( 1219): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1219): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b4f4c5 
I/bt-smp  ( 1219): SMP_Register state=0
E/bt-btm  ( 1219): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b4f4c5 
D/bt-btif ( 1219): bta_gattc_register state 0
D/bt-btif ( 1219): bta_gattc_enable
I/bt-att  ( 1219): GATT_Register
D/bt-att  ( 1219): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1219): allocated gatt_if=3
D/bt-btif ( 1219): bta_dm_gattc_callback event = 0
D/bt-btif ( 1219): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1219): GATT_StartIf gatt_if=3
D/bt-att  ( 1219): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 1219): gatt_find_the_connected_bda found=0 found_idx=7
I/ActivityManager(  967): Killing 3315:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/bt-btif ( 1219): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:1 
,D/bt-btif ( 1219): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1219): bta_dm_sm_execute event:0x2
D/bt-btif ( 1219): BTA is generating EIR
D/bt-btif ( 1219): getAccess buffer->st_uid:1000 buffer->st_gid:1028
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 1219): Adding UUID=0x110C into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1219): FTP SERVER en
D/bt-btif ( 1219): bta_av_co_audio_init
D/bt-btif ( 1219): bta_av_co_audio_init: 0
D/bt-btif ( 1219): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1219): bta_av_co_audio_init
D/bt-btif ( 1219): bta_av_co_audio_init: 1
D/bt-btif ( 1219): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1219): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:4
I/bt-btif ( 1219): A2D_AddRecord uuid: 110a
,I/bt-a2d  ( 1219): A2D_AddRecord uuid: 110a
E/bt-btif ( 1219): Adding UUID=0x110A i
I/bt-btif ( 1219): Adding UUID=0x110A into EIR
D/bt-btif ( 1219): in add:1
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
D/bt-btif ( 1219): rc_acp_handle:0 idx:1
D/bt-btif ( 1219): create 0
D/bt-btif ( 1219): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1219): reg_audio: 0x1
D/bt-btif ( 1219): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1219): bta_ag_scb_alloc 1
D/bt-btif ( 1219): bta_ag_scb_alloc 1
D/bt-btif ( 1219): AG evt (hdl 0x0001): State 0, Event 0x05
I/bt-btif ( 1219): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-btif ( 1219): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:5
D/bt-btif ( 1219): bta_ag_add_record uuid: 1112
D/bt-btif ( 1219): bta_ag_add_record uuid: 1112
D/bt-btif ( 1219): Remote device:80:01:84:8a:b3:68, size:18
I/bt-btif ( 1219): Adding UUID=0x1112 into EIR
D/bt-btif ( 1219): BTA is generating EIR
D/bt-btif ( 1219): Remote device:58:3f:54:73:64:c0, size:18
I/bt-btif ( 1219): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1219): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1219): bta_ag_add_record uuid: 111f
I/bt-btif ( 1219): Adding UUID=0x111F into EIR
D/bt-btif ( 1219): Adding UUID=0x111F into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1219): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1219): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1219): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1219): Remote device:7c:f9:0e:5
D/bt-btif ( 1219): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_reco05, size:18
D/bt-btif ( 1219): SDP_CreateRecord ok, num_reco05, size:18
I/bt-btif ( 1219): Adding UUID=0x1106 into EIR
D/bt-btif ( 1219): Remote device:50:2e:6
D/bt-btif ( 1219): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1219): Remote device:7c:f9:0e:37:96:ab, size:18
I/bt-btif ( 1219): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1219): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1219): FTS:  SDP Registered (handle 0x00010006)
D/bt-btif ( 1219): bta_fts_ci_resume status:1
I/bt-btif ( 1219): bta_fts_ci_resume status:1
D/bt-btif ( 1219): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1219): SDP_CreateRecord ok, num_recoa0, size:18
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:8
I/bt-btif ( 1219): Adding UUID=0x112D into EIR
D/bt-btif ( 1219): BTA is generating EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1219): bte_sap_evt: event=0
I/bt-btif ( 1219): bta_dm_sm_execute event:0x9
D/bt-btif ( 1219): bta_gattc_register state 2
I/bt-att  ( 1219): GATT_Register
D/bt-att  ( 1219): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 1219): allocated gatt_if=4
D/bt-btif ( 1219): bta_hh_gattc_callback event = 0
D/bt-btif ( 1219): bta_hh_gattc_callback event = 0
I/bt-att  ( 1219): GATT_StartIf gatt_if=4
D/bt-att  ( 1219): Remote device:90:e7:c4:f6:69:77, size:1
D/bt-btif ( 1219): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-att  ( 1219): gatt_find_the_connected_bda found=0 found_idx=7
,D/bt-btif ( 1219): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1219): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1219): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1219): Remote device:, size:128
E/bt-btif ( 1219): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
E/bt-btif ( 1219): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
,D/bt-btif ( 1219): out
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:1 
I/bt-btif ( 1219): bta_dm_sm_execute event:0x9
D/bt-btif ( 1219): bta_dm_sm_execute event:0x9
I/bt-btif ( 1219): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1219): in, bd addr:, prop type:16, len:4
E/bt-btif ( 1219): Unknow prop type:16
,I/bt-btif ( 1219): btif_dm_get_adapter_property: type=0x10
D/bt-btif ( 1219): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1219): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1219): btif_storage_get_adapter_property service_mask:0x120148
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:3 devicemode 0
,D/bt-btif ( 1219): btif_storage_get_adapter_property property->type:3 devicemode 0
I/bt-btif ( 1219): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  967): Bluetooth Adapter name changed to Thali Test's G2
D/BluetoothManagerService(  967): Stored Bluetooth name: Thali Test's G2
,E/BluetoothAdapterProperties( 1219): Property change not handled in Java land:16
,I/bt-btif ( 1219): btif_storage_load_bonded_devices: 2 bonded devices found
D/bt-btif ( 1219): in, bd addr:e0:db:10:14:e2:c0, prop type:1, len:249
D/bt-btif ( 1219): in, bd addr:e0:db:10:14:e2:c0, prop type:10, len:249
D/bt-btif ( 1219): in, bd addr:e0:db:10:14:e2:c0, prop type:4, len:4
D/bt-btif ( 1219): in, bd addr:e0:db:10:14:e2:c0, prop type:5, len:4
D/bt-btif ( 1219): in, bd addr:e0:db:10:14:e2:c0, prop type:3, len:512
,I/bt-btif ( 1219): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1219): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1219): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1219): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1219): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1219): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1219): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1219): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
D/bt-btif ( 1219): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512
,I/bt-btif ( 1219): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1219): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
I/LGRemoteDevicePropertySetting( 1219): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1219): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1219): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
E/bt_hwcfg( 1219): hw_sco_config...
,E/bt_hwcfg( 1219): SCO PCM configure {0, 4, 0, 0, 0}
I/bt-btif ( 1219): HC lib lpm enable=1 return 0
I/bt-btif ( 1219): BTA_BrcmInit
,E/bt-gki  ( 1219): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
D/IOP_DB_BT( 1219): db_open: file /etc/bluetooth/iop_bt.db
,I/bt-btif ( 1219): HC lpm_result_cb 1
D/IOP_DB_BT( 1219): db_open: db_open : handle 1623444012l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1219): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1219): db_query: result 1
I/        ( 1219): iop_db_open: iop_db_open status 0
D/bt-btif ( 1219): btsock initializing...
D/bt-btif ( 1219): in initialized:1
D/bt-btif ( 1219): ts[7].used:1
D/bt-btif ( 1219): ts[6].used:0
,D/bt-btif ( 1219): alloc_thread_slot ret:6
D/bt-btif ( 1219): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1219): h:6, thread id:1626602760
I/bt-btif ( 1219): BTA_JvEnable
D/bt-btif ( 1219): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1219): unhandled event:0, slot id:0
D/bt-btif ( 1219): btsock successfully initialized
D/bt-btif ( 1219): jni_initialized = 1, btpan_cb.enabled:0
D/bt-btif ( 1219): Enabling PAN....
I/bt-btif ( 1219): bta_pan_co_init
D/bt-btif ( 1219): local_role:3
D/bt-btif ( 1219): btpan_role:0x3
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1219): Adding UUID=0x1116 into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1219): Adding UUID=0x1115 into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1219): Adding UUID=0x1116 into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1219): Removing UUID=0x1117 from EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1219): Adding UUID=0x1115 into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bte_conf( 1219): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1219): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
I/bt-btif ( 1219): bta_dm_sm_execute event:0x31
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:10
I/bte_conf( 1219): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1219): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bt-btif ( 1219): btif_dm_load_local_oob prop
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1219): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
D/bt-btif ( 1219): bte did registered::handle: 0x10009
I/bt-btif ( 1219): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1219): adapter_state_change_callback: Status is: 1
D/bt-btif ( 1219): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 1219): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1219): btif_av_state_idle_handler devicemode: 0
D/bt-btif ( 1219): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 1219): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 1219): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
I/bt-btif ( 1219): File Transfer: Enable Complete
I/bt-btif ( 1219): HAL bt_fts_callbacks->operation_cmpl_cb
,D/BluetoothFTPServiceJni( 1219): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1219): onFtpServerEnabled: /storage
D/bt-btif ( 1219): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1219): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
D/bt-btif ( 1219): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
D/bt-btif ( 1219): btif_hh_upstreams_evt--Loading added devices
D/bt-btif ( 1219): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1219): Remote device:f8:95:c7:87:3c:51, size:18
,D/bt-btif ( 1219): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1219): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1219): Remote device:14:b4:84:21:3b:49, size:18
D/BluetoothAdapterState( 1219): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1219): ScanMode =  20
D/BluetoothAdapterProperties( 1219): State =  11
D/BluetoothAdapterProperties( 1219): mDiscoverableTimeout =  120
I/bt-btif ( 1219): btif_set_adapter_property type: 7, len 4, 0x428f82f8
I/bt-btif ( 1219): set property scan mode : 1
,I/bt-btif ( 1219): bta_dm_sm_execute event:0x3
I/bt-btif ( 1219): btif_in_storage_request_copy_cb
I/bt-btif ( 1219): btif_set_adapter_property type: 9, len 4, 0x428f8350
I/bt-btif ( 1219): btif_in_storage_request_copy_cb
D/bt-btif ( 1219): btif_in_storage_request_copy_cb
D/bt-btif ( 1219): Remote device:58:3f:54:73:64:c0, size:18
I/BluetoothAdapterState( 1219): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 1219): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  967): Message: 60
,D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  967): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan(  967): onBluetoothStateChange(on) call bindService
D/bt-btif ( 1219): Remote device:10:d3:8a:fb:85:d4, size:18
V/BluetoothAdapterService( 1219): startPbapService
D/bt-btif ( 1219): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1219): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1219): Remote device:f8:cf:c5:d9:e5:61, size:18
,D/bt-btif ( 1219): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1219): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1219): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1219): Remote device:50:2e:6c:ac:21:50, size:18
D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
D/bt-btif ( 1219): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1219): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1219): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1219): Remote device:f8:95:c7:87:85:54, size:18
,D/bt-btif ( 1219): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1219): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1219): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1219): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1219): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1219): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1219): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1219): Remote device:, size:18
E/bt-btif ( 1219): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
,D/bt-btif ( 1219): BTA_PAN_ENABLE_EVT
D/bt-btif ( 1219): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1219): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/bt-btif ( 1219): execute storage request event : 2
I/bt-btif ( 1219): type: 7, len 4, 0x60aa503a
D/bt-btif ( 1219): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1219): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
D/BluetoothA2dp(  967): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  967): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
I/bt-btif ( 1219): execute storage request event : 2
I/bt-btif ( 1219): type: 9, len 4, 0x60aa5086
D/bt-btif ( 1219): in, bd addr:, prop type:9, len:4
I/bt-btif ( 1219): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothManagerService(  967): Bluetooth State Change Intent: 11 -> 12
I/BluetoothAdapterState( 1219): Entering On State
,D/LGBluetoothServiceAdapter( 1219): [BTUI] OnState
,D/BluetoothAdapterService( 1219): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4288f300
V/BluetoothPbapService( 1219): Pbap Service onCreate
V/BluetoothPbapService( 1219): Starting PBAP service
D/LGBluetoothServiceAdapter( 1219): [BTUI]         global_name: Thali Test's G2
D/LGBluetoothServiceAdapter( 1219): [BTUI]         local_name: Thali Test's G2
D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LGBluetoothAPIService( 1156): Message: 1
,D/LGBluetoothAPIService( 1156): MESSAGE_BOOT_COMPLETED
,W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
D/BluetoothAdapterService(1116271360)( 1219): Quiet mode Enabled = false
D/BluetoothAdapterService(1116271360)( 1219): Initiate auto connection on BT on...
D/BluetoothAdapterService( 1219): [BTUI] autoConnect() : not allowed
I/LGBluetoothAPIService( 1156): [BTUI] LGBluetoothAPIService Binding Success
D/bt_h4   ( 1219): vendor lib postload completed
I/bt-btif ( 1219): HC postload_cb 0
D/BluetoothAdapterService(1116271360)( 1219): Get Bonded Devices being called
D/LGBluetoothPbapAdapter( 1219): [BTUI] getInstance : create
V/BluetoothPbapService( 1219): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1219): state: 12
D/BluetoothMapService( 1219): onReceive
D/BluetoothMapService( 1219): STATE_ON
D/BluetoothManagerService(  967): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  967): Message: 40
D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothPbapService( 1219): Handler(): got msg=1
V/BluetoothPbapService( 1219): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 1219): Pbap Service initSocket
D/LGBluetoothAPIServer( 1219): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1219): [BTUI] onBind()
D/LGBluetoothAPIService( 1156): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1156): Message: 100
D/LGBluetoothAPIService( 1156): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothMapService( 1219): Handler(): got msg=1
D/BluetoothMapService( 1219): Map Service startRfcommSocketListener
D/BluetoothMapService( 1219): Map Service initSocket
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1219): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothPbapReceiver( 1219): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1219): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1219): ***********state = 12
E/BluetoothServiceJni( 1219): SOCK FLAG = 1 ***********************
D/bt-btif ( 1219): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
,D/bt-btif ( 1219): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1219): BTA_JvCreateRecordByUser
D/bt-btif ( 1219): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1219): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1219): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1219): Adding UUID=0x112F into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000094 04071440
D/bt-btif ( 1219): PBS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1219): BTA_JvRfcommStartServer
D/bt-btif ( 1219): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1219): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
W/BluetoothAdapter( 1219): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/LGBluetoothServiceAdapter( 1219): [BTUI] createSocketChannel FD=90 mFd=0
V/BluetoothPbapService( 1219): Succeed to create listening socket 
V/BluetoothPbapService( 1219): Accepting socket connection...
E/BluetoothServiceJni( 1219): SOCK FLAG = 1 ***********************
D/bt-btif ( 1219): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1219): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1219): BTA_JvCreateRecordByUser
D/bt-btif ( 1219): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1219): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1219): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1219): Adding UUID=0x1132 into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1219): MAPSS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1219): BTA_JvRfcommStartServer
D/bt-btif ( 1219): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1219): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1219): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothMapService( 1219): Succeed to create listening socket 
D/BluetoothMapService( 1219): Accepting socket connection...
D/LocalBluetoothProfileManager( 2563): Adding local A2DP profile
,D/BluetoothManagerService(  967): Message: 30
,D/LocalBluetoothProfileManager( 2563): Adding local HEADSET profile
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/BluetoothManagerService(  967): Message: 30
,D/BluetoothManagerService(  967): Message: 30
,D/BluetoothManagerService(  967): Message: 30
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
,W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
D/LocalBluetoothProfileManager( 2563): Adding local MAP profile
D/BluetoothMap( 2563): Create BluetoothMap proxy object
,D/BluetoothManagerService(  967): Message: 30
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
,D/BluetoothManagerService(  967): Message: 30
,V/BluetoothPbapService( 1219): Pbap Service onBind
,D/LocalBluetoothProfileManager( 2563): LocalBluetoothProfileManager construction complete
,D/LGBluetoothUserBindClient( 2563): [BTUI] initUserBindClient
W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
,W/ContextImpl( 2563): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 2563): finishStartingService: stopping service
D/BluetoothA2dp( 2563): Proxy object connected
D/A2dpProfile( 2563): Bluetooth service connected
D/BluetoothHeadset( 2563): Proxy object connected
D/HeadsetProfile( 2563): Bluetooth service connected
D/BluetoothInputDevice( 2563): Proxy object connected
D/HidProfile( 2563): Bluetooth service connected
D/BluetoothPan( 2563): BluetoothPAN Proxy object connected
D/PanProfile( 2563): Bluetooth service connected
D/BluetoothMap( 2563): Proxy object connected
D/MapProfile( 2563): Bluetooth service connected
D/BluetoothMap( 2563): getConnectedDevices()
V/BluetoothMapService( 1219): getConnectedDevices()
D/BluetoothPbap( 2563): Proxy object connected
D/PbapServerProfile( 2563): Bluetooth service connected
D/LGBluetoothUserBindClient( 2563): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2563): onReceive
D/LGBluetoothFeatureConfig( 2563): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2563): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2563): return without doing reset settings.
V/BluetoothOppReceiver( 1219): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1219): [BTUI] startOppService()
,V/BluetoothOppManager( 1219): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 1219): isPrivacyLogsEnabled : true
,V/BtOppService( 1219): onCreate
,D/LGBluetoothOppAdapter( 1219): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothOppNotification( 1219): send message
,V/BtOppService( 1219): Starting RfcommListener
,D/BluetoothOppPreference( 1219): Dumping Names:  
D/BluetoothOppPreference( 1219): {}
D/BluetoothOppPreference( 1219): Dumping Channels:  
D/BluetoothOppPreference( 1219): {}
,V/BtOppService( 1219): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BtOppService( 1219): onStartCommand
,V/BluetoothOppNotification( 1219): new notify threadi!
,V/BtOppService( 1219): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BtOppService( 1219): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1219): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 1219): send delay message
,V/BtOppService( 1219): start RfcommListener
,V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@4292a0e8 on behalf of 
V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@42929e80 on behalf of 
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 1219): RfcommListener started
V/BtOppRfcommListener( 1219): Starting RFCOMM listener....
V/BtOppService( 1219): ContentObserver received notification
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BtOppService( 1219): ContentObserver received notification
V/BtOppService( 1219): pendingUpdate is true keepUpdateThread is false sListenStarted is true
W/BluetoothAdapter( 1219): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@4292d0f0 on behalf of 
,E/BluetoothServiceJni( 1219): SOCK FLAG = 0 ***********************
D/bt-btif ( 1219): btsock_rfc_listen, service_name:OBEX Object Push
D/bt-btif ( 1219): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1219): BTA_JvCreateRecordByUser
D/bt-btif ( 1219): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1219): name:OBEX Object Push, scn:12
D/bt-btif ( 1219): scn 12, service name OBEX Object Push
D/bt-sdp  ( 1219): SDP_CreateRecord ok, num_records:13
I/bt-btif ( 1219): Adding UUID=0x1105 into EIR
D/bt-btif ( 1219): BTA is generating EIR
I/bt-btif ( 1219): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1219): BTA_JvRfcommStartServer
D/bt-btif ( 1219): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
,D/bt-btif ( 1219): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
D/LGBluetoothServiceAdapter( 1219): [BTUI] createSocketChannel FD=95 mFd=92
V/BtOppRfcommListener( 1219): Started RFCOMM listener....
I/BtOppRfcommListener( 1219): Accept thread started.
V/BtOppRfcommListener( 1219): Accepting connection...
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@4292f450 on behalf of 
,V/BluetoothOppNotification( 1219): update too frequent, put in queue
,V/BluetoothOppNotification( 1219): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BtOppService( 1219): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/AuthorizationBluetoothService( 1566): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1566): Proximity feature is not enabled.
,V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@429318a0 on behalf of 
,V/BluetoothOppNotification( 1219): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1219): outbound notification was removed.
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@42933618 on behalf of 
,V/BluetoothOppNotification( 1219): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1219): inbound notification was removed.
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@42934d00 on behalf of 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4244): EAPOL: disable timer tick
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4244): EAPOL: disable timer tick
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/BluetoothOppNotification( 1219): new notify threadi!
,V/BluetoothOppNotification( 1219): send delay message
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@42936e70 on behalf of 
,V/BluetoothOppNotification( 1219): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@42938aa8 on behalf of 
,V/BluetoothOppNotification( 1219): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1219): outbound notification was removed.
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@4293a638 on behalf of 
,V/BluetoothOppNotification( 1219): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1219): inbound notification was removed.
,V/BluetoothOppProvider( 1219): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1219): created cursor android.database.sqlite.SQLiteCursor@4293bbe0 on behalf of 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/AudioFlinger(  270): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  270): releaseWakeLock_l() AudioOut_2
V/AudioFlinger(  270): thread 0xb253c008 type 0 TID 1002 going to sleep
,V/AudioFlinger(  270): thread 0xb26a7008 type 0 TID 913 going to sleep
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 4244): nl80211: Event message available
D/wpa_supplicant( 4244): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4244): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4244): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4244): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 4244): nl80211: Survey data missing
D/wpa_supplicant( 4244): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 4244): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wlan0: BSS: Add new id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wlan0: BSS: Add new id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wlan0: BSS: Add new id 4 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wlan0: BSS: Add new id 5 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 4244): wlan0: New scan results available
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4244): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4244): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 4244): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 4244): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4244): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4244): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4244): WPS: AP[3] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4244): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 4244): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-56 wps
D/wpa_supplicant( 4244): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4244): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-55 wps
D/wpa_supplicant( 4244): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4244): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4244): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4244): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4244): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4244): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4244): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4244): wlan0: [MDM], lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 4244): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb82025a8  current_ssid=0x0
D/wpa_supplicant( 4244): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC
E/wpa_supplicant( 4244): USIM:  scard_init function
D/wpa_supplicant( 4244): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 4244): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4244): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4244): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 4244): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 4244): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 4244): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4244): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4244): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4244): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4244): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4244): wlan0: Cancelling scan request
D/wpa_supplicant( 4244): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4244): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 4244): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 4244): RSN: PMKSA cache search - network_ctx=0xb82025a8 try_opportunistic=0
D/wpa_supplicant( 4244): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4244): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 4244): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 4244): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4244): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4244): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4244): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 4244): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 4244): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4244): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 4244): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 4244): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4244): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4244): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4244): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4244): nl80211: Unsubscribe mgmt frames handle 0xb8201590 (mode change)
D/wpa_supplicant( 4244): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/w,pa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4244): nl80211: Register frame type=0xd0 nl_handle=0xb8201590
D/wpa_supplicant( 4244): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4244): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 4244):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244):   * freq=2412
D/wpa_supplicant( 4244):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4244):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4244):   * Auth Type 0
D/wpa_supplicant( 4244):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 00:37:b7:9d:3e:73]
D/wpa_supplicant( 4244): nl80211: Connect request send successfully
D/wpa_supplicant( 4244): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4244): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4244): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4244): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4244): RSN: Ignored PMKID candidate without preauth flag
D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/Wif,iNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 4244): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 4244): nl80211: Event message available
,D/wpa_supplicant( 4244): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4244): nl80211: Connect event
D/wpa_supplicant( 4244): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4244): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4244): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4244): wlan0: Association info event
D/wpa_supplicant( 4244): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4244): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4244): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4244): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4244): wlan0: freq=2412 MHz
D/wpa_supplicant( 4244): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4244): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4244): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4244): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4244): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4244): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): scard is not null..
D/wpa_supplicant( 4244): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4244): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4244): TDLS: Remove peers on association
D/wpa_supplicant( 4244): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4244): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4244): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4244): EAPOL: enable timer tick
D/wpa_supplicant( 4244): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4244): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4244): wlan0: Cancelling scan request
D/wpa_supplicant( 4244): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 4244): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4244): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 27 88 92 0c bb 0f 60 f4 97 1d 55 a9 13 ef 74 ...
D/wpa_supplicant( 4244): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4244): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4244): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4244): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4244): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4244):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4244):   key_nonce - hexdump(len=32): 27 88 92 0c bb 0f 60 f4 97 1d 55 a9 13 ef 74 68 91 e7 bc c3 0e a0 c9 da e9 24 7d 90 b2 30 4e c7
D/wpa_supplicant( 4244):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4244):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4244):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4244):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4244): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 27 88 92 0c bb 0f 60 f4 97 1d 55 a9 13 ef 74 ...
D/wpa_supplicant( 4244): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4244): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 4244): Get randomness: len=32 entropy=7
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 4244): WPA: Renewed SNonce - hexdump(len=32): a2 ea 25 0c e4 5c eb df 94 de 21 48 e0 9b ac d9 fe 6e be 3b e1 98 1e 59 e2 7c bd e9 ce 43 a2 15
D/wpa_supplicant( 4244): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): WPA: Nonce1 - hexdump(len=32): a2 ea 25 0c e4 5c eb df 94 de 21 48 e0 9b ac d9 fe 6e be 3b e1 98 1e 59 e2 7c bd e9 ce 43 a2 15
D/wpa_supplicant( 4244): WPA: Nonce2 - hexdump(len=32): 27 88 92 0c bb 0f 60 f4 97 1d 55 a9 13 ef 74 68 91 e7 bc c3 0e a0 c9 da e9 24 7d 90 b2 30 4e c7
D/wpa_supplicant( 4244): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4244): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4244): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4244): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4244): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4244): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4244): WPA: Derived Key MIC - hexdump(len=16): 60 5d 33 b0 05 e1 45 9f fa 80 fa ca ab 0b 6e 02
D/wpa_supplicant( 4244): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 a2 ea 25 0c e4 5c eb df 94 de 21 48 e0 9b ac ...
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 4244): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4244): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 27 88 92 0c bb 0f 60 f4 97 1d 55 a9 13 ef 74 ...
D/wpa_supplicant( 4244): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4244): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4244): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4244): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4244):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4244):   key_nonce - hexdump(len=32): 27 88 92 0c bb 0f 60 f4 97 1d 55 a9 13 ef 74 68 91 e7 bc c3 0e a0 c9 da e9 24 7d 90 b2 30 4e c7
D/wpa_supplicant( 4244):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4244):   key_rsc - hexdump(len=8): 87 11 00 00 00 00 00 00
D/wpa_supplicant( 4244):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 4244):   key_mic - hexdump(len=16): ff 1c c8 ee 62 ff ae e6 3e c5 a9 b8 fb 17 02 0e
D/wpa_supplicant( 4244): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 27 88 92 0c bb 0f 60 f4 97 1d 55 a9 13 ef 74 ...
D/wpa_supplicant( 4244): RSN: encrypted key data - hexdump(len=56): 86 a4 82 0b 97 ef e1 c6 ff 62 7a 21 6c 1e f1 5b fb 5e 6e 7f d3 a6 42 76 72 3a 36 81 2c 77 40 d6 ...
D/wpa_supplicant( 4244): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4244): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4244): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4244): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 66 e2 ...
D/wpa_supplicant( 4244): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 4244): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4244): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4244): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4244): WPA: Derived Key MIC - hexdump(len=16): 51 9b a5 07 5d 4f 93 54 72 49 bf 63 6d b7 06 0a
D/wpa_supplicant( 4244): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4244): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8201c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4244):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4244): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 4244): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4244): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 4244): WPA: RSC - hexdump(len=6): 87 11 00 00 00 00
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f7303a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4244):    broadcast key
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
I/wpa_supplicant( 4244): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4244): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4244): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4244): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 4244): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4244): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4244): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4244): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4244): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4244): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4244): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4244): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 4244): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4244): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4244): EAPOL authentication completed successfully
D/wpa_supplicant( 4244): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4244): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4244): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
,D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4244): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4244): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  967):    returned bssid=c0:ff:d4:d3:aa:48
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
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-22ms what=147462 obj=android.net.wifi.StateChangeResult@432cb268 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/DhcpStateMachine(  967): StoppedState
D/DhcpStateMachine(  967): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): ObtainingIpState{ when=-19ms what=147462 obj=android.net.wifi.StateChangeResult@44b33198 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-20ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-7ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 4244): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4244): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,D/WifiStateMachine(  967): handleMessage: E msg.what=196612
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-12ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/WifiService(  967): New client listening to asynchronous messages
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4381 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,D/HyLog   ( 4381): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4381): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4381): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4381): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4381): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4381): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4381): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4381): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4381): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4381): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4381): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4381): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager(  967): Killing 3999:com.android.defcontainer/u0a4 (adj 15): empty #17
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4399 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 4244): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
,D/WifiStateMachine(  967): handleMessage: X
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43449978 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43449978 target=com.android.internal.util.StateMachine$SmHandler }
,D/HyLog   ( 4399): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4399): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4399): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Babel   ( 4399): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4399): MmsConfig.loadMmsSettings
,I/MediaCodecList( 4399): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 4399): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4399): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4399): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 4399): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4399): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 4399): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4399): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4399): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4399): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4399): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4399): MmsConfig.loadFromResources
,E/Babel   ( 4399): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4399): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 4399): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4399): [loadRssi] File not exist 
,V/LGRssiData( 4399): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4399): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4399): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4399): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4399): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  967): Killing 4033:com.google.android.partnersetup/u0a9 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 4244): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4244): EAPOL: disable timer tick
,I/jxcore-log( 4165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4165): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-1ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  967): handleMessage: X
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
V/LgDhcpStateMachineHelper(  967): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: true
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4244): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4244): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4244): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/DhcpStateMachine(  967): RunningState
,D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
,D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  967): send additional Connectivity Action
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/WifiStateMachine(  967): handleMessage: X
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/jxcore-log( 4165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 4165): 
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=0 connState=2
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  409): Reading a NULL string not supported here.
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,D/QRemote ( 4381): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4381): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/QRemote ( 4381): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4381): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/        (  264): RouteController
,I/PCSuite ( 4245): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4245): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,D/QRemote ( 4381): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4381): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/QRemote ( 4381): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4381): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,V/        (  264): RouteController
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/QCNEA   (  409): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  409): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  409): |CAC| updateNetCfgInfo
V/QCNEA   (  409): |CAC| *********************************************
V/QCNEA   (  409): |CAC|                   Netconfig               
V/QCNEA   (  409): |CAC| *********************************************
V/QCNEA   (  409): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  409): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  409): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  409): |CAC| 	NetConfig: ip4        =192.168.1.155
V/QCNEA   (  409): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  409): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  409): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  409): |CAC| *********************************************
D/QCNEA   (  409): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  409): |CAC| net type = 1
V/QCNEA   (  409): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  409): |CAC| Received ssid= NG700
V/QCNEA   (  409): |CAC| 	ssid           =NG700
V/QCNEA   (  409): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  409): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  409): |CAC| *********************************************
D/QCNEA   (  409): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  409): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  409): |CAC| dispatchNetCfg: updating:0xb80f38dc
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/jxcore-log( 4165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4165): 
,I/jxcore-log( 4165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4165): 
,I/jxcore-log( 4165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4165): 
,I/jxcore-log( 4165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4165): 
,I/jxcore-log( 4165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4165): 
,I/jxcore-log( 4165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4165): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GpsLocationProvider(  967): NTP server returned: 1453903036876 (Wed Jan 27 14:57:16 CET 2016) reference: 120257 certainty: 27 system time offset: 2873
E/LocSvc_afw(  967): V/Entering int loc_inject_time(GpsUtcTime, int64_t, int) line 446 
E/LocSvc_eng(  967): I/===> int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1910 
E/LocSvc_eng(  967): V/time: 1453903036876
E/LocSvc_eng(  967):   timeReference: 120257
E/LocSvc_eng(  967):   uncertainty: 27
E/LocSvc_utils_q(  967): D/msg_q_snd: Sending message with handle = 0x68666B90
E/LocSvc_utils_ll(  967): D/linked_list_add: Adding to list data_obj = 0x68666B90
,E/LocSvc_utils_q(  967): D/msg_q_snd: Finished Sending message with handle = 0x68666B90
E/LocSvc_eng(  967): V/Exiting int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1917 0
E/LocSvc_afw(  967): V/Exiting int loc_inject_time(GpsUtcTime, int64_t, int) line 452 0
E/LocSvc_utils_ll(  967): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  967): D/msg_q_rcv: Received message 0x68666B90 rv = 0
E/LocSvc_eng(  967): V/time: 1453903036876
E/LocSvc_eng(  967):   timeReference: 120257
E/LocSvc_eng(  967):   uncertainty: 27
E/LocSvc_ApiV02(  967): V/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):436]: uncertainty = 27
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 56, req_id 56 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 56
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=56, len = 16
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 56, len = 16
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=56 buf_len=7 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 56 is a resp size = 4
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 56, client cookie ptr = 0x6603fa98
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 56 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 56 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 4 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_MsgTask(  967): D/MsgTask::loop() 26 listening ...
,E/LocSvc_utils_q(  967): D/msg_q_rcv: Waiting on message
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4244): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4244): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/GpsLocationProvider(  967): calling native_inject_xtra_data
,E/LocSvc_afw(  967): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  967): V/length: 59574
E/LocSvc_eng(  967):   data: 0x68740008
E/LocSvc_utils_q(  967): D/msg_q_snd: Sending message with handle = 0x68666760
E/LocSvc_utils_ll(  967): D/linked_list_add: Adding to list data_obj = 0x68666760
E/LocSvc_utils_q(  967): D/msg_q_snd: Finished Sending message with handle = 0x68666760
E/LocSvc_afw(  967): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
E/LocSvc_utils_ll(  967): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  967): D/msg_q_rcv: Received message 0x68666760 rv = 0
E/LocSvc_eng(  967): V/length: 59574
E/LocSvc_eng(  967):   data: 0x68740008
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 59574
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/59, len = 1024, total injected = 0
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/59, len = 1024, total injected = 1024
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
,E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/59, len = 1024, total injected = 2048
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/59, len = 1024, total injected = 3072
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/59, len = 1024, total injected = 4096
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/59, len = 1024, total injected = 5120
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/59, len = 1024, total injected = 6144
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/59, len = 1024, total injected = 7168
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/59, len = 1024, total injected = 8192
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/59, len = 1024, total injected = 9216
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/59, len = 1024, total injected = 10240
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/59, len = 1024, total injected = 11264
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/L,ocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/59, len = 1024, total injected = 12288
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/59, len = 1024, total injected = 13312
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/59, len = 1024, total injected = 14336
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/59, len = 1024, total injected = 15360
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/WifiStateMachine(  967): processMsg: DefaultState
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/59, len = 1024, total injected = 16384
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  967): send additional Connectivity Action
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/59, len = 1024, total injected = 17408
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/59, len = 1024, total injected = 18432
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/59, len = 1024, total injected = 19456
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/59, len = 1024, total injected = 20480
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/59, len = 1024, total injected = 21504
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/59, len = 1024, total injected = 22528
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/59, len = 1024, total injected = 23552
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/59, len = 1024, total injected = 24576
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/59, len = 1024, total injected = 25600
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/59, len = 1024, total injected = 26624
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/59, len = 1024, total injected = 27648
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSv,c_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/59, len = 1024, total injected = 28672
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/59, len = 1024, total injected = 29696
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967):, V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/59, len = 1024, total injected = 30720
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/59, len = 1024, total injected = 31744
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/59, len = 1024, total injected = 32768
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/59, len = 1024, total injected = 33792
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/59, len = 1024, total injected = 34816
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/59, len = 1024, total injected = 35840
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/59, len = 1024, total injected = 36864
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/59, len = 1024, total injected = 37888
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/59, len = 1024, total injected = 38912
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/59, len = 1024, total injected = 39936
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/59, len = 1024, total injected = 40960
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/59, len = 1024, total injected = 41984
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/59, len = 1024, total injected = 43008
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/59, len = 1024, total injected = 44032
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/59, len = 1024, total injected = 45056
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/59, len = 1024, total injected = 46080
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/59, len = 1024, total injected = 47104
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/59, len = 1024, total injected = 48128
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/59, len = 1024, total injected = 49152
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/59, len = 1024, total injected = 50176
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/59, len = 1024, total injected = 51200
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/59, len = 1024, total injected = 52224
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/59, len = 1024, total injected = 53248
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/59, len = 1024, total injected = 54272
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/59, len = 1024, total injected = 55296
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/59, len = 1024, total injected = 56320
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/59, len = 1024, total injected = 57344
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58368
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 58/59, len = 1024, total injected = 58368
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 103, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 59392
E/LocSvc_ApiV02(  967): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 59/59, len = 182, total injected = 59392
E/LocSvc_api_v02(  967): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  967): V/loc_sync_select_ind:356]: client handle 0x6603fa00, ind_id 53, req_id 53 
E/LocSvc_api_v02(  967): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  967): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  967): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  967): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  967): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  967): V/convertQmiResponseToLocStatus:681]: result = 0, error = 104, status = 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  967): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x6603fa00
,E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  967): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  967): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x6603fa00, resp id = 53, client cookie ptr = 0x6603fa98
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:165]: received indication, handle = 0x6603fa00 ind_id = 53 
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  967): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  967): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  967): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  967): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  967): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 59574
E/LocSvc_MsgTask(  967): D/MsgTask::loop() 27 listening ...
,E/LocSvc_utils_q(  967): D/msg_q_rcv: Waiting on message
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  967): MasterInitialState.processMessage what=3
,D/        (  967): Setting time of day to sec=1453903039
,W/        (  967): Unable to set rtc to 1453903039: Invalid argument
,D/WeatherService( 1831): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:57:19
,I/SecureClockService( 1156): Intent.ACTION_TIME_CHANGED 
,I/MusicWidget( 2107): intentReceiver onReceive() action::android.intent.action.TIME_SET
,I/[LGHome]LGCalendarIcon( 1487): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 27
,I/MusicWidget( 2107): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2107): beingMusicWidget_Lock() result::false
,I/MusicWidget( 2107): beingMusicWidget_Quick() result::false
I/MusicWidget( 2107): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2107): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2107): beingMusicWidget_4x1() result::true
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_SET
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453903039049, nextTick: 40983, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453903039050, nextTick: 40983, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,I/MusicWidget( 2107): performUpdate()_4x1
,I/MusicWidget( 2107): status::mounted
,I/MusicWidget( 2107): defaultAppWidget()_4x1
,I/MusicWidget( 2107): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
,I/MusicWidget( 2107): setDefaultViewLayoutId()_4x1
,I/[LGHome]LGCalendarIcon( 1487): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 27
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/MusicWidget( 2107): appWidgetViewUpdate()_4x1
,I/MusicWidget( 2107): linkButtons()_4x1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WeatherService( 1831): 2 : requestRefreshAppWidget, isUpdateStart : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/UpdateThreadPoolManager( 1831): 2 : This is isUpdating : false
,D/WeatherService( 1831): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1831): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1831): 2 : Map key string is -2
,D/lim     ( 1831): 2 : time = 14:57
I/WeatherReflect( 1831): Model Name : LG-D802
D/WeatherTheme( 1831): 2 : Different view - status_min_formatted : 55 != 57
,D/WeatherTheme( 1831): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1831): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1831): 2 : Fixed theme : optimus
,D/WeatherTheme( 1831): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1831): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:57:19
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/QCNEA   (  409): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/MusicWidget( 2107): pushUpdate()_4x1
,I/MusicWidget( 2107): performViewUpdater handleMessage() msg.what::3
,I/MusicWidget( 2107): beingMusicWidget_Quick() result::false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3659): onReceive
,D/AppUp4:CustFacade( 3659): Context : android.app.ReceiverRestrictedContext@4287f3e0
,D/AppUp4:CustFacade( 3659): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3659): isOpenOperator : true
,D/AppUp4:CustFacade( 3659): isPhone : true
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
,I/AppUp4:EulaManager( 3659): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3659): begin check event
,I/AppUp4:CustModeStarterReceiver( 3659): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3659): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3659): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3659): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3659): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3659): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4539 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/GoogleURLConnFactory( 1566): Using platform SSLCertificateSocketFactory
,D/HyLog   ( 4539): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4539): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4539): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4553 uid=10063 gids={50063, 3003, 1028, 1015}
,D/HyLog   ( 4553): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4553): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4553): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.562408 Y: -0.336044 Z: 9.814514 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.592804 Y: -0.350159 Z: 9.799332 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.562408 .y:-0.336044 .z:9.814514
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/MusicWidget( 2107): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2107): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2107): beingMusicWidget_Lock() result::false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.564896 Y: -0.348923 Z: 9.812210 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.564896 .y:-0.348923 .z:9.812210
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/DelayedSyncController( 4553): Delaying sync.
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,E/Auth.Api.Credentials( 1976): [CredentialSyncAdapter] Unknown sync event.
,W/DriveInitializer( 1976): Background init thread started
,V/DownloadManager( 4539): DownloadService onCreate
,I/DownloadManager( 4539): in removeSpuriousFiles
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/dalvikvm( 1566): GC_EXPLICIT freed 1301K, 28% free 17887K/24832K, paused 2ms+6ms, total 117ms
,D/dalvikvm(  967): GC_EXPLICIT freed 2432K, 52% free 29633K/61100K, paused 2ms+7ms, total 119ms
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428a8a18 on behalf of 4539
D/EAS     ( 4076): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4076): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
W/DriveInitializer( 1976): Background init thread ended
,I/DownloadManager( 4539): in trimDatabase
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428aa730 on behalf of 4539
,I/ConfigService( 1566): onCreate
,I/ConfigFetchService( 1976): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1976): running network task: configservice_periodic
,D/eas_req ( 4076): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4539): DownloadService onStartCommand
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/dalvikvm( 1976): GC_CONCURRENT freed 1161K, 23% free 19210K/24832K, paused 3ms+3ms, total 40ms
,V/DownloadManager( 4539): DownloadService onStartCommand
,E/WakeLock( 1976): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1976): launchTask
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428ae220 on behalf of 4539
,I/LgeMiscReceiver( 3823): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3823): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3823): networkInfo.isConnected() = false
,W/linker  ( 4076): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 4076): JNI_OnLoad
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4076): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4076): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428b2278 on behalf of 4539
,I/dalvikvm( 4076): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4076): register_HtmlEditor, Success
,D/HtmlEditor( 4076): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4076): register_HtmlEditorTimer, Success
,D/HtmlEditor( 4076): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
I/ConfigFetchService( 1976): service connected
D/HtmlEditor( 4076): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4076): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4076): register_HtmlEditorFont, Success
,D/HtmlEditor( 4076): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4076): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4076): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4076): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4076): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4076): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4076): JNI_OnLoad Success
,V/DownloadManager( 4539): DownloadService onDestroy
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4597 uid=10052 gids={50052, 3003}
,I/HubEmail( 4076): JNI_OnLoad()
,I/HubEmail( 4076): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4076): registerNatives()
I/HubEmail( 4076): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4076): registerNativeMethods()
,I/HubEmail( 4076): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/HyLog   ( 4597): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4597): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4597): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConfigFetchService( 1976): ConfigApi connection successful.
,W/Settings( 4076): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  967): Killing 3681:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4597): [loadRssi] File not exist 
V/LGRssiData( 4597): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4597): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4597): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4597): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4597): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4597): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 4597): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4597): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4597): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4597): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4615 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  967): Killing 4095:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,D/dalvikvm(  268): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 1ms+2ms, total 23ms
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,D/HyLog   ( 4615): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4615): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4615): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1976): Checking schedule, now: 1453903039721 next: 1453536628759
,I/CheckinService( 1976): active receiver: enabled
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
,I/CheckinService( 1976): Preparing to send checkin request
,I/EventLogService( 1976): Accumulating logs since 1453901975549
,D/DrmBroadcastReceiver( 4615): Receive CONNECTIVITY_ACTION
,D/LGDMClient( 2851): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/DelayedSyncController( 4553): Delaying sync.
,D/LGDMSGCM( 4311): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2851): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4330): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4330): CONNECT : WIFI_CONNECT
I/LGDMClient( 2851): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4632 uid=10104 gids={50104, 3003, 1028, 1015}
E/LGDMClient( 2851): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2851): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2851): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LGDMClient( 2851): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/ActivityManager(  967): Killing 1877:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
D/HyLog   ( 4632): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4632): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4632): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/Finsky  ( 3738): [336] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3738): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  967): Killing 4060:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,W/GAV2    ( 4632): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,E/Ads     ( 1976): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/CheckinRequestBuilder( 1976): Checkin reason type: 8 attempt count: 1
,D/WifiService(  967): New client listening to asynchronous messages
,V/WebViewChromium( 4632): Binding Chromium to the main looper Looper (main, tid 1) {4285e320}
,I/chromium( 4632): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4632): Initializing chromium process, renderers=0
E/ActivityThread( 1976): Failed to find provider info for com.google.android.wearable.settings
,W/chromium( 4632): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4632): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4632): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4632): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4632): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4632): Remote Branch: 
I/Adreno-EGL( 4632): Local Patches: 
I/Adreno-EGL( 4632): Reconstruct Branch: 
,I/NSApplication( 4632): Starting up...
,I/ActivityManager(  967): Killing 4286:com.lge.settings.easy/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/dalvikvm( 3713): GC_FOR_ALLOC freed 751K, 16% free 20909K/24832K, paused 16ms, total 17ms
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/dalvikvm-heap( 3713): Grow heap (frag case) to 26.501MB for 4099024-byte allocation
,W/BaseRuntimeLoader( 1976): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1976): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1976): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1976): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/iu.SyncManager( 1976): SYNC; picasa accounts
,D/dalvikvm( 3713): GC_CONCURRENT freed 37K, 14% free 24895K/28836K, paused 2ms+1ms, total 22ms
,D/NetworkLogImpl( 1976): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1976): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/iu.UploadsManager( 1976): num queued entries: 0
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/iu.UploadsManager( 1976): num updated entries: 0
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.SyncManager( 1976): NEXT; no task
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4244): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4244): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  967): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4681 uid=10010 gids={50010, 3003, 1028, 4002}
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,I/GcmGroups( 1976): Failed to subscribe to group.
I/GcmGroups( 1976): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1976): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1976): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1976): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1976): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1976): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1976): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1976): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1976): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1976): 	at android.os.Looper.loop(Looper.java:136)
I/GcmGroups( 1976): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GcmGroups( 1976): Groups upload failed, retrying in 24000:00:00
D/HyLog   ( 4681): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4681): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4681): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/OpenGL ES Test( 4681): getCurrentLocale == en_US
E/OpenGL ES Test( 4681): localeFound retString == en_US
E/OpenGL ES Test( 4681): getCurrentLocale == en_US
,E/OpenGL ES Test( 4681): localeFound retString == en_US
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ALBootInit( 4681): ====action==>android.intent.action.TIME_SET
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ALBootInit( 4681): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4681): [setNextAlert] start
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,D/Alarms  ( 4681): [setNextAlert] (1)
,D/Alarms  ( 4681):  minTime  = 0
,D/Alarms  ( 4681):  -- OK multi -- 0
E/jeny.kim( 4681): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4681): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4681): setStatusBarIcon : false
,D/Alarms  ( 4681): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,D/WorldClockReceiver( 4681): ====action==>android.intent.action.TIME_SET
,E/OpenGL ES Test( 4681): getCurrentLocale == en_US
E/OpenGL ES Test( 4681): localeFound retString == en_US
E/OpenGL ES Test( 4681): getCurrentLocale == en_US
,E/OpenGL ES Test( 4681): localeFound retString == en_US
E/OpenGL ES Test( 4681): getCurrentLocale == en_US
,E/OpenGL ES Test( 4681): localeFound retString == en_US
E/OpenGL ES Test( 4681): getCurrentLocale == en_US
,E/OpenGL ES Test( 4681): localeFound retString == en_US
,E/OpenGL ES Test( 4681): isExistDatabase = false
,W/CheckinRequestBuilder( 1976): awaiting user notification for token
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43278b10: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/CommonUtil( 4681): BUILD Country: EU
E/OpenGL ES Test( 4681): loadMapCityData() -- S
E/OpenGL ES Test( 4681): getCurrentLocale == en_US
E/OpenGL ES Test( 4681): localeFound retString == en_US
E/OpenGL ES Test( 4681): getCurrentLocale == en_US
E/OpenGL ES Test( 4681): localeFound retString == en_US
,E/OpenGL ES Test( 4681): loadMapCityData() - While S
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4696 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4696): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4696): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4696): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4696): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4696): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4696): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4696): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4696): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4696): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4696): install
,I/MultiDex( 4696): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,E/OpenGL ES Test( 4681): loadMapCityData() - While E
E/OpenGL ES Test( 4681): loadMapCityData() -- E
,E/OpenGL ES Test( 4681): getCurrentLocale == en_US
E/OpenGL ES Test( 4681): localeFound retString == en_US
E/OpenGL ES Test( 4681): getCurrentLocale == en_US
,E/OpenGL ES Test( 4681): localeFound retString == en_US
,I/MultiDex( 4696): loading existing secondary dex files
,I/MultiDex( 4696): load found 3 secondary dex files
,I/MultiDex( 4696): install done
,D/dalvikvm(  967): GC_EXPLICIT freed 1518K, 52% free 29599K/61100K, paused 2ms+6ms, total 83ms
,E/OpenGL ES Test( 4681): [updateWidgetDST] backup_cityInfoList is null >>>>
,I/ActivityManager(  967): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4710 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4399:com.google.android.talk/u0a77 (adj 15): empty #17
D/dalvikvm( 4696): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4696): VFY: unable to resolve instance field 61
D/dalvikvm( 4696): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4696): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4696): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4696): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4696): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4696): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4696): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4696): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4696): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
D/dalvikvm( 4696): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428671d0
D/dalvikvm( 4696): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428671d0
D/dalvikvm( 4696): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428671d0, skipping init
D/dalvikvm( 4696): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428671d0
D/dalvikvm( 4696): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428671d0
,V/JNIHelp ( 4696): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4710): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4710): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4710): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4696): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428671d0
D/dalvikvm( 4696): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428671d0
D/dalvikvm( 4696): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428671d0
,D/dalvikvm( 4696): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428671d0
,I/Config  ( 4710): LGCalendar ver.4.2.6
,I/Config  ( 4710): start check model
I/Config  ( 4710): start check native_ca
,E/Config  ( 4710): [setCountryAndOperator] Operator=OPEN, Country=EU
,I/ProviderInstaller( 4696): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4696): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4696): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4696): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4696): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4696): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4696): VFY: replacing opcode 0x6e at 0x0201
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/QSEECOMAPI: (  270): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  270): App is not loaded in QSEE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/dalvikvm( 4696): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.a.a
W/dalvikvm( 4696): VFY: unable to resolve virtual method 299: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4696): VFY: replacing opcode 0x6e at 0x0013
,D/CalendarWidget( 4710): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,I/InitNotificationRingtoneService( 4710): Start InitializeAlertRingtoneService.onHandleIntent
,D/QSEECOMAPI: (  270): Loaded image: APP id = 2
,D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1eb9000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1eb9000
,W/dalvikvm( 4696): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4696): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/ActivityManager(  967): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4740 uid=10016 gids={50016, 3003, 1028, 1015}
,W/dalvikvm( 4696): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 4696): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4696): VFY: unable to resolve virtual method 727: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4696): VFY: replacing opcode 0x6e at 0x00bb
D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,I/InitNotificationRingtoneService( 4710): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 4710): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 4710): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 4710): End InitializeAlertRingtoneService.onHandleIntent
D/HyLog   ( 4740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4740): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/dalvikvm( 1566): GC_EXPLICIT freed 1179K, 28% free 17894K/24832K, paused 1ms+3ms, total 36ms
,I/GoogleURLConnFactory( 4696): Using platform SSLCertificateSocketFactory
,D/GCM     ( 1566): Connected
D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CalendarProvider2( 4740): Created com.android.providers.calendar.CalendarAlarmManager@428809d0(com.android.providers.calendar.CalendarProvider2@42877938)
D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,E/DataScheduler( 4696): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=4054074299
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ActivityManager(  967): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4762 uid=10043 gids={50043, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4245:com.lge.sync/1000 (adj 15): empty #17
,D/HyLog   ( 4762): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4762): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4762): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,E/TASKS   ( 4762): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/TASKS_APP_WIDGET( 4762): onReceive() #################################################
,I/TASKS   ( 4762): getCurrentThemeInfo START #############################
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/TASKS   ( 4762): com.lge.launcher2.theme.optimus
I/TASKS   ( 4762): com.lge.task
I/TASKS   ( 4762): getCurrentThemeInfo END #############################
I/TASKS   ( 4762): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4762): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4762): intentAction : android.intent.action.TIME_SET
,I/ActivityManager(  967): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4779 uid=10122 gids={50122}
,I/ActivityManager(  967): Killing 4381:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4779): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4779): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42869e00, skipping init
,D/TimeService( 4779): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453903040818
D/        ( 4779): TimeServiceNative: User Time to be set is 1453903040818
D/QC-time-services( 4779): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4779): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4779): Lib:time_genoff_operation: pargs->ts_val = 1453903040818
,D/QC-time-services(  418): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4779): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  418): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453903040818
D/QC-time-services(  418): Daemon:genoff_opr: Base = 2, val = 1453903040818, operation = 0
D/QC-time-services(  418): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/4/70 1:41:35
D/QC-time-services(  418): Daemon:Value read from RTC seconds = 13311695000
D/QC-time-services(  418): Daemon:new time 1453903040818 
D/QC-time-services(  418): Daemon: delta 1440591345818 genoff 1440591345818 
D/QC-time-services(  418): Daemon:genoff_persistent_update: Writing genoff = 1440591345818 to memory
D/QC-time-services(  418): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  418): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  418): Updating the TOD offset
D/QC-time-services(  418): Daemon:genoff_persistent_update: Writing genoff = 1440591345818 to memory
D/QC-time-services(  418): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  418): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  418): Daemon:Update to modem bit set
,E/QC-time-services( 4779): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  418): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  418): Daemon: Base = 2, Value being sent to MODEM = 1137938240818
,E/QC-time-services(  418): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  418): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  967): Killing 3738:com.android.vending/u0a50 (adj 15): empty #17
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1566): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3659): onReceive
D/AppUp4:CustFacade( 3659): Context : android.app.ReceiverRestrictedContext@4287f3e0
D/AppUp4:CustFacade( 3659): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3659): isOpenOperator : true
,D/AppUp4:CustFacade( 3659): isPhone : true
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
,I/AppUp4:EulaManager( 3659): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3659): begin check event
,I/AppUp4:CustModeStarterReceiver( 3659): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4539): DownloadService onCreate
,I/DownloadManager( 4539): in removeSpuriousFiles
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428b94b8 on behalf of 4539
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 4539): in trimDatabase
V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/EAS     ( 4076): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4076): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428baeb0 on behalf of 4539
I/LgeMiscReceiver( 3823): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3823): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3823): networkInfo.isConnected() = true
D/PhoneState( 3823): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 4597): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 4539): DownloadService onStartCommand
D/MobileConnectivityChangeReceiver( 4597): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4076): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DrmBroadcastReceiver( 4615): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 4615): 1  network is available. Sync DRM Time with NTP
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428bd060 on behalf of 4539
D/LGDMClient( 2851): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DrmService( 4615): Service onCreate
D/DrmService( 4615): Received new request = 2
D/LGDMClient( 2851): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/LGDMSGCM( 4311): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 4615): Start Sync process
,D/DrmSntpClient( 4615): Server : 0
E/DataScheduler( 4615): isDataSchedulerEnabled():false
,I/LGDMClient( 2851): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4330): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4330): CONNECT : WIFI_CONNECT
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,E/LGDMClient( 2851): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 4539): DownloadService onDestroy
,W/ContextImpl( 4311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2851): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2851): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2851): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 3713): GC_FOR_ALLOC freed 9K, 14% free 24889K/28836K, paused 12ms, total 13ms
,I/dalvikvm-heap( 3713): Grow heap (frag case) to 30.388MB for 4099024-byte allocation
,D/dalvikvm( 3713): GC_CONCURRENT freed <1K, 13% free 28894K/32840K, paused 2ms+1ms, total 12ms
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 3713): GC_FOR_ALLOC freed 4K, 13% free 28891K/32840K, paused 22ms, total 23ms
,I/LGDrmService( 4615): _DRM_ServiceGet() : Bind lgdrm service
I/LGDRM   (  274): [DRM] SET TIME : YR=2016, MON=1, DAY=27
,I/LGDRM   (  274): [DRM] SET TIME : HR=13, MIN=57, SEC=20
,I/DrmSntpClient( 4615): Synched
D/DrmService( 4615): Completed !! request = 2
,D/DrmService( 4615): Request count = 0
,V/DrmService( 4615): Service onDestroy
,I/dalvikvm-heap( 3713): Grow heap (frag case) to 34.296MB for 4099024-byte allocation
,D/GCM     ( 1566): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/WeatherAncestor( 1831): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:57:20
,D/UpdateThreadPoolManager( 1831): 2 : This is isUpdating : false
,D/Weather_cast( 1831): 2 : Request from alarm is Canceled
,D/WeatherAncestor( 1831): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:57:20
,D/WeatherService( 1831): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,D/WeatherQuickCover( 1831): 2 : quick cover state : opened : 0
D/AuthorizationBluetoothService( 1566): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/Weather.Utils( 1831): 2 : Utils getTopActivity com.lge.launcher2 / false
E/AuthorizationBluetoothService( 1566): Proximity feature is not enabled.
D/Weather.Utils( 1831): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1831): 2 : shouldTimeTickRegistered : false
,D/GCM     ( 1566): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GmsCoreStatsServiceLauncher( 1976): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  967): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4802 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
,W/ActivityThread(  967): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/LocationInitializer( 1976): Restart initialization of location
,D/HyLog   ( 4802): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4802): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4802): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/VacuumService( 1566): Vacuum at: now=1453903041058 tag=VacuumService
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3659): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3659): onReceive
D/AppUp4:CustFacade( 3659): Context : android.app.ReceiverRestrictedContext@4287f3e0
D/AppUp4:CustFacade( 3659): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3659): isOpenOperator : true
,D/AppUp4:CustFacade( 3659): isPhone : true
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/LicenseContentProvider( 2963): start selecting data
,D/SIMObserver( 2963): simInfo1
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/AppUp4:EulaManager( 3659): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3659): begin check event
,I/AppUp4:CustModeStarterReceiver( 3659): Event For GoodConnectivity, noConnectivity : false, but skip! 
W/dalvikvm( 4802): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4802): VFY: replacing opcode 0x60 at 0x000b
,V/DownloadManager( 4539): DownloadService onCreate
,I/DownloadManager( 4539): in removeSpuriousFiles
,D/EAS     ( 4076): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4076): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): DownloadService onStartCommand
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428c1f48 on behalf of 4539
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428c3840 on behalf of 4539
,I/LgeMiscReceiver( 3823): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3823): action = android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 4076): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4539): DownloadService onDestroy
,I/DownloadManager( 4539): in trimDatabase
I/LgeMiscReceiver( 3823): networkInfo.isConnected() = true
,D/PhoneState( 3823): setPdpRejectCasuse : false
D/dalvikvm( 4802): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4802): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4802): VFY: replacing opcode 0x62 at 0x005e
,D/MobileConnectivityChangeReceiver( 4597): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4597): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/MultiDex( 4802): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4802): install
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428c5800 on behalf of 4539
,D/LGDMClient( 2851): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/MultiDex( 4802): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/LGDMClient( 2851): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4311): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2851): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/MultiDex( 4802): loading existing secondary dex files
,W/ContextImpl( 4311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2851): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/NFS     ( 4330): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4330): CONNECT : WIFI_CONNECT
D/LGDMClient( 2851): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2851): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/MultiDex( 4802): load found 3 secondary dex files
I/MultiDex( 4802): install done
I/LGDMClient( 2851): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 3713): GC_CONCURRENT freed 7K, 10% free 33211K/36844K, paused 1ms+1ms, total 19ms
,D/dalvikvm( 4802): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4802): VFY: unable to resolve instance field 61
,D/dalvikvm( 4802): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4802): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4802): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4802): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4802): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4802): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4802): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4802): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4802): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4802): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4286bf48
,D/dalvikvm( 4802): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4286bf48
,D/dalvikvm( 4802): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4286bf48, skipping init
,D/dalvikvm( 4802): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4286bf48
D/dalvikvm( 4802): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4286bf48
,V/JNIHelp ( 4802): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4802): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4286bf48
,D/dalvikvm( 4802): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4286bf48
D/dalvikvm( 4802): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4286bf48
,D/dalvikvm( 4802): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4286bf48
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4827 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/HyLog   ( 4827): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4827): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4827): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ProviderInstaller( 4802): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4802): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
,W/dalvikvm( 4802): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4802): VFY: replacing opcode 0x6e at 0x003f
,D/WearableService( 4802): callingUid 10006, callindPid: 4802
,E/dalvikvm( 4802): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4802): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 4802): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 4802): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 4802): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4802): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4802): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4802): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4802): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4802): VFY: replacing opcode 0x6e at 0x0201
,E/MDM     ( 1423): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Babel   ( 4827): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4827): MmsConfig.loadMmsSettings
,I/Babel   ( 4827): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4827): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 4827): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,W/BaseRuntimeLoader( 4827): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4827): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4827): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4827): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4827): MmsConfig.loadFromResources
,E/Babel   ( 4827): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4827): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/MediaCodecList( 4827): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 4827): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4827): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4827): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/Settings( 4827): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4827): [loadRssi] File not exist 
V/LGRssiData( 4827): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4827): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4827): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4827): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4827): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/GoogleURLConnFactory( 1566): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1566): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1566): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1566): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1566): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1566): No account for auth token provided
,D/CalendarWidget( 4710): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4710): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,D/TASKS_APP_WIDGET( 4762): onReceive() #################################################
I/TASKS   ( 4762): getCurrentThemeInfo START #############################
I/TASKS   ( 4762): com.lge.launcher2.theme.optimus
I/TASKS   ( 4762): com.lge.task
I/TASKS   ( 4762): getCurrentThemeInfo END #############################
,I/TASKS   ( 4762): loadThemeResources packageName : com.lge.task
I/TASKS   ( 4762): loadLocalResId #############################
D/TASKS_APP_WIDGET( 4762): intentAction : com.lge.task.APPWIDGET_UPDATE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1566): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1566): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1566): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1976): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1423): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1976): Restart initialization of location
,D/CalendarWidget( 4710): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4710): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4827): UserRecoverableAuthException.
,E/Babel   ( 4827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4827): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4827): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4827): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4827): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4827): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4827): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4827): Error getting auth token
,E/Babel   ( 4827): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4827): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4827): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4827): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4827): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4827): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4827): Account registration failedRedacted-21
,E/Babel   ( 4827): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4827): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4827): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4827): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4827): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4827): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
I/Babel   ( 4827): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4827): Account sign in complete with state 106account: Redacted-21
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4827): Unexpected exception while authenticating.
,E/Babel   ( 4827): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4827): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4827): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4827): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4827): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4827): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4827): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4827): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4827): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43468910: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/dalvikvm( 4696): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42be1b90
D/dalvikvm( 4696): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42be1b90
,D/dalvikvm( 4696): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42be1b90, skipping init
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,I/CalendarProvider2( 4740): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
W/ContentResolver( 4740): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/AlertReceiver( 4710): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CalendarWidget( 4710): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 4710): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/AlertService( 4710): Beginning updateAlertNotification
,D/AlertService( 4710): No fired or scheduled alerts
,D/CalendarWidget( 4710): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4710): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
I/ActivityManager(  967): Killing 3697:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 4696): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4869): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4696): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4696): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 111ms
,I/Adreno-EGL( 4696): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4696): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4696): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4696): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4696): Remote Branch: 
I/Adreno-EGL( 4696): Local Patches: 
I/Adreno-EGL( 4696): Reconstruct Branch: 
,I/jxcore-log( 4165): Test app app.js loaded
I/jxcore-log( 4165): 
I/dalvikvm( 4165): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4165): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4165): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4165): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4165): BLE advertisement is supported
I/jxcore-log( 4165): 
,I/chromium( 4165): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Adreno-EGL( 4696): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4696): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4696): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4696): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4696): Remote Branch: 
I/Adreno-EGL( 4696): Local Patches: 
I/Adreno-EGL( 4696): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1566): No account for auth token provided
,I/Adreno-EGL( 4696): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4696): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4696): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4696): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4696): Remote Branch: 
I/Adreno-EGL( 4696): Local Patches: 
I/Adreno-EGL( 4696): Reconstruct Branch: 
,W/Uploader( 1566): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1566): No account for auth token provided
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,W/Uploader( 1566):  no longer exists, so no auth token.
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=508211801
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Uploader( 1566): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm( 1566): GC_CONCURRENT freed 1740K, 28% free 18104K/24832K, paused 3ms+4ms, total 40ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings( 4696): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1976): Classify the device as Phone.
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4244): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4244): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1566): No account for auth token provided
,D/dalvikvm( 1976): GC_CONCURRENT freed 1649K, 22% free 19553K/24832K, paused 4ms+8ms, total 51ms
,I/CheckinTask( 1976): Sending checkin request (11855 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinResponseProcessor( 1976): From server: 11 gservices updates and 1 deletes
,I/CertBlacklister(  967): Certificate blacklist changed, updating...
,I/CertBlacklister(  967): Certificate blacklist updated
,I/GservicesProvider( 1566): main difference update completed
,I/ActivityManager(  967): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4886 uid=10003 gids={50003, 3003, 2001}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1976): Checkin reason type: 8 attempt count: 1
D/HyLog   ( 4886): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4886): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4886): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/ActivityThread( 1976): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4886): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4886): Update started
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DownloadManager( 4539): DB Update : deleted 1
,V/DownloadManager( 4539): DownloadService onCreate
,E/UpdateRequestReceiver( 4886): Received malformed URL while handling Gservices.CHANGED_ACTION
I/DownloadManager( 4539): in removeSpuriousFiles
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4539): initiating download with UID 10003
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428ceac8 on behalf of 4539
,V/DownloadManager( 4539): DownloadService onStartCommand
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4539): in trimDatabase
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428d2c88 on behalf of 4539
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428d3e40 on behalf of 4539
,V/DownloadManager( 4539): DownloadService onStartCommand
V/DownloadManager( 4539): processing inserted download 261
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:190
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428d7788 on behalf of 4539
,W/ContextImpl( 4886): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,D/dalvikvm(  967): GC_EXPLICIT freed 1857K, 52% free 29829K/61100K, paused 3ms+12ms, total 119ms
,D/DownloadManager( 4539): DB Update : status 192
,I/UpdateFetcherService( 4886): Update started
,D/DownloadManager( 4539): DB Update : deleted 1
,V/DownloadManager( 4539): DownloadService onStartCommand
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428dbb30 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): initiating download with UID 10003
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428de598 on behalf of 4539
I/DownloadManager( 4539): Download 261 starting
I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/DownloadManager( 4539): fileSize : -1state.mContinuingDownload :false
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,E/DataScheduler( 4539): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4488c1c0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,V/DownloadManager( 4539): DownloadService onStartCommand
V/DownloadManager( 4539): processing updated download 261, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428f8460 on behalf of 4539
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
V/DownloadManager( 4539): processing inserted download 262
V/LFT     ( 4539): isReadyToDownload mId, mStatus=262:190
V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428fa628 on behalf of 4539
D/DownloadManager( 4539): DB Update : status 192
,W/CheckinRequestBuilder( 1976): awaiting user notification for token
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428fc940 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@428fea00 on behalf of 4539
V/DownloadManager( 4539): processing updated download 261, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42900888 on behalf of 4539
,I/DownloadManager( 4539): Download 262 starting
,I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 4539): fileSize : -1state.mContinuingDownload :false
V/DownloadManager( 4539): processing updated download 262, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=262:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42902c38 on behalf of 4539
,E/UpdateRequestReceiver( 4886): Received malformed URL while handling Gservices.CHANGED_ACTION
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,E/UpdateRequestReceiver( 4886): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinRequestBuilder( 1976): Classify the device as Phone.
,E/UpdateRequestReceiver( 4886): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  967): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4948 uid=10009 gids={50009, 3003}
,D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,D/HyLog   ( 4948): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4948): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4948): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,I/CheckinTask( 1976): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,I/CheckinService( 1976): Checking schedule, now: 1453903044536 next: 1454480440522
,I/CheckinService( 1976): active receiver: disabled
,W/BaseRuntimeLoader( 4948): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4948): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4948): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4948): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/DownloadManager( 4539): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 4539): Content-Disposition: null
V/DownloadManager( 4539): Content-Length: -1
V/DownloadManager( 4539): Content-Location: null
V/DownloadManager( 4539): Content-Type: text/plain
,V/DownloadManager( 4539): ETag: null
V/DownloadManager( 4539): Transfer-Encoding: chunked
V/DownloadManager( 4539): X-Oma-Drm-Separate-Delivery: null
,V/DownloadManager( 4539): Min update size = 16384
I/CheckinService( 1976): Checking schedule, now: 1453903044585 next: 1454480440522
,I/CheckinService( 1976): active receiver: disabled
,V/DownloadManager( 4539): getting filename from uri
,I/ContactAccountLoggerTas( 2640): canRun() : Opted Out
,I/DownloadManager( 4539): in verifySpace, destination: 5, path: 10152015-sms-metadata.txt, length: 0
,V/DownloadManager( 4539): keeping extension
,V/DownloadManager( 4539): target file: /cache/10152015-sms-metadata.txt
,I/Search.GservicesUpdateTask( 2640): Updating Gservices keys
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42931bd0 on behalf of 4539
,D/DownloadManager( 4539): DB Update : title 10152015-sms-metadata.txt
D/DownloadManager( 4539): DB Update : mimetype text/plain
D/DownloadManager( 4539): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4539): DB Update : total_bytes -1
,I/ContactAccountLoggerTas( 2640): canRun() : Opted Out
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/ContactAccountLoggerTas( 2640): canRun() : Opted Out
,W/Search.LoginHelper( 2640): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2640): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2640): canRun() : Opted Out
,I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@4295e490 on behalf of 4539
,I/LGDrmService( 4539): _DRM_ServiceGet() : Bind lgdrm service
,V/DownloadManager( 4539): processing updated download 261, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@4296bcc0 on behalf of 4539
D/DownloadManager( 4539): DB Update : current_bytes 383
,D/DownloadManager( 4539): DB Update : total_bytes 383
V/DownloadManager( 4539): processing updated download 262, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=262:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/ContactAccountLoggerTas( 2640): canRun() : Opted Out
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@4296f898 on behalf of 4539
,V/LFT     ( 4539): notifyThroughDatabase after updateDB  id :  262, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 4539): notifyThroughDatabase start id : 262 name : /cache/10152015-sms-metadata.txt status : 200
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42973698 on behalf of 4539
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42974a00 on behalf of 4539
,D/DownloadManager( 4539): DB Update : numfailed 0
D/DownloadManager( 4539): DB Update : method 0
,D/DownloadManager( 4539): DB Update : lastmod 1453903044653
,D/DownloadManager( 4539): DB Update : mimetype text/plain
D/DownloadManager( 4539): DB Update : _data /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4539): DB Update : status 200
,V/DownloadManager( 4539): processing updated download 261, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42979500 on behalf of 4539
,I/DownloadManager( 4539): Download 262 finished with status SUCCESS
,V/DownloadManager( 4539): processing updated download 262, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=262:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 1976): Checking schedule, now: 1453903044685 next: 1454480440522
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@4297d980 on behalf of 4539
,I/CheckinService( 1976): active receiver: disabled
I/SystemUpdateService( 1976): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/DownloadManager( 4539): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 4539): checkStatusUpdate return true mID : mStatus = 262 : 200 => 200
,D/SystemUpdateService( 1976): onCreate
,D/SystemUpdateService( 1976): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@429835e0 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 261, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42986e00 on behalf of 4539
,I/SystemUpdateService( 1976): cancelUpdate (empty URL)
,I/SystemUpdateService( 1976): active receiver: disabled
,D/SystemEventReceiver( 1976): Received GSERVICES_CHANGED broadcast
,D/GCM     ( 1566): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  967): Killing 4681:com.lge.clock/u0a10 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 1566): GC_EXPLICIT freed 899K, 28% free 18121K/24832K, paused 1ms+3ms, total 25ms
,I/OcrUtils( 1976): Updating ocr activity enabled=false
,D/SystemUpdateService( 1976): onDestroy
,I/GCoreUlr( 1423): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1423): DispatchingService.onCreate()
,I/GCoreUlr( 1423): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GAV2    ( 4632): Thread[GAThread,5,main]: No campaign data found.
,I/GCoreUlr( 1423): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1423): Unbound from all location providers
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm( 1566): GC_EXPLICIT freed 173K, 28% free 18046K/24832K, paused 2ms+3ms, total 27ms
,D/dalvikvm( 1976): GC_EXPLICIT freed 1199K, 22% free 19438K/24832K, paused 2ms+4ms, total 38ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GCoreUlr( 1423): DispatchingService.onDestroy()
,I/GCoreUlr( 1423): Unbound from all location providers
,W/ActivityThread( 4539): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/GCM     ( 1566): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm(  967): GC_EXPLICIT freed 1341K, 52% free 29645K/61100K, paused 3ms+6ms, total 87ms
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 262; sort is lastmod DESC.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a792a8 on behalf of 4886
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 262; sort is lastmod DESC.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a7ca40 on behalf of 4886
,W/ContextImpl( 4886): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 4539): initiating download with UID 10003
,D/GCM     ( 1566): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 4539): DownloadService onStartCommand
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a80ae0 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 261, status: 192
V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a829a0 on behalf of 4539
,V/DownloadManager( 4539): processing inserted download 263
V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:190
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a84ea8 on behalf of 4539
,D/DownloadManager( 4539): DB Update : status 192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a87100 on behalf of 4539
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a89280 on behalf of 4539
,I/DownloadManager( 4539): Download 263 starting
,I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 4539): processing updated download 261, status: 192
V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
,I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 4539): fileSize : -1state.mContinuingDownload :false
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a8bb80 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 263, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a90ae8 on behalf of 4539
,I/DownloadManager( 4539): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 4539): Content-Disposition: null
V/DownloadManager( 4539): Content-Length: -1
V/DownloadManager( 4539): Content-Location: null
V/DownloadManager( 4539): Content-Type: text/plain
,V/DownloadManager( 4539): ETag: null
V/DownloadManager( 4539): Transfer-Encoding: chunked
V/DownloadManager( 4539): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4539): Min update size = 16384
V/DownloadManager( 4539): getting filename from uri
,I/DownloadManager( 4539): in verifySpace, destination: 5, path: 08202014-metadata.txt, length: 0
V/DownloadManager( 4539): keeping extension
,V/DownloadManager( 4539): target file: /cache/08202014-metadata.txt
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a94ad8 on behalf of 4539
,D/DownloadManager( 4539): DB Update : title 08202014-metadata.txt
D/DownloadManager( 4539): DB Update : mimetype text/plain
D/DownloadManager( 4539): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 4539): DB Update : total_bytes -1
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a975b8 on behalf of 4539
V/DownloadManager( 4539): processing updated download 261, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 4539): transferData threadNum : -1
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42a9a720 on behalf of 4539
V/DownloadManager( 4539): processing updated download 263, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42aa4130 on behalf of 4539
,D/DownloadManager( 4539): transferData threadNum : -1
D/DownloadManager( 4539): DB Update : current_bytes 384
,D/DownloadManager( 4539): DB Update : total_bytes 384
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 4539): notifyThroughDatabase after updateDB  id :  261, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 4539): notifyThroughDatabase start id : 261 name : /cache/08202014-metadata.txt status : 200
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42aa8598 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 261, status: 192
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42aa8f50 on behalf of 4539
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=261:192
V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 4539): DB Update : numfailed 0
D/DownloadManager( 4539): DB Update : method 0
D/DownloadManager( 4539): DB Update : lastmod 1453903045296
D/DownloadManager( 4539): DB Update : mimetype text/plain
D/DownloadManager( 4539): DB Update : _data /cache/08202014-metadata.txt
,D/DownloadManager( 4539): DB Update : status 200
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42aab170 on behalf of 4539
,D/DownloadManager( 4539): checkStatusUpdate current status 192 is changed to 200
,D/DownloadManager( 4539): checkStatusUpdate return true mID : mStatus = 261 : 200 => 200
V/DownloadManager( 4539): processing updated download 263, status: 192
I/DownloadManager( 4539): Download 261 finished with status SUCCESS
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42aae168 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ab02f0 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 261; sort is lastmod DESC.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ab38e8 on behalf of 4886
V/DownloadManager( 4539): processing updated download 263, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ab5da0 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 261; sort is lastmod DESC.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ab9398 on behalf of 4886
,W/ContextImpl( 4886): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,V/DownloadManager( 4539): initiating download with UID 10003
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4539): DownloadService onStartCommand
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ac4460 on behalf of 4539
V/DownloadManager( 4539): processing updated download 263, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ac6a68 on behalf of 4539
,V/DownloadManager( 4539): processing inserted download 264
V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:190
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ac8bb8 on behalf of 4539
,D/DownloadManager( 4539): DB Update : status 192
I/DownloadManager( 4539): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4539): Content-Disposition: null
V/DownloadManager( 4539): Content-Length: -1
V/DownloadManager( 4539): Content-Location: null
V/DownloadManager( 4539): Content-Type: text/plain
,V/DownloadManager( 4539): ETag: null
V/DownloadManager( 4539): Transfer-Encoding: chunked
V/DownloadManager( 4539): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4539): Min update size = 16384
V/DownloadManager( 4539): getting filename from uri
I/DownloadManager( 4539): in verifySpace, destination: 5, path: 10152015-sms-blacklist.txt, length: 0
V/DownloadManager( 4539): keeping extension
V/DownloadManager( 4539): target file: /cache/10152015-sms-blacklist.txt
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42accce0 on behalf of 4539
,D/DownloadManager( 4539): DB Update : title 10152015-sms-blacklist.txt
D/DownloadManager( 4539): DB Update : mimetype text/plain
D/DownloadManager( 4539): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 4539): DB Update : total_bytes -1
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ad1058 on behalf of 4539
I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42acffc0 on behalf of 4539
,D/LGDRM   (  274): [DRM] Part_DetectType() : Buffer contains XML Prologue
,D/LGDRM   (  274): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
V/DownloadManager( 4539): processing updated download 263, status: 192
,D/DownloadManager( 4539): transferData threadNum : -1
I/DownloadManager( 4539): Download 264 starting
V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42add998 on behalf of 4539
,D/DownloadManager( 4539): fileSize : -1state.mContinuingDownload :false
,D/DownloadManager( 4539): transferData threadNum : -1
V/DownloadManager( 4539): processing updated download 264, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ae1f68 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ae4a38 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 263, status: 192
V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ae6f18 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 264, status: 192
V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42ae8438 on behalf of 4539
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
D/DownloadManager( 4539): DB Update : current_bytes 13383
,D/DownloadManager( 4539): DB Update : total_bytes 13383
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42af61c0 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 263, status: 192
V/LFT     ( 4539): notifyThroughDatabase after updateDB  id :  263, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 4539): notifyThroughDatabase start id : 263 name : /cache/10152015-sms-blacklist.txt status : 200
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 4539): isReadyToDownload mId, mStatus=263:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42af9160 on behalf of 4539
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42af9bb0 on behalf of 4539
D/DownloadManager( 4539): DB Update : numfailed 0
D/DownloadManager( 4539): DB Update : method 0
D/DownloadManager( 4539): DB Update : lastmod 1453903045401
D/DownloadManager( 4539): DB Update : mimetype text/plain
,D/DownloadManager( 4539): DB Update : _data /cache/10152015-sms-blacklist.txt
,D/DownloadManager( 4539): DB Update : status 200
V/DownloadManager( 4539): processing updated download 264, status: 192
V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42afc1c8 on behalf of 4539
,I/DownloadManager( 4539): Download 263 finished with status SUCCESS
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b028a0 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 263; sort is lastmod DESC.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b0bc80 on behalf of 4886
,V/DownloadManager( 4539): processing updated download 264, status: 192
V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b123e0 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 263; sort is lastmod DESC.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b1eca8 on behalf of 4886
,W/ContextImpl( 4886): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4886): Update downloaded, starting installation
,I/UpdateFetcherService( 4886): Started installation
,D/DownloadManager( 4539): DB Update : deleted 1
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): DownloadService onStartCommand
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b58520 on behalf of 4539
,D/DownloadManager( 4539): deleteFileIfExists() deleting /cache/10152015-sms-metadata.txt
,D/DownloadManager( 4539): deleteFileIfExists() deleting /cache/10152015-sms-blacklist.txt
,V/DownloadManager( 4539): processing updated download 264, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b5dbe0 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b5fd68 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 264, status: 192
V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b61d68 on behalf of 4539
,I/DownloadManager( 4539): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 4539): Content-Disposition: null
V/DownloadManager( 4539): Content-Length: -1
V/DownloadManager( 4539): Content-Location: null
V/DownloadManager( 4539): Content-Type: text/plain
,V/DownloadManager( 4539): ETag: null
V/DownloadManager( 4539): Transfer-Encoding: chunked
V/DownloadManager( 4539): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 4539): Min update size = 16384
V/DownloadManager( 4539): getting filename from uri
I/DownloadManager( 4539): in verifySpace, destination: 5, path: 08202014-pins.txt, length: 0
V/DownloadManager( 4539): keeping extension
,V/DownloadManager( 4539): target file: /cache/08202014-pins.txt
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b65878 on behalf of 4539
,D/DownloadManager( 4539): DB Update : title 08202014-pins.txt
D/DownloadManager( 4539): DB Update : mimetype text/plain
D/DownloadManager( 4539): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 4539): DB Update : total_bytes -1
V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4539): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b68668 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 264, status: 192
V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
D/DownloadManager( 4539): transferData threadNum : -1
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b737b0 on behalf of 4539
,D/DownloadManager( 4539): transferData threadNum : -1
D/DownloadManager( 4539): transferData threadNum : -1
D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
D/DownloadManager( 4539): transferData threadNum : -1
D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
D/DownloadManager( 4539): transferData threadNum : -1
D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): DB Update : current_bytes 32768
,V/DownloadManager( 4539): downloaded 32768 for https://www.gstatic.com/android/config_update/08202014-pins.txt
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/DownloadManager( 4539): transferData threadNum : -1
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b788f0 on behalf of 4539
,V/DownloadManager( 4539): processing updated download 264, status: 192
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b7aa10 on behalf of 4539
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
,D/DownloadManager( 4539): transferData threadNum : -1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/DownloadManager( 4539): DB Update : current_bytes 39938
D/DownloadManager( 4539): DB Update : total_bytes 39938
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/LFT     ( 4539): notifyThroughDatabase after updateDB  id :  264, mstatus : 192, largemode : 0, settingMode : 0
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b7e898 on behalf of 4539
,D/DownloadManager( 4539): notifyThroughDatabase start id : 264 name : /cache/08202014-pins.txt status : 200
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b80a80 on behalf of 4539
,D/DownloadManager( 4539): DB Update : numfailed 0
,V/DownloadManager( 4539): processing updated download 264, status: 192
D/DownloadManager( 4539): DB Update : method 0
,D/DownloadManager( 4539): DB Update : lastmod 1453903045992
D/DownloadManager( 4539): DB Update : mimetype text/plain
,D/DownloadManager( 4539): DB Update : _data /cache/08202014-pins.txt
,D/DownloadManager( 4539): DB Update : status 200
,V/LFT     ( 4539): isReadyToDownload mId, mStatus=264:192
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b82f58 on behalf of 4539
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 264; sort is lastmod DESC.
,I/DownloadManager( 4539): Download 264 finished with status SUCCESS
,D/DownloadManager( 4539): checkStatusUpdate current status 192 is changed to 200
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b86e30 on behalf of 4886
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 264; sort is lastmod DESC.
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b8a748 on behalf of 4886
,W/ContextImpl( 4886): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,D/DownloadManager( 4539): checkStatusUpdate return true mID : mStatus = 264 : 200 => 200
,I/UpdateFetcherService( 4886): Update downloaded, starting installation
,I/UpdateFetcherService( 4886): Started installation
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4244): wlan0: Control interface command 'SIGNAL_POLL'
,D/DownloadManager( 4539): DB Update : deleted 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigUpdateInstallReceiver(  967): Not installing, new version is <= current version
V/DownloadManager( 4539): DownloadService onDestroy
D/wpa_supplicant( 4244): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
V/DownloadManager( 4539): DownloadService onCreate
I/DownloadManager( 4539): in removeSpuriousFiles
V/DownloadManager( 4539): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b8f410 on behalf of 4539
V/DownloadManager( 4539): DownloadService onStartCommand
I/DownloadManager( 4539): in removeSpuriousFiles, preserving file /cache/08202014-metadata.txt
I/DownloadManager( 4539): in removeSpuriousFiles, preserving file /cache/08202014-pins.txt
V/DownloadManager( 4539): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4539): in trimDatabase
V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b92560 on behalf of 4539
V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b92ad8 on behalf of 4539
V/DownloadManager( 4539): processing inserted download 261
D/DownloadManager( 4539): deleteFileIfExists() deleting /cache/08202014-metadata.txt
,V/DownloadManager( 4539): processing inserted download 264
,D/DownloadManager( 4539): deleteFileIfExists() deleting /cache/08202014-pins.txt
,V/DownloadManager( 4539): DownloadService onDestroy
I/ActivityManager(  967): Killing 4779:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Killing 2963:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityThread( 3659): Removing dead content provider:android.content.ContentProviderProxy@428bb6a8
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Killing 3659:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Killing 4076:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  967): Checking http://216.58.209.78/generate_204
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4244): wlan0: Control interface command 'SIGNAL_POLL'
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 4244): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,V/ConfigFetchTask( 1976): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1W5DtAqbKyA_1DuVQ8RFHuh9dLR9J0S3ngkvmvjRunEAyxj09-JKwme_G0m6KYJC66bjX4q9mbaAPXdhCelnb0C1TDVlOcVD-AFWOuIoYhI_BgbTC2U9x_eeVRbFRZtjLSKUKBA7Sx5Edg6HqJYoAJQUgCaurmuhjFfj1WUZjD0CLKHtWcEZtRWq693UWkffq3fwGEvRH81mYDuTwkqaLX26bMqRkHAVfXTOzg_fsTmxM5XD5Q
,I/GAV2    ( 3713): Thread[GAThread,5,main]: No campaign data found.
,I/GoogleURLConnFactory( 1976): Using platform SSLCertificateSocketFactory
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3571): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,D/administrator(  967): Handling package changes for user 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3571): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  967): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5069 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3571): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3571): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5069): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5069): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5069): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/AppUp4  ( 5069):  AppBoxContentProvider onCreate
,W/AppUp4  ( 5069):  [AppBoxDatabaseHelper] construct
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
,I/AppUp4  ( 5069):  setFingerPrint start
,I/AppUp4  ( 5069):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 5069):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 5069):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5069): AppBoxApplication onCreate()
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppBoxBlacklist( 5069): ConfigFile is not exist. /cust/config/appmanager.cfg
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  967): Handling package changes for user 0
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/PackageParser( 5069): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/PackageParser( 5069): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
D/AppUp4:Utils( 5069): [getPackageName] uri : package:com.google.android.talk
D/AppUp4  ( 5069): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5069): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
,I/AppUp4:CustModeStarterReceiver( 5069): onReceive
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AppUp4:CustFacade( 5069): Context : android.app.ReceiverRestrictedContext@42875328
D/AppUp4:CustFacade( 5069): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5069): isOpenOperator : true
D/AppUp4:CustFacade( 5069): isPhone : true
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  967): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=5093 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5093): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5093): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5093): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/LicenseContentProvider( 5093): start selecting data
,W/BaseRuntimeLoader( 5093): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5093): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5093): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5093): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 5093): simInfo1
,I/AppUp4:EulaManager( 5069): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 5069): begin check event
D/AppUp4:Utils( 5069): [getPackageName] uri : package:com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 5069): Event For Nothing, skip.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5106 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  967): Killing 4615:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  967): Killing 4553:com.android.chrome/u0a63 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/HyLog   ( 5106): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5106): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5106): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1423): DISABLE
,I/SystemConfig( 5106): BUILD Country: EU
,I/SystemConfig( 5106): BUILD Operator: OPEN
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5106): systemFeature RCS result false
,D/SystemConfig( 5106): refreshRcsSupport() :false
I/ActivityManager(  967): Killing 4311:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5122 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5122): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5122): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5122): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ConfigFetchTask( 1976): updating config table for com.google.android.gms
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,I/ConfigFetchService( 1976): fetch service done; releasing wakelock
,D/dalvikvm(  967): GC_EXPLICIT freed 2346K, 52% free 29778K/61100K, paused 2ms+10ms, total 95ms
,I/ConfigFetchService( 1976): stopping self
,I/IcingCorporaProvider( 2640): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  967): Killing 4330:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
,I/IcingCorporaProvider( 2640): UpdateCorporaTask done [took 38 ms] updated apps [took 38 ms] 
I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5140 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5140): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5140): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5140): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5140): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5140): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5140): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5140): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5140): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5140): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5140): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5140): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5140): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5140): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5140): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5140): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5140): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5140): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5140): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5140): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5140): VFY: replacing opcode 0x6e at 0x011e
,V/DownloadManager( 4539): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
I/dalvikvm( 5140): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5140): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5140): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5140): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5140): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5140): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 4539): created cursor android.database.sqlite.SQLiteCursor@42b9cd80 on behalf of 5140
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,I/dalvikvm( 5140): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5140): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5140): VFY: replacing opcode 0x6e at 0x001a
,W/GLSActivity( 1566): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1566): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1566): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1566): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1566): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1566): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1566): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1566): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5140): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5140): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5140): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5140): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5140): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5140): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5140): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5140): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43154530: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/dalvikvm( 5140): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5140): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5140): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5140): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5140): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5140): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1976): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/Finsky  ( 5140): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/AppUp4:Utils( 5069): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 5069): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5069): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5069): onReceive
D/AppUp4:CustFacade( 5069): Context : android.app.ReceiverRestrictedContext@42875328
D/AppUp4:CustFacade( 5069): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5069): isOpenOperator : true
,D/AppUp4:CustFacade( 5069): isPhone : true
,I/LicenseContentProvider( 5093): start selecting data
,D/SIMObserver( 5093): simInfo1
,I/AppUp4:EulaManager( 5069): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5069): begin check event
,D/AppUp4:Utils( 5069): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5069): Event For Nothing, skip.
,I/PeopleContactsSync( 1976): CP2 sync disabled
,W/System  ( 5140): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5140): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ActivityManager(  967): Killing 4632:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
I/IcingCorporaProvider( 2640): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/PackageBroadcastService( 1976): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ConfigFetchService( 1976): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/PackageBroadcastService( 1976): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  967): Delaying start of: ServiceRecord{43341148 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ConfigFetchService( 1976): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1976): GmsCore config value changed; rescheduling
,W/ConfigFetchService( 1976): ConfigApi client is not connected. Falling back to defaultfetch interval.
,I/ConfigFetchService( 1976): service connected
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConfigFetchService( 1976): ConfigApi connection successful.
,I/ConfigFetchService( 1976): stopping self
,I/Icing   ( 1976): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1976): GC_CONCURRENT freed 1829K, 22% free 19605K/24832K, paused 2ms+7ms, total 64ms
,I/IcingCorporaProvider( 2640): UpdateCorporaTask done [took 216 ms] updated apps [took 216 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  967): battery changed pluggedType: 2
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/Finsky  ( 5140): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5140): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5140): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5140): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5140): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1566): GC_EXPLICIT freed 917K, 28% free 18077K/24832K, paused 2ms+7ms, total 45ms
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5140): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 5140): Total arena pages for JIT: 11
,I/dalvikvm( 5140): Total arena pages for JIT: 12
I/dalvikvm( 5140): Total arena pages for JIT: 13
,I/dalvikvm( 5140): Total arena pages for JIT: 14
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4244): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4244): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/GLSUser ( 1566): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1566): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1566): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1566): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1566): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5140): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5140): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5140): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5140): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1423): client connected with version: 7571000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.579239 Y: -0.346283 Z: 9.781982 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.583694 Y: -0.347382 Z: 9.800858 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.579239 .y:-0.346283 .z:9.781982
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.587082 Y: -0.330734 Z: 9.790451 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.587082 .y:-0.330734 .z:9.790451
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
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
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9068 usec
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
D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.589172 Y: -0.340302 Z: 9.804474 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.589172 .y:-0.340302 .z:9.804474
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.586029 Y: -0.334244 Z: 9.802475 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.586029 .y:-0.334244 .z:9.802475
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  391): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  967): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  967): proximitySensorChanged  positive = true
I/KnockOnPowerController(  967): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.590378 Y: -0.350174 Z: 9.794098 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.590378 .y:-0.350174 .z:9.794098
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.595612 Y: -0.350571 Z: 9.796387 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.595612 .y:-0.350571 .z:9.796387
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.592697 Y: -0.338028 Z: 9.793182 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.592697 .y:-0.338028 .z:9.793182
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
W/PackageSettings(  967): Skipping PackageSetting{42d513b0 com.example.hello/10312} due to missing metadata
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.590469 Y: -0.348755 Z: 9.792389 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.590469 .y:-0.348755 .z:9.792389
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43c423e8)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
I/WindowManager(  967): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7d87450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.590408 Y: -0.350800 Z: 9.795273 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.590408 .y:-0.350800 .z:9.795273
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4244): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 4244): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4244): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 4244): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433cd538 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3571): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3571): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/WeatherAncestor( 1831): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:57:34
,D/UpdateThreadPoolManager( 1831): 2 : This is isUpdating : false
,D/WeatherAncestor( 1831): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:57:34
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1831): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1831): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/WeatherService( 1831): 2 : shouldTimeTickRegistered : false
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1156): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 243, B = 243
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 237, B = 237
,D/dalvikvm( 1156): GC_CONCURRENT freed 2863K, 11% free 25470K/28488K, paused 2ms+4ms, total 49ms
,D/qdlights( 1156): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1156): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 412ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453903055316, nextTick: 24716, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/dalvikvm( 1142): GC_CONCURRENT freed 9624K, 13% free 69131K/78936K, paused 6ms+11ms, total 84ms
,D/dalvikvm( 1142): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453903055395, nextTick: 24637, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1156): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1156): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1156): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1156): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1156): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1156): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1156): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1156): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 27, B = 27
,D/dalvikvm(  967): GC_EXPLICIT freed 1813K, 52% free 29856K/61100K, paused 6ms+15ms, total 180ms
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1156): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 21, B = 21
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1156): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 15, B = 15
D/WeatherService( 1831): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:57:35
,D/WeatherService( 1831): 2 : ACTION screen on
,D/WeatherService( 1831): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1831): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:57:35
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
,I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1142): notifyScreenOffLocked
,I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/UsbSettings( 2563): [AUTORUN] onDestroy() : getDefaultFunction =boot
,I/GAV4    ( 4827): Thread[GAThread,5,main]: No campaign data found.
,I/LGImmersionVibrator(  967): Vibrator off
V/UsbSettings( 2563): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2563): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2563): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/WifiStateMachine(  967): handleScreenStateChanged: false
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3} (stop complete)
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
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
D/wpa_supplicant( 4244): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 4244): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/WifiController(  967): CMD_SCREEN_OFF 
D/WifiController(  967): shouldWifiStayAwake TRUE
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
D/EmotionalLed( 1156): RESTART MSG
,D/VolumeVibrator( 1156): clear
E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/wpa_supplicant( 4244): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=2
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4308aa00 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432fcb30 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
E/Parcel  (  409): Reading a NULL string not supported here.
,E/Parcel  (  409): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/WeatherService( 1831): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:57:35
D/WeatherService( 1831): 2 : ACTION screen off
D/WeatherService( 1831): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:57:35
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
D/NfcService( 1471): NFC-C OFF
I/ConfigService( 1566): onDestroy
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  391): sns_pwr.c(320):releasing wakelock
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5140): [438] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5140): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453903073242179570; DSPS: 5272264; Offset: 1453902912345451055
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453903080033, nextTick: 59999, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453903080051, nextTick: 59972, mDrawingTime: 3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453903093244063522; DSPS: 5927685; Offset: 1453902912345473435
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453903113245689347; DSPS: 6583099; Offset: 1453902912345451310
,I/rmt_storage(  420): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb83fa178
I/rmt_storage(  420): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  420): wakelock acquired: 1, error no: 42
,I/rmt_storage(  420): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203790104)
,I/rmt_storage(  420): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  420): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  420): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203790104) wakelock released: 1, error no: 0
I/rmt_storage(  420): 
I/rmt_storage(  420): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb83fa178
,E/Diag_Lib(  678): [IMS_FATAL]| 2912 | 688 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453903133247584183; DSPS: 7238521; Offset: 1453902912345454057
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453903140041, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453903140056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453903153249440738; DSPS: 7893942; Offset: 1453902912345449039
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453903173251355001; DSPS: 8549364; Offset: 1453902912345471212
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453903193253733379; DSPS: 9204802; Offset: 1453902912345469219
,I/jxcore-log( 4165): --= Surplus to requirements =--
I/jxcore-log( 4165): 
,I/jxcore-log( 4165): ****TEST TOOK:  ms ****
I/jxcore-log( 4165): 
,I/jxcore-log( 4165): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4165): 
,D/AndroidRuntime( 5421): 
D/AndroidRuntime( 5421): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5421): CheckJNI is OFF
,D/dalvikvm( 5421): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5421): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5421): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5421): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5421): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5421): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5421): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5421): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5421): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  967): Killing 4165:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
I/MDM     (  967):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  967):   Force finishing activity ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  967): moveHomeStack:
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdae20 stackId=0, 1 tasks}
,V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} (in existing)
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1}
D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdae20 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43078c38 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdae20 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/WindowState(  967): WIN DEATH: Window{430a3190 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  967): Client connection lost with reason: 4
,W/PackageSettings(  967): Skipping PackageSetting{42d513b0 com.example.hello/10312} due to missing metadata
,I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdae20 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/AppUp4:Utils( 5069): [getPackageName] uri : package:com.test.thalitest
E/SlideAside( 3571): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,D/AppUp4  ( 5069): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 5069):  isExcludedPackage  packagename = com.test.thalitest
D/PhoneApp( 1448): getIsInUseVoLTE : false
,I/SlideAside( 3571): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppUp4  ( 5069):  isExcludedPackage TRUE : com.test.thalitest
,D/dalvikvm( 2640): GC_EXPLICIT freed 5421K, 27% free 18191K/24832K, paused 6ms+4ms, total 63ms
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,W/System.err( 2628): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/GeofencerStateMachine( 1423): Ignoring removeGeofence because network location is disabled.
,W/System.err( 2628): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2628): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,W/System.err( 2628): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2628): 	at android.os.Handler.handleCallback(Handler.java:733)
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/System.err( 2628): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2628): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2628): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2628): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2628): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2628): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2628): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2628): 	at dalvik.system.NativeStart.main(Native Method)
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  967): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5439 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  967): GC_EXPLICIT freed 1096K, 52% free 29838K/61100K, paused 2ms+13ms, total 135ms
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5463 uid=10090 gids={50090}
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
D/administrator(  967): Handling package changes for user 0
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5439): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5439): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5439): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5463): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5463): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5463): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/LockScreenSettings( 5463): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/InputMethodManagerService(  967): IME STATUS OFF
,W/Binder  ( 1314): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1314): java.lang.NullPointerException
W/Binder  ( 1314): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1314): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1314): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1314): 	at dalvik.system.NativeStart.run(Native Method)
,D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
,D/[BNRAppListMgrReceiver]( 5439): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
,D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
,D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
,W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4165 uid 10304
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1142): createShortcutInfo...
,D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
I/ActivityManager(  967): Killing 4762:com.lge.task/u0a43 (adj 15): empty #17
,D/KeyguardModel( 1142): handleShortcutListChanged...
D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
,D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
,D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
,I/ActivityManager(  967): Killing 4740:com.android.providers.calendar/u0a16 (adj 15): empty #17
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1142): createShortcutInfo...
,D/KeyguardModel( 1142): handleShortcutListChanged...
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdae20 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10304 #1
I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
I/InteractionManagerConfigurator(  967): com.test.thalitest isn't inclued in dragdropPackageList
D/VoicemailCleanupService( 1767): Cleaning up data for package: com.test.thalitest
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5480 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdae20 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{42c6d288 u0 com.lge.launcher2/.Launcher t1} time:282520
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
D/HyLog   ( 5480): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5480): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5480): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 2905K, 9% free 72392K/78936K, paused 22ms, total 22ms
,D/dalvikvm( 1487): GC_CONCURRENT freed 5653K, 9% free 60777K/66612K, paused 1ms+3ms, total 28ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/LGEmail ( 5480): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/dalvikvm(  967): GC_EXPLICIT freed 613K, 51% free 29945K/61100K, paused 3ms+9ms, total 225ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/LGEmail ( 5480): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:6.30.33]
E/LGEmail ( 5480): Email Not Started (at LGEmailContentProvider.java query 509)[v:6.30.33]
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,D/LGEmail ( 5480): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/AndroidRuntime( 5421): Shutting down VM
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/dalvikvm( 5421): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,W/BaseRuntimeLoader( 5480): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5480): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5480): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5480): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/PackageChangeReceiver( 5480): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/ActivityManager(  967): Killing 4710:com.android.calendar/u0a15 (adj 15): empty #17
D/PackageIntentReceiver( 2563): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2563): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2563): Delete mPackageMame : com.test.thalitest
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/IcingCorporaProvider( 2640): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdae20 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/ActivityManager(  967): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5504 uid=10073 gids={50073, 3003, 1028, 1015}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,D/HyLog   ( 5504): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5504): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5504): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@42863f20 time:282767
,I/IcingCorporaProvider( 2640): UpdateCorporaTask done [took 81 ms] updated apps [took 81 ms] 
,E/SQLiteDatabase( 5504): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5504): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5504): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5504): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5504): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5504): 	at aJh.a(Scopes.java:65)
E/SQLiteDatabase( 5504): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5504): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteDatabase( 5504): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteDatabase( 5504): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5504): 	at aGr.a(GellyInjector.java:117)
E/SQLiteDatabase( 5504): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5504): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5504): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteDatabase( 5504): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteDatabase( 5504): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 5504): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 5504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5504): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5504): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 5504): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5504): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5504): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 5504): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 5504): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 5504): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 5504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 5504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5504): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5504): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5504): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5504): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5504): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5504): 	at aJh.a(Scopes.java:65)
E/SQLiteOpenHelper( 5504): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5504): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteOpenHelper( 5504): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteOpenHelper( 5504): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5504): 	at aGr.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5504): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5504): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5504): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteOpenHelper( 5504): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteOpenHelper( 5504): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 5504): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 5504): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5504): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 5504): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 5504): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5504): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5504): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 5504): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 5504): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 5504): Opened ClientFlag.db in read-only mode
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SQLiteDatabase( 5504): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5504): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5504): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5504): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5504): 	at azE.a(Suppliers.java:125)
E/SQLiteDatabase( 5504): 	at ahj.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 5504): threadid=11: thread exiting with uncaught exception (group=0x41826e48)
,I/Process ( 5504): Sending signal. PID: 5504 SIG: 9
E/AndroidRuntime( 5504): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5504): Process: com.google.android.apps.docs, PID: 5504
E/AndroidRuntime( 5504): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 5504): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 5504): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5504): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5504): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5504): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5504): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5504): 	at azE.a(Suppliers.java:125)
E/AndroidRuntime( 5504): 	at ahj.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  967): Process com.google.android.apps.docs (pid 5504) has died.
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdae20 stackId=0, 1 tasks}
,E/SQLiteLog( 2628): (3850) statement aborts at 15: [INSERT INTO t001(f006,f003,f002,f005,f004) VALUES (?,?,?,?,?)] disk I/O error
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
E/SQLiteDatabase( 2628): Error inserting f006=-1 f003= f002=1453903199647 f005=5504 f004=20
E/SQLiteDatabase( 2628): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2628): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2628): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2628): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2628): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2628): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2628): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2628): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2628): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2628): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2628): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2628): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2628): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2628): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2628): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)

```
