#### Test 50388019f4ce509_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/EulaProviderUpdateObserver( 2855): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 2855): uri : package:com.example.hello
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1934): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1934): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
--------- beginning of /dev/log/system
I/ActivityManager(  966): Delaying start of: ServiceRecord{43847b98 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ConfigFetchService( 1934): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1934): launchTask
W/dalvikvm( 1934): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1934): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XsuoZLi3Reez5v_4kTY5JiMZcE7Uhd6WhCWpExfKJUFweRNXyphCWOVP2XzmcdT5jaDw3Pd97zyYffBtHJ1L1dAWlgSggM7MKoRSkiotFfhorK0lRX6NxziC4SGwgza92gvAhj5HDXCyXPgMcczEAIiDQQVYSV4lNszKEAPKLzEIYuFBG4fk61h6g2ozpAEIgdgMwI-SVsNcRIT0DkhzBo5WvVHTRs2_XpHIGtybo7ny-2N3E
I/GoogleURLConnFactory( 1934): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1934): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1934): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1934): Failed to find package metadata for com.example.hello
D/Vision  ( 1934): No vision deps
I/PeopleContactsSync( 1934): CP2 sync disabled
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
I/dalvikvm( 1934): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1934): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1934): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
E/DataScheduler( 1934): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =0
D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1934): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1934): fetch service done; releasing wakelock
I/ConfigFetchService( 1934): stopping self
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
W/GAV2    ( 3828): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  966): Killing 3308:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{437f5ab8 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1934): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1934): GC_CONCURRENT freed 1588K, 26% free 18435K/24832K, paused 3ms+2ms, total 32ms
I/Icing   ( 1934): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1934): Loaded CLD2 Version V2.0 - 20141016
I/ActivityManager(  966): Waited long enough for: ServiceRecord{4373fb48 u0 com.lge.slideaside/.MainService}
I/Icing   ( 1934): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
D/libc    (  265): _dns_getaddrinfo: iptype =0
D/libc    (  265): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
D/AndroidRuntime( 3879): 
D/AndroidRuntime( 3879): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3879): CheckJNI is OFF
D/dalvikvm( 3879): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3879): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3879): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3879): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3879): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3879): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3879): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3879): failed to load memtrack module: -2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 3879): Calling main entry com.android.commands.am.Am
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3879
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{437f5ab8 stackId=1, 2 tasks}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (104 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  966): GC_FOR_ALLOC freed 433K, 12% free 27524K/31192K, paused 64ms, total 66ms
I/dalvikvm-heap(  966): Grow heap (frag case) to 29.875MB for 856096-byte allocation
D/dalvikvm(  966): GC_FOR_ALLOC freed 75K, 12% free 28288K/32032K, paused 82ms, total 82ms
I/dalvikvm-heap(  966): Grow heap (frag case) to 30.622MB for 856096-byte allocation
D/AndroidRuntime( 3879): Shutting down VM
D/UsbSettingsControl( 2467): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2467): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 3879): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{437f5ab8 stackId=1, 2 tasks}
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  966): startService SlideAside
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2} (pause complete)
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{437f5ab8 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{436806b8 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  966): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3903 uid=10311 gids={50311, 3003, 3001, 3002}
I/SlideAside( 3432): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/SlideAside( 3432): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3432): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{436806b8 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/HyLog   ( 3903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3903): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 3903): Binding Chromium to the background looper Looper (main, tid 1) {42e1ac68}
I/chromium( 3903): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3903): Initializing chromium process, renderers=0
W/chromium( 3903): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3903): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3903): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3903): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3903): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3903): Remote Branch: 
I/Adreno-EGL( 3903): Local Patches: 
I/Adreno-EGL( 3903): Reconstruct Branch: 
I/dalvikvm( 3903): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3903): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3903): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3903): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3903): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3903): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3903): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3903): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3903): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3903): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3903): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3903): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3903): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3903): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3903): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3903): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3903): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3903): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3903): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3903): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 3903): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3903): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3903): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3903): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 3903): Enabling debug mode 0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/AwContents( 3903): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 3903): Timeline: Activity_idle id: android.os.BinderProxy@42e1c430 time:42186
I/ActivityManager(  966): Displayed com.example.hello/.MainActivity: +483ms
I/chromium( 3903): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3903): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 3903): Set native->JS mode to OnlineEventsBridgeMode
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 3903): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42e204f0
D/dalvikvm( 3903): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42e204f0
D/jxcore_app_log( 3903): JniHelper::setJavaVM(0x41dc9808), pthread_self() = 1627280384
D/JX-Cordova( 3903): jxcore cordova android initializing
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{436806b8 u0 com.example.hello/.MainActivity t3} time:42468
D/ActivityManager(  966): no-history finish of ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{4322db48 ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436806b8 u0 com.example.hello/.MainActivity t3}
D/UsbSettings( 2467): [AUTORUN] onStop()
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 3903): Initializing JXcore engine
W/jxcore-log( 3903): JXcore engine is ready
W/jxcore-log( 3903): Starting JXcore engine
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/jxcore-log( 3903): Platform android
W/jxcore-log( 3903): 
,W/jxcore-log( 3903): Process ARCH arm
W/jxcore-log( 3903): 
,I/jxcore-log( 3903): JXcore Cordova bridge is ready!
I/jxcore-log( 3903): 
,W/jxcore-log( 3903): JXcore engine is started
,I/chromium( 3903): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 3903): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore-log( 3903): >> LGE-LG-D802
E/jxcore-log( 3903): 
,I/jxcore-log( 3903): Total memory 1943035904
I/jxcore-log( 3903): 
I/jxcore-log( 3903): Free memory 459046912
I/jxcore-log( 3903): 
I/jxcore-log( 3903): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3903): 
,I/jxcore-log( 3903): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3903): 
,I/jxcore-log( 3903): userPath [ 'www' ]
I/jxcore-log( 3903): 
I/jxcore-log( 3903): Size 1080 1776
I/jxcore-log( 3903): 
,I/jxcore-log( 3903): Screen Brightness 255
I/jxcore-log( 3903): 
,E/jxcore-log( 3903): Dummy Error Log.
E/jxcore-log( 3903): 
,I/CheckinService( 1934): Done disabling old GoogleServicesFramework version
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1154): GC_CONCURRENT freed 1271K, 6% free 25440K/26888K, paused 1ms+5ms, total 18ms
D/WifiController(  966): battery changed pluggedType: 2
,I/jxcore-log( 3903): getBuffer is called!!!!
I/jxcore-log( 3903): 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3828): Thread[GAThread,5,main]: No campaign data found.
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1550): onDestroy
,I/ActivityManager(  966): Killing 3362:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{437f5ab8 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436806b8 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.548492 Y: -0.367645 Z: 9.760529 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.548492 .y:-0.367645 .z:9.760529
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.552231 Y: -0.362503 Z: 9.750244 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.552231 .y:-0.362503 .z:9.750244
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/BluetoothManagerService(  966): Message: 20
,D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@435eaae8:true
,D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  966): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  966): Message: 2
D/WifiService(  966): New client listening to asynchronous messages
,D/WifiService(  966): setWifiEnabled: false pid=3903, uid=10311
,E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3903): ****TEST TOOK:  5042  ms ****
I/jxcore-log( 3903): 
,I/jxcore-log( 3903): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3903): 
I/WifiService(  966): setWifiEnabled startWifiDelaySendMsg true
,D/AndroidRuntime( 3972): 
D/AndroidRuntime( 3972): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3972): CheckJNI is OFF
,D/dalvikvm( 3972): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3972): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 3972): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3972): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3972): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3972): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,E/memtrack( 3972): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3972): failed to load memtrack module: -2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 3972): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  966): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  966): Killing 3903:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  966): Force removing ActivityRecord{436806b8 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{436806b8 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{436806b8 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  966):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{437f5ab8 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  966): moveHomeStack:
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  966): resumeTopActivityLocked: Resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  966): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/WindowState(  966): WIN DEATH: Window{437a7910 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  966): Client connection lost with reason: 4
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
D/UsbSettings( 2467): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2467): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2467): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2467): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{4361ecd8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
,W/PackageSettings(  966): Skipping PackageSetting{432c1ac8 com.test.thalitest/10304} due to missing metadata
,I/ActivityManager(  966): Force stopping com.example.hello appid=10311 user=0: pkg removed
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  966): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
,E/SlideAside( 3432): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3432): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,D/AppUp4:Utils( 3528): [getPackageName] uri : package:com.example.hello
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
D/AppUp4  ( 3528): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,W/System.err( 2527): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 2527): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
,I/AppUp4  ( 3528):  isExcludedPackage  packagename = com.example.hello
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/System.err( 2527): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2527): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2527): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2527): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2527): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2527): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2527): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2527): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2527): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2527): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2527): 	at dalvik.system.NativeStart.main(Native Method)
D/AppUp4  ( 3528):  isExcludedPackage TRUE : com.example.hello
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm( 2540): GC_EXPLICIT freed 4439K, 27% free 18169K/24832K, paused 2ms+9ms, total 75ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/ActivityManager(  966): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=3999 uid=10090 gids={50090}
D/PhoneApp( 1441): getIsInUseVoLTE : false
D/dalvikvm(  966): GC_EXPLICIT freed 893K, 12% free 29205K/32864K, paused 2ms+8ms, total 112ms
D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/[BNRAppListMgrReceiver]( 3296): android.intent.action.PACKAGE_REMOVED : com.example.hello
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
D/HyLog   ( 3999): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3999): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 3999): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "smsto"
D/administrator(  966): Handling package changes for user 0
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/LockScreenSettings( 3999): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
,D/VoicemailCleanupService( 1811): Cleaning up data for package: com.example.hello
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageChangeReceiver( 3809): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1140): createShortcutInfo...
,D/BackupManagerService(  966): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  966): removePackageParticipantsLocked: uid=10311 #1
D/PackageIntentReceiver( 2467): Not supported Hotkey customization function 
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/InteractionManagerConfigurator(  966): updateIntentFilterConfig
I/InteractionManagerConfigurator(  966): com.example.hello isn't inclued in dragdropPackageList
D/HideNavigationAppsReceiver( 2467): Receive package name : com.example.hello
D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/HideNavigationAppsReceiver( 2467): Delete mPackageMame : com.example.hello
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1140): handleShortcutListChanged...
,I/ActivityManager(  966): Killing 3250:com.google.android.music:main/u0a107 (adj 15): empty #17
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,F/ActivityManager(  966): Service ServiceRecord{438a4f10 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{436a5080 3250:com.google.android.music:main/u0a107} not same as in map: null
,I/IcingCorporaProvider( 2540): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
F/ActivityManager(  966): Service ServiceRecord{43838220 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{436a5080 3250:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
I/ActivityManager(  966): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4020 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4020): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4020): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4020): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 6199K, 12% free 69262K/78608K, paused 38ms, total 39ms
,D/dalvikvm(  269): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
W/ContextImpl( 4020): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 14ms
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 5415K, 9% free 61007K/66656K, paused 17ms, total 18ms
,I/dalvikvm( 3652): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3652): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3652): VFY: replacing opcode 0x6e at 0x0013
I/ActivityManager(  966): Killing 2075:android.process.media/u0a23 (adj 15): empty #17
,D/dalvikvm( 1487): GC_CONCURRENT freed 863K, 10% free 60520K/66656K, paused 6ms+5ms, total 34ms
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
I/IcingCorporaProvider( 2540): UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
,E/NetworkScheduler.SchedulerReceiver( 1550): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1550): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1140): createShortcutInfo...
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/KeyguardModel( 1140): handleShortcutListChanged...
,D/dalvikvm(  966): GC_EXPLICIT freed 600K, 11% free 29317K/32864K, paused 3ms+17ms, total 300ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3,
,D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1934): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1934): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/AccountUtils( 1934): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1934): Module APK com.google.android.play.games already loaded
D/PackageIntentReceiver( 2467): Not supported Hotkey customization function 
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/ActivityManager(  966): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4047 uid=10065 gids={50065, 1028, 4002}
D/AndroidRuntime( 3972): Shutting down VM
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
D/dalvikvm( 3972): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 1ms
,I/LocationSettingsChecker( 1934): Removing dialog suppression flag for package com.example.hello
D/HyLog   ( 4047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4047): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/ActivityManager(  966): Delaying start of: ServiceRecord{437f0ce8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/ConfigService( 1550): onCreate
,D/Documents( 4047): Loading roots for com.android.externalstorage.documents
,I/ConfigFetchService( 1934): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/GOOGLEHELP_CompatibleDatabase( 1934): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1934): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,I/ActivityManager(  966): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4067 uid=10005 gids={50005, 1028, 1015, 1023}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
D/gH_MetricsDatabase( 1934): 0 metrics were deleted when clearing package com.example.hello.
D/GOOGLEHELP_CompatibleDatabase( 1934): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,D/HyLog   ( 4067): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4067): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4067): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
D/GOOGLEHELP_CompatibleDatabase( 1934): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1934): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,W/BaseAppContext( 1934): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1934): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,W/BaseAppContext( 1934): Using Auth Proxy for data requests.
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
D/GOOGLEHELP_CompatibleDatabase( 1934): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1934): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/ActivityManager(  966): Killing 3748:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/WeatherAncestor( 1872): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 9:12:57
,D/ExternalStorage( 4067): After updating volumes, found 1 active roots
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/Documents( 4047): Updating roots due to change at content://com.android.externalstorage.documents/root
,I/ActivityManager(  966): Killing 3781:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/GOOGLEHELP_CompatibleDatabase( 1934): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1934): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1934): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1934): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Icing   ( 1934): doRemovePackageData com.example.hello
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/PeopleContactsSync( 1934): CP2 sync disabled
D/Documents( 4047): Loading roots for com.android.providers.downloads.documents
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,D/UpdateThreadPoolManager( 1872): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1872): 2 : quick cover state : opened : 0
D/WeatherService( 1872): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1872): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1872): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1872): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherAncestor( 1872): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 9:12:57
D/WeatherService( 1872): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1872): 2 : quick cover state : opened : 0
D/Weather.Utils( 1872): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1872): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1872): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1872): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1872): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/ActivityManager(  966): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4081 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1} time:49450
D/UpdateThreadPoolManager( 1872): 2 : This is isUpdating : false
D/WeatherService( 1872): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1872): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1872): 2 : Map key string is -2
D/lim     ( 1872): 2 : time = 09:12
I/WeatherReflect( 1872): Model Name : LG-D802
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/WeatherTheme( 1872): 2 : exactly same view!
,D/WeatherTheme( 1872): 2 : widgetId = 1 : widgetSize = 1 : Do not refresh any widget.
I/ActivityManager(  966): Killing 1858:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,D/WeatherQuickCover( 1872): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1872): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1872): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1872): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/HyLog   ( 4081): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4081): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4081): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{431d0dd8 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{436236f8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Delaying start of: ServiceRecord{437b8a68 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@42e17fc0 time:49521
,D/Documents( 4047): Loading roots for com.android.providers.media.documents
,D/Documents( 4047): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 4047): Update found 7 roots in 240ms
,D/Documents( 4047): Loading roots for com.android.externalstorage.documents
,D/Documents( 4047): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4047): Used cached roots for com.android.providers.media.documents
D/Documents( 4047): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4047): Update found 7 roots in 7ms
,W/DriveInitializer( 1934): Awaiting to be initialized
,W/DriveInitializer( 1934): Background init thread started
,E/SQLiteLog( 1934): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/DriveInitializer( 1934): Background init thread ended
W/dalvikvm( 1934): threadid=28: thread exiting with uncaught exception (group=0x41ddae48)
E/SQLiteLog( 1934): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1934): disk I/O error (code 3850)
E/DriveAsyncService( 1934): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/DriveAsyncService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1934): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1934): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1934): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1934): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1934): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 1934): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1934): Process: com.google.android.gms, PID: 1934
E/AndroidRuntime( 1934): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/AndroidRuntime( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1934): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/AndroidRuntime( 1934): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/AndroidRuntime( 1934): 	at com.google.android.gms.drive.database.f.e(SourceFile:804)
E/AndroidRuntime( 1934): 	at com.google.android.gms.drive.events.ao.a(SourceFile:135)
E/AndroidRuntime( 1934): 	at com.google.android.gms.drive.r.run(SourceFile:72)
,E/DropBoxManagerService(  966): Can't write: system_app_crash
E/DropBoxManagerService(  966): java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  966): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  966): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  966): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  966): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  966): 	... 5 more
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
,E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
,E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
,E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
,E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
,E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
,E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
,E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
,E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  268): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  268): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  268): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  268): MdpData failed to play
E/qdoverlay(  268): == Dump MdpData start ==
E/qdoverlay(  268): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  268): mOvData msmfb_overlay_data id=8
E/qdoverlay(  268): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
E/qdoverlay(  268): == Dump MdpData end ==
E/qdhwcomposer(  268): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  268): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  268): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  268): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  268): hwc_set_primary: display commit fail for 0 dpy!

```
