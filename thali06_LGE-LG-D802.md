#### Test 50388019193a02f_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1935): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1935): launchTask
W/dalvikvm( 1935): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1935): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Xic7rZwv_zJ1tDI9zM5ZsqgssQyt2XZoZxMFBGaJL2v_HZik22wx-EfydQKt3fV3f2unvc1mNJrjrxl8bqA4lokchMfmlnQ0vnxqCVhhJkl808GWkt3qUVAVUVDrJ0BNuudCSczep11-nriE03ftSkt2F7FUdrgwwBdCbr2RS8I-swvB4qOsIrEIP6TGUDbR7UxrD7
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1935): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1935): Failed to find package metadata for com.example.hello
D/Vision  ( 1935): No vision deps
I/GoogleURLConnFactory( 1935): Using platform SSLCertificateSocketFactory
I/PeopleContactsSync( 1935): CP2 sync disabled
I/dalvikvm( 1935): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1935): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1935): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1935): Using Auth Proxy for data requests.
W/BaseAppContext( 1935): Using Auth Proxy for data requests.
E/DataScheduler( 1935): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1935): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1935): fetch service done; releasing wakelock
I/ConfigFetchService( 1935): stopping self
D/dalvikvm( 1538): GC_EXPLICIT freed 901K, 29% free 17796K/24832K, paused 3ms+6ms, total 43ms
W/BaseAppContext( 1935): Using Auth Proxy for data requests.
W/BaseAppContext( 1935): Using Auth Proxy for data requests.
W/BaseAppContext( 1935): Using Auth Proxy for data requests.
W/GAV2    ( 3834): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
W/BaseAppContext( 1935): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 3322:com.lge.clock/u0a10 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433204b0 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Icing   ( 1935): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/dalvikvm( 1935): GC_CONCURRENT freed 1554K, 26% free 18451K/24832K, paused 5ms+6ms, total 54ms
D/Icing   ( 1935): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1935): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/ActivityManager(  966): Killing 3370:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433204b0 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  966): Start proc com.lge.appbox.client:AppBoxCommonService for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService: pid=3909 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
D/HyLog   ( 3909): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3909): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3909): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AppUp4:AppBoxApplication( 3909): AppBoxApplication onCreate()
D/AppUp4:AbstractIntentService( 3909): onCreate
D/AppUp4  ( 3909): config : false
D/AppUp4:AbstractEnvInfo( 3909): Config no : EnvRealInfo
D/AppUp4:AutoProfileManager( 3909): db mvno version : 9
E/AppUp4:AutoProfileManager( 3909): what happen...? prepareValid DB... can't do anything...
W/BaseRuntimeLoader( 3909): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3909): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3909): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3909): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/AppUp4  ( 3909): config : false
D/AppUp4:AbstractServerEnvInfo( 3909): Config no : EnvRealInfo
D/AppUp4:AppBoxCommonService( 3909): onCreate()
D/AppUp4:AppBoxCommonService( 3909): onHandleIntent begin.
D/AppUp4:AppBoxCommonService( 3909): Factory mode : 0
I/AppUp4:NetworkUtils( 3909): Active NetworkInfo : null
D/AppUp4:AppBoxCommonService( 3909): Skip invalid intent of hidden update popup .
D/AppUp4:AppBoxCommonService( 3909): onDestroy()
I/ActivityManager(  966): Killing 3351:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433204b0 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 3925): 
D/AndroidRuntime( 3925): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3925): CheckJNI is OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 3925): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3925): Added shared lib libjavacore.so 0x0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 3925): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3925): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3925): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3925): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3925): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3925): failed to load memtrack module: -2
D/AndroidRuntime( 3925): Calling main entry com.android.commands.am.Am
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3925
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433204b0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (99 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  966): GC_FOR_ALLOC freed 815K, 12% free 27202K/30852K, paused 67ms, total 69ms
I/dalvikvm-heap(  966): Grow heap (frag case) to 29.561MB for 856096-byte allocation
D/dalvikvm(  966): GC_FOR_ALLOC freed 116K, 12% free 27926K/31692K, paused 84ms, total 84ms
I/dalvikvm-heap(  966): Grow heap (frag case) to 30.268MB for 856096-byte allocation
D/AndroidRuntime( 3925): Shutting down VM
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{433204b0 stackId=1, 2 tasks}
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/UsbSettingsControl( 2509): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2509): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 3925): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433204b0 stackId=1, 2 tasks}
I/ActivityManager(  966): startService SlideAside
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  966): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3943 uid=10311 gids={50311, 3003, 3001, 3002}
I/SlideAside( 3452): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 2ms+1ms, total 22ms
D/HyLog   ( 3943): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3943): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3943): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 15ms
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
V/WebViewChromium( 3943): Binding Chromium to the background looper Looper (main, tid 1) {42895cb0}
I/chromium( 3943): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3943): Initializing chromium process, renderers=0
I/SlideAside( 3452): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3452): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
W/chromium( 3943): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3943): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3943): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3943): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3943): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3943): Remote Branch: 
I/Adreno-EGL( 3943): Local Patches: 
I/Adreno-EGL( 3943): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  966): Waited long enough for: ServiceRecord{43252390 u0 com.lge.slideaside/.MainService}
I/dalvikvm( 3943): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3943): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3943): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3943): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3943): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3943): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3943): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3943): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3943): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3943): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3943): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3943): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3943): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3943): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3943): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3943): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3943): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3943): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3943): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3943): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/BaseRuntimeLoader( 3943): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3943): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3943): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3943): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 3943): Enabling debug mode 0
,W/AwContents( 3943): nativeOnDraw failed; clearing to background color.
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/ActivityManager(  966): Displayed com.example.hello/.MainActivity: +344ms
,I/ActivityManager( 3943): Timeline: Activity_idle id: android.os.BinderProxy@42897478 time:41451
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/chromium( 3943): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3943): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3943): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3943): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x4289b628
,D/dalvikvm( 3943): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x4289b628
,D/jxcore_app_log( 3943): JniHelper::setJavaVM(0x41758838), pthread_self() = 1632186536
,D/JX-Cordova( 3943): jxcore cordova android initializing
,W/jxcore-log( 3943): Initializing JXcore engine
,W/jxcore-log( 3943): JXcore engine is ready
,W/jxcore-log( 3943): Starting JXcore engine
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3} time:41884
D/ActivityManager(  966): no-history finish of ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{433922e0 ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2509): [AUTORUN] onStop()
,V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,W/jxcore-log( 3943): Platform android
W/jxcore-log( 3943): 
,W/jxcore-log( 3943): Process ARCH arm
W/jxcore-log( 3943): 
,I/jxcore-log( 3943): JXcore Cordova bridge is ready!
I/jxcore-log( 3943): 
,W/jxcore-log( 3943): JXcore engine is started
,I/chromium( 3943): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 3943): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore-log( 3943): >> LGE-LG-D802
E/jxcore-log( 3943): 
,I/jxcore-log( 3943): Total memory 1943035904
I/jxcore-log( 3943): 
I/jxcore-log( 3943): Free memory 461578240
I/jxcore-log( 3943): 
I/jxcore-log( 3943): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3943): 
,I/jxcore-log( 3943): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3943): 
,I/jxcore-log( 3943): userPath [ 'www' ]
I/jxcore-log( 3943): 
,I/jxcore-log( 3943): Size 1080 1776
I/jxcore-log( 3943): 
,I/jxcore-log( 3943): Screen Brightness 255
I/jxcore-log( 3943): 
,E/jxcore-log( 3943): Dummy Error Log.
E/jxcore-log( 3943): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/jxcore-log( 3943): getBuffer is called!!!!
I/jxcore-log( 3943): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1935): Done disabling old GoogleServicesFramework version
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): Killing 3396:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433204b0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3}
,I/GAV2    ( 3834): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1538): onDestroy
,I/ActivityManager(  966): Killing 3302:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  966): Service ServiceRecord{432c4660 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4324e658 3302:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  966): Service ServiceRecord{4327a000 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4324e658 3302:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433204b0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1154): GC_CONCURRENT freed 1266K, 6% free 25457K/26900K, paused 4ms+9ms, total 46ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  966): Message: 20
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42acf708:true
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  966): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  966): Message: 2
,D/WifiService(  966): New client listening to asynchronous messages
,D/WifiService(  966): setWifiEnabled: false pid=3943, uid=10311
,E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  966): setWifiEnabled startWifiDelaySendMsg true
I/jxcore-log( 3943): ****TEST TOOK:  5072  ms ****
I/jxcore-log( 3943): 
I/jxcore-log( 3943): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3943): 
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.573395 Y: -0.400360 Z: 9.766434 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573395 .y:-0.400360 .z:9.766434
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.574081 Y: -0.396118 Z: 9.764587 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.574081 .y:-0.396118 .z:9.764587
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 4020): 
D/AndroidRuntime( 4020): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4020): CheckJNI is OFF
,D/dalvikvm( 4020): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4020): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4020): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4020): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4020): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4020): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 4020): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4020): failed to load memtrack module: -2
,D/AndroidRuntime( 4020): Calling main entry com.android.commands.pm.Pm
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  966): Killing 3943:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  966): Force removing ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{4312d5a0 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  966):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433204b0 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  966): moveHomeStack:
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,I/WindowState(  966): WIN DEATH: Window{430a0c28 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  966): Client connection lost with reason: 4
,W/PackageSettings(  966): Skipping PackageSetting{42d5cee0 com.test.thalitest/10304} due to missing metadata
,V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  966): resumeTopActivityLocked: Resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/UsbSettings( 2509): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/ActivityManager(  966): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,D/dalvikvm( 2580): GC_EXPLICIT freed 3646K, 29% free 17872K/24832K, paused 1ms+4ms, total 34ms
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  966): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
V/UsbSettings( 2509): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
E/SlideAside( 3452): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3452): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
V/UsbSettings( 2509): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2509): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/AppUp4:Utils( 3608): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3608): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,I/AppUp4  ( 3608):  isExcludedPackage  packagename = com.example.hello
,W/System.err( 2567): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/GeofencerStateMachine( 1425): Ignoring removeGeofence because network location is disabled.
,W/System.err( 2567): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2567): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2567): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
,W/System.err( 2567): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2567): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2567): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2567): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
,W/System.err( 2567): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2567): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2567): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
,D/AppUp4  ( 3608):  isExcludedPackage TRUE : com.example.hello
W/System.err( 2567): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2567): 	at dalvik.system.NativeStart.main(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  966): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4052 uid=10090 gids={50090}
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  966): GC_EXPLICIT freed 900K, 12% free 28924K/32516K, paused 4ms+7ms, total 107ms
D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/[BNRAppListMgrReceiver]( 3339): android.intent.action.PACKAGE_REMOVED : com.example.hello
I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
D/HyLog   ( 4052): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4052): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4052): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43097380 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,D/administrator(  966): Handling package changes for user 0
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "mms"
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/LockScreenSettings( 4052): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1140): createShortcutInfo...
,I/PackageChangeReceiver( 3812): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/VoicemailCleanupService( 1822): Cleaning up data for package: com.example.hello
,D/PackageIntentReceiver( 2509): Not supported Hotkey customization function 
,D/dalvikvm(  966): GC_EXPLICIT freed 501K, 12% free 28878K/32516K, paused 3ms+11ms, total 153ms
,D/HideNavigationAppsReceiver( 2509): Receive package name : com.example.hello
,D/HideNavigationAppsReceiver( 2509): Delete mPackageMame : com.example.hello
,D/AndroidRuntime( 4020): Shutting down VM
I/InteractionManagerConfigurator(  966): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  966): com.example.hello isn't inclued in dragdropPackageList
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
D/BackupManagerService(  966): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  966): removePackageParticipantsLocked: uid=10311 #1
D/dalvikvm( 4020): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 1ms+0ms, total 2ms
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/IcingCorporaProvider( 2580): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/KeyguardModel( 1140): handleShortcutListChanged...
I/ActivityManager(  966): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4077 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  966): Killing 3222:com.google.android.talk/u0a77 (adj 15): empty #17
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 4077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4077): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/ContextImpl( 4077): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,D/dalvikvm( 1487): GC_CONCURRENT freed 5282K, 9% free 60996K/66484K, paused 1ms+3ms, total 21ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/dalvikvm( 3693): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
,W/dalvikvm( 3693): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3693): VFY: replacing opcode 0x6e at 0x0013
,I/IcingCorporaProvider( 2580): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 
E/NetworkScheduler.SchedulerReceiver( 1538): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1538): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 5799K, 12% free 69462K/78384K, paused 50ms, total 51ms
,D/PackageBroadcastService( 1935): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1935): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,D/PackageIntentReceiver( 2509): Not supported Hotkey customization function 
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
I/ActivityManager(  966): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4101 uid=10065 gids={50065, 1028, 4002}
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/LocationSettingsChecker( 1935): Removing dialog suppression flag for package com.example.hello
,D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1140): createShortcutInfo...
I/ActivityManager(  966): Delaying start of: ServiceRecord{432983b0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,D/HyLog   ( 4101): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4101): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4101): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardModel( 1140): handleShortcutListChanged...
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
D/GOOGLEHELP_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,I/ConfigService( 1538): onCreate
,I/ConfigFetchService( 1935): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/gH_MetricsDatabase( 1935): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/BaseAppContext( 1935): Using Auth Proxy for data requests.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
D/Documents( 4101): Loading roots for com.android.externalstorage.documents
W/BaseAppContext( 1935): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/GOOGLEHELP_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,I/PeopleContactsSync( 1935): CP2 sync disabled
,D/GOOGLEHELP_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/ActivityManager(  966): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4124 uid=10005 gids={50005, 1028, 1015, 1023}
,D/WifiController(  966): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 295 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Icing   ( 1935): doRemovePackageData com.example.hello
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/ActivityManager(  966): Killing 2982:android.process.media/u0a23 (adj 15): empty #17
,D/WeatherAncestor( 1850): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:46:50
I/ActivityManager(  966): Killing 3770:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/UpdateThreadPoolManager( 1850): 2 : This is isUpdating : false
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/WeatherQuickCover( 1850): 2 : quick cover state : opened : 0
D/WeatherService( 1850): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1850): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1850): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1850): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherAncestor( 1850): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:46:50
D/WeatherService( 1850): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/HyLog   ( 4124): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4124): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4124): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
D/WeatherQuickCover( 1850): 2 : quick cover state : opened : 0
D/Weather.Utils( 1850): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1850): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1850): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1850): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1850): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1850): 2 : This is isUpdating : false
D/WeatherService( 1850): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1850): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1850): 2 : Map key string is -2
D/lim     ( 1850): 2 : time = 18:46
I/WeatherReflect( 1850): Model Name : LG-D802
D/WeatherTheme( 1850): 2 : exactly same view!
D/WeatherTheme( 1850): 2 : widgetId = 1 : widgetSize = 1 : Do not refresh any widget.
D/WeatherQuickCover( 1850): 2 : quick cover state : opened : 0
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/Weather.Utils( 1850): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1850): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1850): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,D/ExternalStorage( 4124): After updating volumes, found 1 active roots
,D/Documents( 4101): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/GOOGLEHELP_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/Documents( 4101): Loading roots for com.android.providers.downloads.documents
,D/GOOGLEHELP_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,D/GOOGLEHELP_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
I/ActivityManager(  966): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4138 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/ActivityManager(  966): Killing 3909:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/HyLog   ( 4138): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
D/HyLog   ( 4138): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4138): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1} time:48602
I/ActivityManager(  966): Delaying start of: ServiceRecord{4364ba80 u0 com.android.providers.downloads/.DownloadService}
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 6651K, 11% free 61672K/69264K, paused 20ms, total 20ms
,E/SQLiteDatabase( 4138): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4138): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4138): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4138): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4138): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4138): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4138): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4138): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4138): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4138): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4138): failed to open database external.db
E/LGMediaProvider( 4138): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4138): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4138): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4138): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4138): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4138): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4138): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4138): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4138): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4138): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4138): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4138): 	at dalvik.system.NativeStart.main(Native Method)
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
E/SQLiteDatabase( 4138): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4138): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4138): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4138): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4138): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4138): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4138): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4138): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4138): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4138): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4138): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4138): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4138): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4138): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4138): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4138): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4138): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4138): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4138): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4138): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4138): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4138): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4138): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4138): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4138): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4138): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4138): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
W/System.err( 4138): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4138): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4138): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4138): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4138): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4138): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4138): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4138): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4138): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4138): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4138): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4138): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
W/System.err( 4138): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4138): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4138): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4138): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4138): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4138): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4138): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4138): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4138): 	... 12 more
I/Process ( 4138): Sending signal. PID: 4138 SIG: 9
I/ActivityManager(  966): Process android.process.media (pid 4138) has died.
,I/ActivityManager(  966): Start proc android.process.media for restart android.process.media: pid=4153 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@42890f98 time:48686
D/HyLog   ( 4153): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4153): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4153): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/DriveInitializer( 1935): Awaiting to be initialized
,W/DriveInitializer( 1935): Background init thread started
,E/SQLiteDatabase( 4153): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4153): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4153): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4153): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4153): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4153): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4153): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4153): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4153): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4153): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4153): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4153): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4153): failed to open database external.db
E/LGMediaProvider( 4153): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4153): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4153): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4153): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4153): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4153): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4153): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4153): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4153): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4153): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4153): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4153): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4153): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4153): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4153): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4153): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4153): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4153): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4153): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4153): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4153): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4153): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4153): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4153): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4153): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4153): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4153): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4153): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4153): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4153): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4153): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4153): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4153): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4153): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4153): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4153): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4153): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4153): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4153): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4153): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4153): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4153): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4153): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4153): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4153): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4153): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4153): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4153): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteLog( 4153): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4153): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4153): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,W/System.err( 4153): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4153): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4153): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4153): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4153): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4153): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4153): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4153): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4153): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 4153): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4153): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4153): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4153): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4153): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4153): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4153): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4153): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
,W/System.err( 4153): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4153): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4153): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4153): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4153): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4153): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4153): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4153): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
,W/System.err( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4153): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4153): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4153): 	... 12 more
,I/Process ( 4153): Sending signal. PID: 4153 SIG: 9
,I/ActivityManager(  966): Process android.process.media (pid 4153) has died.
,I/ActivityManager(  966): Start proc android.process.media for restart android.process.media: pid=4167 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 4167): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4167): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4167): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/SQLiteDatabase( 4167): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4167): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4167): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4167): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4167): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4167): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4167): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4167): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4167): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4167): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4167): failed to open database external.db
E/LGMediaProvider( 4167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4167): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4167): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4167): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4167): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4167): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4167): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4167): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4167): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4167): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4167): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4167): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4167): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4167): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4167): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4167): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4167): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4167): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4167): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4167): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4167): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4167): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4167): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4167): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4167): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4167): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4167): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4167): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4167): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4167): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4167): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4167): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4167): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4167): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4167): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4167): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4167): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4167): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4167): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4167): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4167): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4167): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4167): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteLog( 4167): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4167): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4167): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
W/System.err( 4167): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4167): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
,W/System.err( 4167): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4167): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4167): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4167): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4167): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4167): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
,W/System.err( 4167): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4167): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4167): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4167): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4167): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 4167): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4167): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4167): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4167): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
,W/System.err( 4167): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4167): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4167): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4167): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4167): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
,W/System.err( 4167): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4167): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4167): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4167): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4167): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
,W/System.err( 4167): 	... 12 more
,I/Process ( 4167): Sending signal. PID: 4167 SIG: 9
,I/ActivityManager(  966): Process android.process.media (pid 4167) has died.
,I/ActivityManager(  966): Start proc android.process.media for restart android.process.media: pid=4180 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 4180): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4180): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4180): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/SQLiteDatabase( 4180): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4180): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4180): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4180): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4180): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4180): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4180): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4180): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4180): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4180): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4180): failed to open database external.db
E/LGMediaProvider( 4180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4180): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4180): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4180): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4180): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4180): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4180): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4180): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4180): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4180): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4180): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4180): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4180): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4180): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4180): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4180): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4180): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4180): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4180): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4180): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4180): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4180): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4180): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4180): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4180): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4180): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4180): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4180): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4180): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4180): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4180): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4180): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4180): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4180): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4180): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4180): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4180): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4180): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4180): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4180): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4180): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4180): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4180): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4180): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4180): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4180): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,W/System.err( 4180): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4180): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4180): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4180): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4180): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4180): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4180): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4180): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4180): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4180): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4180): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4180): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4180): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4180): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4180): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
,W/System.err( 4180): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4180): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
W/System.err( 4180): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4180): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4180): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4180): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4180): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4180): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4180): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
,W/System.err( 4180): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4180): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4180): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4180): 	... 12 more
,I/Process ( 4180): Sending signal. PID: 4180 SIG: 9
,I/ActivityManager(  966): Process android.process.media (pid 4180) has died.
,I/ActivityManager(  966): Start proc android.process.media for restart android.process.media: pid=4194 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 4194): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4194): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4194): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/SQLiteDatabase( 4194): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4194): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4194): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4194): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4194): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4194): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4194): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4194): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4194): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4194): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4194): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4194): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4194): failed to open database external.db
E/LGMediaProvider( 4194): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4194): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4194): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4194): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4194): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4194): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4194): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4194): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4194): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4194): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4194): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4194): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4194): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4194): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4194): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4194): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4194): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4194): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4194): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4194): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4194): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4194): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4194): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4194): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4194): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4194): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4194): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4194): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4194): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4194): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4194): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4194): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4194): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4194): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4194): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4194): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4194): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4194): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4194): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4194): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4194): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4194): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4194): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4194): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4194): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4194): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4194): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4194): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteLog( 4194): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4194): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4194): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
W/System.err( 4194): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4194): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4194): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4194): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4194): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
,W/System.err( 4194): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4194): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4194): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4194): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4194): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4194): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
,W/System.err( 4194): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4194): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4194): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4194): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4194): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4194): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
,W/System.err( 4194): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4194): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4194): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4194): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4194): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
,W/System.err( 4194): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4194): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4194): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4194): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4194): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4194): 	... 12 more
,I/Process ( 4194): Sending signal. PID: 4194 SIG: 9
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): Process android.process.media (pid 4194) has died.
,I/ActivityManager(  966): Start proc android.process.media for restart android.process.media: pid=4211 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 4211): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4211): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4211): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SQLiteDatabase( 4211): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4211): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4211): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4211): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4211): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4211): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4211): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4211): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4211): failed to open database external.db
E/LGMediaProvider( 4211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4211): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4211): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4211): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4211): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4211): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4211): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4211): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4211): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4211): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4211): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4211): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4211): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4211): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4211): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4211): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4211): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4211): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4211): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4211): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4211): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4211): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4211): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4211): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4211): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4211): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4211): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4211): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4211): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4211): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteLog( 4211): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4211): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4211): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
W/System.err( 4211): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,W/System.err( 4211): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4211): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4211): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4211): 	at android.os.Looper.loop(Looper.java:136)
,W/System.err( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4211): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4211): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4211): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 4211): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4211): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4211): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4211): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
,W/System.err( 4211): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4211): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4211): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4211): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4211): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
,W/System.err( 4211): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4211): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4211): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4211): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4211): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4211): 	... 12 more
,I/Process ( 4211): Sending signal. PID: 4211 SIG: 9
,I/ActivityManager(  966): Process android.process.media (pid 4211) has died.
,I/ActivityManager(  966): Start proc android.process.media for restart android.process.media: pid=4227 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c600e8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431b7440 u0 com.lge.launcher2/.Launcher t1}
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
,D/HyLog   ( 4227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4227): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 13ms
,E/SQLiteDatabase( 4227): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4227): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4227): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4227): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4227): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4227): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4227): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4227): 	at dalvik.system.NativeStart.main(Native Method)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,E/LGMediaProvider( 4227): failed to open database external.db
E/LGMediaProvider( 4227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4227): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4227): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4227): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4227): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4227): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4227): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4227): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4227): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4227): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4227): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4227): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4227): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4227): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4227): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4227): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4227): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4227): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4227): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4227): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4227): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4227): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4227): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4227): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4227): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4227): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4227): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4227): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4227): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4227): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4227): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4227): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4227): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4227): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4227): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4227): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,W/System.err( 4227): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4227): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4227): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4227): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4227): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4227): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4227): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4227): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 4227): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4227): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4227): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4227): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4227): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
W/System.err( 4227): ,	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4227): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4227): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
,W/System.err( 4227): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4227): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4227): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4227): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4227): ,	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4227): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4227): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
,W/System.err( 4227): 	... 12 more

```
