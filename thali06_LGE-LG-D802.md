#### Test 5038801932cd575_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1946): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1946): launchTask
W/dalvikvm( 1946): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1946): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WL4XHhDP436hlgykqTgTOUCtwWagkIQrTtGpVQVdrM-hfN22BF-w5HnhYSAk1iNJqqjWWY4hFV-pOVTwwrKMVss3TwY_HJB2l2y-BLDLIJrCjrn2DMPNVFzxVJnUysIuuLVlR8OcG-6baRktPVCg-zk8xY0HBeK8s7UAMJe4YDI-bnrvXFG1eVg0g_N0wSXtxhVjWd
I/GoogleURLConnFactory( 1946): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1946): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1946): Failed to find package metadata for com.example.hello
D/Vision  ( 1946): No vision deps
W/GAV2    ( 3843): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  961): Killing 3402:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430af188 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
E/DataScheduler( 1946): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1946): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1946): fetch service done; releasing wakelock
I/ConfigFetchService( 1946): stopping self
D/dalvikvm( 1551): GC_EXPLICIT freed 891K, 29% free 17803K/24832K, paused 2ms+5ms, total 38ms
I/PeopleContactsSync( 1946): CP2 sync disabled
I/dalvikvm( 1946): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1946): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1946): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
I/ActivityManager(  961): Waited long enough for: ServiceRecord{430b15d8 u0 com.lge.slideaside/.MainService}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Icing   ( 1946): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1946): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1946): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1946): GC_CONCURRENT freed 1573K, 26% free 18433K/24832K, paused 2ms+4ms, total 35ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  961): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/AndroidRuntime( 3908): 
D/AndroidRuntime( 3908): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3908): CheckJNI is OFF
D/dalvikvm( 3908): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3908): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3908): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3908): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3908): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3908): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3908): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3908): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 3908): Calling main entry com.android.commands.am.Am
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3908
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430af188 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (122 us)
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  961): GC_FOR_ALLOC freed 1266K, 10% free 27958K/30992K, paused 71ms, total 71ms
I/dalvikvm-heap(  961): Grow heap (frag case) to 30.298MB for 856096-byte allocation
D/AndroidRuntime( 3908): Shutting down VM
D/dalvikvm( 3908): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 4ms
D/UsbSettingsControl( 2460): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2460): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  961): resumeTopActivityLocked: Pausing null
V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  961): setFocusedStack: mFocusedStack=ActivityStack{430af188 stackId=1, 2 tasks}
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  961): startService SlideAside
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430af188 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Restarting ActivityRecord{43021518 u0 com.example.hello/.MainActivity t3}
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
I/ActivityManager(  961): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3926 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{43021518 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/SlideAside( 3495): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 1ms+2ms, total 34ms
D/HyLog   ( 3926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3926): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 22ms
I/SlideAside( 3495): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3495): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 20ms
V/WebViewChromium( 3926): Binding Chromium to the background looper Looper (main, tid 1) {42813978}
I/chromium( 3926): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3926): Initializing chromium process, renderers=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/chromium( 3926): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3926): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3926): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3926): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3926): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3926): Remote Branch: 
I/Adreno-EGL( 3926): Local Patches: 
I/Adreno-EGL( 3926): Reconstruct Branch: 
I/dalvikvm( 3926): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3926): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3926): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3926): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3926): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3926): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3926): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3926): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3926): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3926): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3926): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3926): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3926): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3926): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3926): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3926): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3926): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3926): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3926): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3926): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 3926): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3926): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3926): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3926): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 3926): Enabling debug mode 0
W/AwContents( 3926): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  961): Displayed com.example.hello/.MainActivity: +338ms
I/ActivityManager( 3926): Timeline: Activity_idle id: android.os.BinderProxy@42815608 time:42967
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/CheckinService( 1946): Done disabling old GoogleServicesFramework version
I/chromium( 3926): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3926): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 3926): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 3926): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x428192f0
D/dalvikvm( 3926): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x428192f0
D/jxcore_app_log( 3926): JniHelper::setJavaVM(0x416d6838), pthread_self() = 1631890728
D/JX-Cordova( 3926): jxcore cordova android initializing
W/jxcore-log( 3926): Initializing JXcore engine
W/jxcore-log( 3926): JXcore engine is ready
W/jxcore-log( 3926): Starting JXcore engine
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/WifiController(  961): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{43021518 u0 com.example.hello/.MainActivity t3} time:43422
D/UsbSettings( 2460): [AUTORUN] onStop()
D/ActivityManager(  961): no-history finish of ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  961): Finishing activity token=Token{431e82b0 ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43021518 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 3926): Platform android
W/jxcore-log( 3926): 
W/jxcore-log( 3926): Process ARCH arm
W/jxcore-log( 3926): 
I/jxcore-log( 3926): JXcore Cordova bridge is ready!
I/jxcore-log( 3926): 
W/jxcore-log( 3926): JXcore engine is started
I/chromium( 3926): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 3926): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore-log( 3926): >> LGE-LG-D802
E/jxcore-log( 3926): 
,I/jxcore-log( 3926): Total memory 1943035904
I/jxcore-log( 3926): 
I/jxcore-log( 3926): Free memory 485138432
I/jxcore-log( 3926): 
I/jxcore-log( 3926): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3926): 
,I/jxcore-log( 3926): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3926): 
,I/jxcore-log( 3926): userPath [ 'www' ]
I/jxcore-log( 3926): 
,I/jxcore-log( 3926): Size 1080 1776
I/jxcore-log( 3926): 
,I/jxcore-log( 3926): Screen Brightness 255
I/jxcore-log( 3926): 
,E/jxcore-log( 3926): Dummy Error Log.
E/jxcore-log( 3926): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/WifiController(  961): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/jxcore-log( 3926): getBuffer is called!!!!
I/jxcore-log( 3926): 
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  961): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  961): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/GAV2    ( 3843): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  961): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1156): GC_CONCURRENT freed 1279K, 6% free 25439K/26896K, paused 4ms+2ms, total 67ms
,I/ConfigService( 1551): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  961): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.558884 Y: -0.382553 Z: 9.727280 
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.560013 Y: -0.370331 Z: 9.719513 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.558884 .y:-0.382553 .z:9.727280
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
I/ActivityManager(  961): Killing 3357:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430af188 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43021518 u0 com.example.hello/.MainActivity t3}
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.576477 Y: -0.386642 Z: 9.741364 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.576477 .y:-0.386642 .z:9.741364
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/BluetoothManagerService(  961): Message: 20
,D/BluetoothManagerService(  961): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@430eddc8:true
,D/BluetoothManagerService(  961): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  961): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  961): Message: 2
D/WifiService(  961): New client listening to asynchronous messages
,D/WifiService(  961): setWifiEnabled: false pid=3926, uid=10311
,E/WifiService(  961): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  961): setWifiEnabled startWifiDelaySendMsg true
I/jxcore-log( 3926): ****TEST TOOK:  5044  ms ****
I/jxcore-log( 3926): 
I/jxcore-log( 3926): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3926): 
,D/AndroidRuntime( 4013): 
D/AndroidRuntime( 4013): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4013): CheckJNI is OFF
,D/dalvikvm( 4013): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4013): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4013): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4013): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4013): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4013): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/memtrack( 4013): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4013): failed to load memtrack module: -2
,D/AndroidRuntime( 4013): Calling main entry com.android.commands.pm.Pm
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  961): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  961): Killing 3926:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  961): Force removing ActivityRecord{43021518 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{43021518 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{43021518 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  961):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430af188 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  961): moveHomeStack:
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
,I/WindowState(  961): WIN DEATH: Window{4325dd38 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  961): Client connection lost with reason: 4
,W/PackageSettings(  961): Skipping PackageSetting{42ccbce8 com.test.thalitest/10304} due to missing metadata
,V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  961): resumeTopActivityLocked: Resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/UsbSettings( 2460): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/ActivityManager(  961): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
,I/InputReader(  961): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
,I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
V/UsbSettings( 2460): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
E/SlideAside( 3495): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
V/UsbSettings( 2460): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2460): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
I/SlideAside( 3495): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppUp4:Utils( 3591): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3591): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 3591):  isExcludedPackage  packagename = com.example.hello
W/GeofencerStateMachine( 1425): Ignoring removeGeofence because network location is disabled.
W/System.err( 2536): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 2536): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
W/System.err( 2536): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System.err( 2536): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2536): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2536): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2536): 	at android.os.Looper.loop(Looper.java:136)
,W/System.err( 2536): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2536): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2536): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2536): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
,W/System.err( 2536): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2536): 	at dalvik.system.NativeStart.main(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{4303e568 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,D/AppUp4  ( 3591):  isExcludedPackage TRUE : com.example.hello
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/[BNRAppListMgrReceiver]( 3344): android.intent.action.PACKAGE_REMOVED : com.example.hello
D/dalvikvm(  961): GC_EXPLICIT freed 1100K, 10% free 28854K/31832K, paused 3ms+10ms, total 133ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 2548): GC_EXPLICIT freed 4007K, 27% free 18151K/24832K, paused 17ms+2ms, total 135ms
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
D/administrator(  961): Handling package changes for user 0
,D/VoicemailCleanupService( 1824): Cleaning up data for package: com.example.hello
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
,I/PackageChangeReceiver( 3823): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
,D/PackageIntentReceiver( 2460): Not supported Hotkey customization function 
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/HideNavigationAppsReceiver( 2460): Receive package name : com.example.hello
,D/HideNavigationAppsReceiver( 2460): Delete mPackageMame : com.example.hello
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/ActivityManager(  961): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4048 uid=10090 gids={50090}
,D/BackupManagerService(  961): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/InteractionManagerConfigurator(  961): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  961): com.example.hello isn't inclued in dragdropPackageList
V/BackupManagerService(  961): removePackageParticipantsLocked: uid=10311 #1
I/IcingCorporaProvider( 2548): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/HyLog   ( 4048): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4048): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4048): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  961): GC_EXPLICIT freed 451K, 10% free 28810K/31832K, paused 2ms+11ms, total 146ms
,I/ActivityManager(  961): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4061 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/LockScreenSettings( 4048): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
,D/AndroidRuntime( 4013): Shutting down VM
,D/dalvikvm( 4013): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
,D/dalvikvm( 1490): GC_CONCURRENT freed 5451K, 9% free 61005K/66676K, paused 1ms+3ms, total 33ms
,D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
,D/HyLog   ( 4061): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4061): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4061): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/ContextImpl( 4061): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,D/KeyguardModel( 1142): handleShortcutListChanged...
,D/KeyguardModel( 1142): handleShortcutListChanged...
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/dalvikvm( 3672): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3672): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3672): VFY: replacing opcode 0x6e at 0x0013
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/IcingCorporaProvider( 2548): UpdateCorporaTask done [took 138 ms] updated apps [took 138 ms] 
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
E/NetworkScheduler.SchedulerReceiver( 1551): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1551): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
I/ActivityManager(  961): Killing 3302:com.google.android.music:main/u0a107 (adj 15): empty #17
I/ActivityManager(  961): Killing 2979:android.process.media/u0a23 (adj 15): empty #17
E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
,F/ActivityManager(  961): Service ServiceRecord{4326da48 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432aebc0 3302:com.google.android.music:main/u0a107} not same as in map: null
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
F/ActivityManager(  961): Service ServiceRecord{431f1520 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432aebc0 3302:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
D/PackageBroadcastService( 1946): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1946): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
D/WeatherAncestor( 1873): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 22:46:47
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
D/UpdateThreadPoolManager( 1873): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1873): 2 : quick cover state : opened : 0
D/WeatherService( 1873): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1873): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1873): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1873): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherAncestor( 1873): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 22:46:47
,D/WeatherService( 1873): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/PackageIntentReceiver( 2460): Not supported Hotkey customization function 
D/WeatherQuickCover( 1873): 2 : quick cover state : opened : 0
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/LocationSettingsChecker( 1946): Removing dialog suppression flag for package com.example.hello
,D/Weather.Utils( 1873): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1873): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1873): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1873): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1873): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
D/UpdateThreadPoolManager( 1873): 2 : This is isUpdating : false
D/WeatherService( 1873): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1873): 2 : buildUpdate, appWidgetId: 1
,I/ActivityManager(  961): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4090 uid=10065 gids={50065, 1028, 4002}
D/WeatherReflect( 1873): 2 : Map key string is -2
D/lim     ( 1873): 2 : time = 22:46
I/WeatherReflect( 1873): Model Name : LG-D802
D/WeatherTheme( 1873): 2 : exactly same view!
D/WeatherTheme( 1873): 2 : widgetId = 1 : widgetSize = 1 : Do not refresh any widget.
D/WeatherQuickCover( 1873): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1873): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,D/HyLog   ( 4090): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4090): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4090): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  961): Delaying start of: ServiceRecord{4329fdd0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,D/WeatherService( 1873): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1873): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ConfigService( 1551): onCreate
,I/ConfigFetchService( 1946): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1946): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1946): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1946): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1946): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1946): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/Icing   ( 1946): doRemovePackageData com.example.hello
,I/PeopleContactsSync( 1946): CP2 sync disabled
,W/BaseAppContext( 1946): Using Auth Proxy for data requests.
,D/Documents( 4090): Loading roots for com.android.externalstorage.documents
,I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1} time:50017
,D/GOOGLEHELP_CompatibleDatabase( 1946): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1946): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1946): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  961): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4109 uid=10005 gids={50005, 1028, 1015, 1023}
,D/HyLog   ( 4109): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4109): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4109): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/GOOGLEHELP_CompatibleDatabase( 1946): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1946): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1946): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1946): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
I/ActivityManager(  961): Killing 3778:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  961): Killing 3215:com.google.android.talk/u0a77 (adj 15): empty #17
D/GOOGLEHELP_CompatibleDatabase( 1946): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1946): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
D/ExternalStorage( 4109): After updating volumes, found 1 active roots
D/Documents( 4090): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4090): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager(  961): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4122 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@4280eff0 time:50082
,I/ActivityManager(  961): Killing 3796:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/HyLog   ( 4122): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4122): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4122): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Delaying start of: ServiceRecord{432a1ae8 u0 com.android.providers.downloads/.DownloadService}
,E/SQLiteDatabase( 4122): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4122): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4122): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4122): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4122): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4122): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4122): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4122): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4122): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4122): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4122): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4122): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4122): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4122): failed to open database external.db
E/LGMediaProvider( 4122): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4122): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4122): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4122): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4122): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4122): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4122): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4122): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4122): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4122): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4122): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4122): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4122): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4122): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4122): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4122): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4122): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4122): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4122): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4122): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4122): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4122): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4122): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4122): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4122): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4122): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4122): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4122): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4122): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4122): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4122): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4122): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4122): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4122): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4122): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4122): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4122): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4122): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4122): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4122): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4122): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4122): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4122): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4122): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4122): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4122): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4122): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4122): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4122): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4122): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4122): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4122): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4122): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4122): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
W/System.err( 4122): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4122): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4122): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4122): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4122): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4122): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4122): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4122): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4122): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4122): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4122): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4122): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4122): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4122): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4122): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4122): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4122): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4122): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
W/System.err( 4122): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4122): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4122): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4122): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4122): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/FileUtils( 1946): Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
W/System.err( 4122): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4122): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4122): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4122): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4122): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4122): 	... 12 more
I/Process ( 4122): Sending signal. PID: 4122 SIG: 9
I/ActivityManager(  961): Process android.process.media (pid 4122) has died.
I/ActivityManager(  961): Start proc android.process.media for restart android.process.media: pid=4136 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42beb228 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bca928 u0 com.lge.launcher2/.Launcher t1}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/HyLog   ( 4136): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4136): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4136): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/DriveInitializer( 1946): Background init thread started
,W/DriveInitializer( 1946): Awaiting to be initialized
,E/SQLiteLog( 1946): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock112] disk I/O error
,E/SQLiteDatabase( 4136): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4136): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4136): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4136): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4136): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4136): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4136): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4136): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4136): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4136): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4136): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4136): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4136): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4136): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4136): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4136): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4136): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4136): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4136): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4136): 	at dalvik.system.NativeStart.main(Native Method)
E/DocListDatabase( 1946): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1946): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1946): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1946): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/DocListDatabase( 1946): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/DocListDatabase( 1946): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1946): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/DocListDatabase( 1946): 	at com.google.android.gms.drive.da,tabase.k.a(SourceFile:520)
E/DocListDatabase( 1946): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1946): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/LGMediaProvider( 4136): failed to open database external.db
E/LGMediaProvider( 4136): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4136): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4136): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4136): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4136): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4136): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4136): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4136): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4136): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4136): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4136): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4136): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4136): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4136): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4136): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4136): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4136): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4136): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4136): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4136): 	at dalvik.system.NativeStart.main(Native Method)
W/DriveInitializer( 1946): Background init thread ended
E/SQLiteLog( 1946): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 1946): threadid=27: thread exiting with uncaught exception (group=0x417d1e48)
,E/DriveAsyncService( 1946): disk I/O error (code 3850)
E/DriveAsyncService( 1946): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1946): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1946): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1946): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1946): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1946): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1946): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1946): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1946): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 1946): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1946): Process: com.google.android.gms, PID: 1946
E/AndroidRuntime( 1946): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1946): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1946): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/AndroidRuntime( 1946): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 1946): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1946): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/AndroidRuntime( 1946): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1946): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 1946): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=36 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!

```
