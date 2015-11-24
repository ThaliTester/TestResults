#### Test 50388019b17f598_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
V/ConfigFetchTask( 1963): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VRtZeUO1pKyUJhlW4wOxstGQ3qqEPOgao62tzqXjI_0G4DssYNwAZIceu9cKJqUTTqWQfqcp9Vgoe_zyyy9uAPxhpa-ZK84t1alHf7CwS-riOxXe2Dnl6Hq08-54U0b97gKOWdYIq4BhHh4B7mANkdFXV7TJ9Ava85iMJcGCh0kNIQzI8YSgVqV6mrPFsWThaMDJDm
I/GoogleURLConnFactory( 1963): Using platform SSLCertificateSocketFactory
D/dalvikvm( 1557): GC_EXPLICIT freed 843K, 29% free 17775K/24832K, paused 1ms+3ms, total 23ms
I/PeopleContactsSync( 1963): CP2 sync disabled
I/dalvikvm( 1963): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1963): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1963): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
E/DataScheduler( 1963): isDataSchedulerEnabled():false
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1963): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1963): fetch service done; releasing wakelock
I/ConfigFetchService( 1963): stopping self
W/BaseAppContext( 1963): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
W/GAV2    ( 3821): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  967): Killing 3345:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5c3c0 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1963): GC_CONCURRENT freed 1558K, 26% free 18430K/24832K, paused 2ms+2ms, total 22ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1963): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/ActivityManager(  967): Killing 3368:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5c3c0 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2}
D/Icing   ( 1963): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1963): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1161): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
I/ActivityManager(  967): Start proc com.lge.appbox.client:AppBoxCommonService for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService: pid=3881 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
D/HyLog   ( 3881): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3881): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3881): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AppUp4:AppBoxApplication( 3881): AppBoxApplication onCreate()
D/AppUp4:AbstractIntentService( 3881): onCreate
D/AppUp4  ( 3881): config : false
D/AppUp4:AbstractEnvInfo( 3881): Config no : EnvRealInfo
D/AppUp4:AutoProfileManager( 3881): db mvno version : 9
E/AppUp4:AutoProfileManager( 3881): what happen...? prepareValid DB... can't do anything...
W/BaseRuntimeLoader( 3881): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3881): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3881): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3881): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/AppUp4  ( 3881): config : false
D/AppUp4:AbstractServerEnvInfo( 3881): Config no : EnvRealInfo
D/AppUp4:AppBoxCommonService( 3881): onCreate()
D/AppUp4:AppBoxCommonService( 3881): onHandleIntent begin.
D/AppUp4:AppBoxCommonService( 3881): Factory mode : 0
I/AppUp4:NetworkUtils( 3881): Active NetworkInfo : null
D/AppUp4:AppBoxCommonService( 3881): Skip invalid intent of hidden update popup .
D/AppUp4:AppBoxCommonService( 3881): onDestroy()
I/ActivityManager(  967): Killing 3327:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5c3c0 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2}
,E/BatteryObserver( 1161): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1161): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 3896): 
D/AndroidRuntime( 3896): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3896): CheckJNI is OFF
D/dalvikvm( 3896): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3896): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3896): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3896): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3896): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3896): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3896): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3896): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 3896): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3896
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5c3c0 stackId=1, 2 tasks}
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (114 us)
D/dalvikvm(  967): GC_FOR_ALLOC freed 658K, 12% free 27186K/30812K, paused 63ms, total 64ms
I/dalvikvm-heap(  967): Grow heap (frag case) to 29.544MB for 856096-byte allocation
D/dalvikvm(  967): GC_FOR_ALLOC freed 96K, 12% free 27927K/31652K, paused 107ms, total 107ms
I/dalvikvm-heap(  967): Grow heap (frag case) to 30.268MB for 856096-byte allocation
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{42c5c3c0 stackId=1, 2 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  967): Waited long enough for: ServiceRecord{43191970 u0 com.lge.slideaside/.MainService}
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/AndroidRuntime( 3896): Shutting down VM
I/SlideAside( 3440): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 3896): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/UsbSettingsControl( 2506): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2506): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3440): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3440): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5c3c0 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{4323d2a0 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  967): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3918 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{4323d2a0 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/HyLog   ( 3918): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3918): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3918): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 3918): Binding Chromium to the background looper Looper (main, tid 1) {4287ac58}
I/chromium( 3918): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3918): Initializing chromium process, renderers=0
W/chromium( 3918): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3918): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3918): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3918): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3918): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3918): Remote Branch: 
I/Adreno-EGL( 3918): Local Patches: 
I/Adreno-EGL( 3918): Reconstruct Branch: 
I/dalvikvm( 3918): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3918): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3918): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3918): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3918): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3918): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3918): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3918): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3918): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3918): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3918): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3918): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3918): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3918): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3918): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3918): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3918): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3918): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3918): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3918): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,W/BaseRuntimeLoader( 3918): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3918): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3918): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3918): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 3918): Enabling debug mode 0
W/AwContents( 3918): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 3918): Timeline: Activity_idle id: android.os.BinderProxy@4287c510 time:41918
I/ActivityManager(  967): Displayed com.example.hello/.MainActivity: +389ms
I/chromium( 3918): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3918): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 3918): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 3918): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x428805d0
D/dalvikvm( 3918): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x428805d0
D/jxcore_app_log( 3918): JniHelper::setJavaVM(0x4173e838), pthread_self() = 1627572904
D/JX-Cordova( 3918): jxcore cordova android initializing
W/jxcore-log( 3918): Initializing JXcore engine
W/jxcore-log( 3918): JXcore engine is ready
W/jxcore-log( 3918): Starting JXcore engine
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{4323d2a0 u0 com.example.hello/.MainActivity t3} time:42319
D/ActivityManager(  967): no-history finish of ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{43271170 ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2 f}
D/UsbSettings( 2506): [AUTORUN] onStop()
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4323d2a0 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1161): usb Uevent not necessary.
W/jxcore-log( 3918): Platform android
W/jxcore-log( 3918): 
W/jxcore-log( 3918): Process ARCH arm
W/jxcore-log( 3918): 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/jxcore-log( 3918): JXcore Cordova bridge is ready!
I/jxcore-log( 3918): 
,W/jxcore-log( 3918): JXcore engine is started
,I/chromium( 3918): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 3918): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore-log( 3918): >> LGE-LG-D802
E/jxcore-log( 3918): 
,I/jxcore-log( 3918): Total memory 1943035904
I/jxcore-log( 3918): 
I/jxcore-log( 3918): Free memory 460886016
I/jxcore-log( 3918): 
I/jxcore-log( 3918): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3918): 
,I/jxcore-log( 3918): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3918): 
,I/jxcore-log( 3918): userPath [ 'www' ]
I/jxcore-log( 3918): 
,I/jxcore-log( 3918): Size 1080 1776
I/jxcore-log( 3918): 
,I/jxcore-log( 3918): Screen Brightness 255
I/jxcore-log( 3918): 
,E/jxcore-log( 3918): Dummy Error Log.
E/jxcore-log( 3918): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 3918): getBuffer is called!!!!
I/jxcore-log( 3918): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1161): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/CheckinService( 1963): Done disabling old GoogleServicesFramework version
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1161): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3821): Thread[GAThread,5,main]: No campaign data found.
E/BatteryObserver( 1161): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1161): GC_CONCURRENT freed 1271K, 6% free 25440K/26888K, paused 7ms+5ms, total 48ms
,I/ConfigService( 1557): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1161): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Killing 3390:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5c3c0 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4323d2a0 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1161): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.554031 Y: -0.388763 Z: 9.751465 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.554031 .y:-0.388763 .z:9.751465
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.554031 Y: -0.382751 Z: 9.731552 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.554031 .y:-0.382751 .z:9.731552
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431a8d08:true
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  967): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  967): Message: 2
D/WifiService(  967): New client listening to asynchronous messages
,D/WifiService(  967): setWifiEnabled: false pid=3918, uid=10311
,E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3918): ****TEST TOOK:  5042  ms ****
I/jxcore-log( 3918): 
,I/jxcore-log( 3918): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3918): 
I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
,D/AndroidRuntime( 3978): 
D/AndroidRuntime( 3978): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3978): CheckJNI is OFF
,D/dalvikvm( 3978): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3978): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 3978): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3978): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3978): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3978): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/BatteryObserver( 1161): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,E/memtrack( 3978): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3978): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 3978): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  967): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  967): Killing 3918:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  967): Force removing ActivityRecord{4323d2a0 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4323d2a0 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4323d2a0 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  967):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c5c3c0 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  967): moveHomeStack:
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
,V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
,D/WifiService(  967): Client connection lost with reason: 4
,I/WindowState(  967): WIN DEATH: Window{42b37268 u0 com.example.hello/com.example.hello.MainActivity}
,W/InputDispatcher(  967): channel '42b37268 com.example.hello/com.example.hello.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  967): channel '42b37268 com.example.hello/com.example.hello.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  967): Attempted to unregister already unregistered input channel '42b37268 com.example.hello/com.example.hello.MainActivity (server)'
I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2506): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2506): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2506): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2506): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,I/[LGHome]EVENT( 1491): [Launcher.java:4947:onStart()]onStart
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4306eae0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/PackageSettings(  967): Skipping PackageSetting{42d36f08 com.test.thalitest/10304} due to missing metadata
,I/ActivityManager(  967): Force stopping com.example.hello appid=10311 user=0: pkg removed
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1491): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/KeyguardModel( 1145): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3440): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3440): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,W/System.err( 2557): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
I/[LGHome]LGActivityUtil( 1491): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/AppUp4:Utils( 3602): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3602): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,I/AppUp4  ( 3602):  isExcludedPackage  packagename = com.example.hello
,I/[LGHome]EVENT( 1491): [Launcher.java:868:onResume()]onResume end
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
W/GeofencerStateMachine( 1426): Ignoring removeGeofence because network location is disabled.
W/System.err( 2557): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2557): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2557): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
,W/System.err( 2557): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2557): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2557): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2557): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2557): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2557): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2557): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2557): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2557): 	at dalvik.system.NativeStart.main(Native Method)
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppUp4  ( 3602):  isExcludedPackage TRUE : com.example.hello
I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/dalvikvm( 2575): GC_EXPLICIT freed 3970K, 27% free 18151K/24832K, paused 1ms+2ms, total 48ms
I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,D/[BNRAppListMgrReceiver]( 3314): android.intent.action.PACKAGE_REMOVED : com.example.hello
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
,D/VoicemailCleanupService( 1817): Cleaning up data for package: com.example.hello
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  967): GC_EXPLICIT freed 967K, 11% free 28883K/32452K, paused 2ms+10ms, total 122ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 114ms
,I/PackageChangeReceiver( 3791): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1145): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1145): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1145): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/PackageIntentReceiver( 2506): Not supported Hotkey customization function 
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
D/administrator(  967): Handling package changes for user 0
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4012 uid=10090 gids={50090}
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/HideNavigationAppsReceiver( 2506): Receive package name : com.example.hello
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/HideNavigationAppsReceiver( 2506): Delete mPackageMame : com.example.hello
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HyLog   ( 4012): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4012): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4012): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/IcingCorporaProvider( 2575): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/LockScreenSettings( 4012): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm(  967): GC_EXPLICIT freed 435K, 12% free 28841K/32452K, paused 3ms+10ms, total 146ms
,I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  967): com.example.hello isn't inclued in dragdropPackageList
D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10311 #1
,D/AndroidRuntime( 3978): Shutting down VM
D/KeyguardModel( 1145): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1145): createShortcutInfo...
,D/dalvikvm( 3978): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,I/ActivityManager(  967): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4027 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/KeyguardModel( 1145): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1145): createShortcutInfo...
,D/KeyguardModel( 1145): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1145): createShortcutInfo...
D/HyLog   ( 4027): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4027): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4027): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1145): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1145): createShortcutInfo...
,D/KeyguardModel( 1145): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1145): createShortcutInfo...
,D/dalvikvm( 1491): GC_CONCURRENT freed 5471K, 9% free 61011K/66672K, paused 2ms+3ms, total 21ms
,D/dalvikvm( 1491): WAIT_FOR_CONCURRENT_GC blocked 10ms
W/ContextImpl( 4027): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,D/dalvikvm( 1145): GC_FOR_ALLOC freed 5649K, 12% free 69734K/78460K, paused 25ms, total 25ms
,I/dalvikvm( 3687): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3687): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3687): VFY: replacing opcode 0x6e at 0x0013
,E/NetworkScheduler.SchedulerReceiver( 1557): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1557): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,D/KeyguardModel( 1145): handleShortcutListChanged...
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/KeyguardModel( 1145): handleShortcutListChanged...
,I/ActivityManager(  967): Killing 3277:com.google.android.music:main/u0a107 (adj 15): empty #17
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
F/ActivityManager(  967): Service ServiceRecord{43250a50 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4330b6f8 3277:com.google.android.music:main/u0a107} not same as in map: null
I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
D/AccountUtils( 1963): Clearing selected account for com.example.hello
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,F/ActivityManager(  967): Service ServiceRecord{43249a30 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4330b6f8 3277:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
,E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/PackageIntentReceiver( 2506): Not supported Hotkey customization function 
I/ActivityManager(  967): Killing 2081:android.process.media/u0a23 (adj 15): empty #17
,D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/LocationSettingsChecker( 1963): Removing dialog suppression flag for package com.example.hello
I/ActivityManager(  967): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4051 uid=10065 gids={50065, 1028, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/ActivityManager(  967): Delaying start of: ServiceRecord{432d2fd0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/HyLog   ( 4051): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4051): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4051): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/IcingCorporaProvider( 2575): UpdateCorporaTask done [took 249 ms] updated apps [took 249 ms] 
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ConfigService( 1557): onCreate
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/ConfigFetchService( 1963): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,W/BaseAppContext( 1963): Using Auth Proxy for data requests.
,W/BaseAppContext( 1963): Using Auth Proxy for data requests.
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
D/GOOGLEHELP_CompatibleDatabase( 1963): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1963): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1} time:49001
D/gH_MetricsDatabase( 1963): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1963): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/PeopleContactsSync( 1963): CP2 sync disabled
,D/Documents( 4051): Loading roots for com.android.externalstorage.documents
,I/Icing   ( 1963): doRemovePackageData com.example.hello
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,D/GOOGLEHELP_CompatibleDatabase( 1963): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1963): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1963): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  967): Killing 3760:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/WeatherAncestor( 1888): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:26:42
D/GOOGLEHELP_CompatibleDatabase( 1963): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1963): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/UpdateThreadPoolManager( 1888): 2 : This is isUpdating : false
,D/GOOGLEHELP_CompatibleDatabase( 1963): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1963): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1963): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/WeatherQuickCover( 1888): 2 : quick cover state : opened : 0
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
D/WeatherService( 1888): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1888): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1888): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1888): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherAncestor( 1888): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:26:42
D/WeatherService( 1888): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/GOOGLEHELP_CompatibleDatabase( 1963): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/WeatherQuickCover( 1888): 2 : quick cover state : opened : 0
D/Weather.Utils( 1888): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1888): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1888): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1888): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1888): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1888): 2 : This is isUpdating : false
D/WeatherService( 1888): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1888): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1888): 2 : Map key string is -2
D/lim     ( 1888): 2 : time = 18:26
I/WeatherReflect( 1888): Model Name : LG-D802
D/WeatherTheme( 1888): 2 : exactly same view!
D/WeatherTheme( 1888): 2 : widgetId = 1 : widgetSize = 1 : Do not refresh any widget.
D/WeatherQuickCover( 1888): 2 : quick cover state : opened : 0
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,D/Weather.Utils( 1888): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/ActivityManager(  967): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4075 uid=10005 gids={50005, 1028, 1015, 1023}
D/WeatherService( 1888): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1888): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/HyLog   ( 4075): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4075): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4075): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 3195:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
,D/ExternalStorage( 4075): After updating volumes, found 1 active roots
,D/Documents( 4051): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 4051): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager(  967): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4087 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager( 1491): Timeline: Activity_idle id: android.os.BinderProxy@42877020 time:49138
I/ActivityManager(  967): Killing 3881:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/HyLog   ( 4087): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4087): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4087): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
,E/SQLiteDatabase( 1963): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.o.run(SourceFile:726)
,W/dalvikvm( 1963): threadid=24: thread exiting with uncaught exception (group=0x41839e48)
E/AndroidRuntime( 1963): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 1963): Process: com.google.android.gms, PID: 1963
E/AndroidRuntime( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1963): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/AndroidRuntime( 1963): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/AndroidRuntime( 1963): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/AndroidRuntime( 1963): 	at com.google.android.gms.drive.database.o.run(SourceFile:726)
,E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  967): Delaying start of: ServiceRecord{43151180 u0 com.android.providers.downloads/.DownloadService}
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1161): usb Uevent not necessary.
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=66 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
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
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=66 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
W/DriveInitializer( 1963): Awaiting to be initialized
,W/DriveInitializer( 1963): Background init thread started
,E/SQLiteDatabase( 1963): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.k.a(SourceFile:242)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/DocListDatabase( 1963): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/DocListDatabase( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/DocListDatabase( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/DocListDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/DocListDatabase( 1963): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/DocListDatabase( 1963): 	at com.google.android.gms.drive.database.m.b(SourceFile:711,)
E/DocListDatabase( 1963): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/DocListDatabase( 1963): 	at com.google.android.gms.drive.database.k.a(SourceFile:242)
E/DocListDatabase( 1963): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1963): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1963): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 1963): Background init thread ended
W/dalvikvm( 1963): threadid=37: thread exiting with uncaught exception (group=0x41839e48)
I/Process ( 1963): Sending signal. PID: 1963 SIG: 9
E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
I/ActivityManager(  967): Process com.google.android.gms (pid 1963) has died.
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
I/ConfigService( 1557): onDestroy
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c608c8 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cb3ba8 u0 com.lge.launcher2/.Launcher t1}
E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
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
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=66 id=0 flags=0x0 priv=0
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
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
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
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=66 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
,E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
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
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
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
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=66 id=0 flags=0x0 priv=0
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
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
,E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=66 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
,E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
,E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=66 id=0 flags=0x0 priv=0
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
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1161): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!

```
