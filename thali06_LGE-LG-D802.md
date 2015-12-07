#### Test 50242285e707819_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 3894): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
--------- beginning of /dev/log/system
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EulaProviderUpdateObserver( 2931): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 2931): uri : package:com.example.hello
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  960): Delaying start of: ServiceRecord{432279f0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ConfigFetchService( 1939): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1939): launchTask
W/dalvikvm( 1939): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1939): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WlbpCximdkN0ZiolhpAA5F9NalmSWRM_DZR2upo1tV96y_Gm-nsh3YSwE0F9g-DsMB65hFwBQGt1h2I8BPIG0fhZfThaAjkR3c3XAAziUstCADB6pvuKxG69atSgib7j0eYQK2Ug4sl5H0vTzZEBBEEAbD8ifOlz_B38iK_uAb_2uQrKswlkTTaWO7zVm9qLcCH3bw
I/GoogleURLConnFactory( 1939): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1939): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1939): Failed to find package metadata for com.example.hello
D/Vision  ( 1939): No vision deps
I/PeopleContactsSync( 1939): CP2 sync disabled
I/dalvikvm( 1939): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1939): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1939): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
E/DataScheduler( 1939): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =0
D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1939): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1939): fetch service done; releasing wakelock
I/ConfigFetchService( 1939): stopping self
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/GAV2    ( 3894): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  960): Killing 3427:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43233070 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2}
I/ActivityManager(  960): Killing 3476:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43233070 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2}
I/Icing   ( 1939): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1939): GC_CONCURRENT freed 1559K, 26% free 18452K/24832K, paused 3ms+4ms, total 33ms
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/Icing   ( 1939): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1939): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/ThermalEngine(  291): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
D/AndroidRuntime( 3964): 
D/AndroidRuntime( 3964): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3964): CheckJNI is OFF
D/dalvikvm( 3964): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3964): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3964): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3964): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3964): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3964): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3964): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3964): failed to load memtrack module: -2
D/AndroidRuntime( 3964): Calling main entry com.android.commands.am.Am
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3964
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43233070 stackId=1, 2 tasks}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (105 us)
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  960): GC_FOR_ALLOC freed 583K, 12% free 27393K/31008K, paused 65ms, total 65ms
I/dalvikvm-heap(  960): Grow heap (frag case) to 29.747MB for 856096-byte allocation
D/dalvikvm(  960): GC_FOR_ALLOC freed 55K, 12% free 28175K/31848K, paused 64ms, total 64ms
I/dalvikvm-heap(  960): Grow heap (frag case) to 30.510MB for 856096-byte allocation
D/UsbSettingsControl( 2559): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2559): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 3964): Shutting down VM
D/dalvikvm( 3964): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
D/ActivityManager(  960): resumeTopActivityLocked: Pausing null
V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  960): setFocusedStack: mFocusedStack=ActivityStack{43233070 stackId=1, 2 tasks}
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  960): startService SlideAside
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43233070 stackId=1, 2 tasks}
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  960): resumeTopActivityLocked: Restarting ActivityRecord{42beb800 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  960): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3975 uid=10311 gids={50311, 3003, 3001, 3002}
I/SlideAside( 3532): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{42beb800 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/SlideAside( 3532): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3532): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
D/HyLog   ( 3975): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3975): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3975): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 3975): Binding Chromium to the background looper Looper (main, tid 1) {427f5c18}
I/chromium( 3975): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3975): Initializing chromium process, renderers=0
W/chromium( 3975): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3975): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3975): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3975): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3975): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3975): Remote Branch: 
I/Adreno-EGL( 3975): Local Patches: 
I/Adreno-EGL( 3975): Reconstruct Branch: 
I/dalvikvm( 3975): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3975): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3975): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3975): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3975): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3975): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3975): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3975): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3975): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3975): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3975): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3975): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3975): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3975): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3975): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3975): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3975): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3975): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3975): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3975): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 3975): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3975): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3975): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3975): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/ActivityManager(  960): Waited long enough for: ServiceRecord{4310fd00 u0 com.lge.slideaside/.MainService}
D/OpenGLRenderer( 3975): Enabling debug mode 0
W/AwContents( 3975): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  960): Displayed com.example.hello/.MainActivity: +528ms
I/InputMethodManagerService(  960): IME STATUS OFF
W/AwContents( 3975): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 3975): Timeline: Activity_idle id: android.os.BinderProxy@427f72f0 time:42023
I/chromium( 3975): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3975): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 3975): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 3975): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x427fb4a0
D/dalvikvm( 3975): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x427fb4a0
D/jxcore_app_log( 3975): JniHelper::setJavaVM(0x416b9838), pthread_self() = 1625974384
D/JX-Cordova( 3975): jxcore cordova android initializing
I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{42beb800 u0 com.example.hello/.MainActivity t3} time:42251
D/UsbSettings( 2559): [AUTORUN] onStop()
D/ActivityManager(  960): no-history finish of ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  960): Finishing activity token=Token{432d04c0 ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42beb800 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/jxcore-log( 3975): Initializing JXcore engine
W/jxcore-log( 3975): JXcore engine is ready
W/jxcore-log( 3975): Starting JXcore engine
,W/jxcore-log( 3975): Platform android
W/jxcore-log( 3975): 
,W/jxcore-log( 3975): Process ARCH arm
W/jxcore-log( 3975): 
,I/jxcore-log( 3975): JXcore Cordova bridge is ready!
I/jxcore-log( 3975): 
,W/jxcore-log( 3975): JXcore engine is started
,I/chromium( 3975): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/chromium( 3975): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore-log( 3975): >> LGE-LG-D802
E/jxcore-log( 3975): 
I/jxcore-log( 3975): Total memory 1943035904
I/jxcore-log( 3975): 
I/jxcore-log( 3975): Free memory 463101952
I/jxcore-log( 3975): 
I/jxcore-log( 3975): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3975): 
I/jxcore-log( 3975): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3975): 
I/jxcore-log( 3975): userPath [ 'www' ]
I/jxcore-log( 3975): 
I/jxcore-log( 3975): Size 1080 1776
I/jxcore-log( 3975): 
I/jxcore-log( 3975): Screen Brightness 255
I/jxcore-log( 3975): 
E/jxcore-log( 3975): Dummy Error Log.
E/jxcore-log( 3975): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 3975): getBuffer is called!!!!
I/jxcore-log( 3975): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1939): Done disabling old GoogleServicesFramework version
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3894): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1532): onDestroy
,I/ActivityManager(  960): Killing 3377:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  960): Service ServiceRecord{43298400 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{431dda20 3377:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  960): Service ServiceRecord{43260eb0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{431dda20 3377:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43233070 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42beb800 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1153): GC_CONCURRENT freed 1260K, 6% free 25438K/26876K, paused 28ms+3ms, total 72ms
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.454697 Y: -0.397263 Z: 9.783661 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454697 .y:-0.397263 .z:9.783661
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.456680 Y: -0.387589 Z: 9.782806 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456680 .y:-0.387589 .z:9.782806
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/BluetoothManagerService(  960): Message: 20
,D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@430342f8:true
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  960): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  960): Message: 2
D/WifiService(  960): New client listening to asynchronous messages
,D/WifiService(  960): setWifiEnabled: false pid=3975, uid=10311
,E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3975): ****TEST TOOK:  5055  ms ****
I/jxcore-log( 3975): 
,I/jxcore-log( 3975): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3975): 
I/WifiService(  960): setWifiEnabled startWifiDelaySendMsg true
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
,D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/WifiController(  960): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 4036): 
D/AndroidRuntime( 4036): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4036): CheckJNI is OFF
,D/dalvikvm( 4036): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4036): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4036): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4036): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4036): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4036): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/memtrack( 4036): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4036): failed to load memtrack module: -2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 4036): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  960): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  960): Killing 3975:com.example.hello/u0a311 (adj 0): stop com.example.hello
W/ActivityManager(  960): Force removing ActivityRecord{42beb800 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{42beb800 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{42beb800 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  960):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43233070 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  960): moveHomeStack:
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
,I/WindowState(  960): WIN DEATH: Window{430450c8 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  960): Client connection lost with reason: 4
,W/PackageSettings(  960): Skipping PackageSetting{42c67a08 com.test.thalitest/10304} due to missing metadata
,V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  960): resumeTopActivityLocked: Resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/UsbSettings( 2559): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/ActivityManager(  960): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1485): [Launcher.java:4947:onStart()]onStart
,D/dalvikvm( 2626): GC_EXPLICIT freed 3958K, 27% free 18159K/24832K, paused 10ms+4ms, total 50ms
,V/UsbSettings( 2559): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,V/UsbSettings( 2559): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,D/KeyguardModel( 1139): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/SlideAside( 3532): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3532): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
V/UsbSettings( 2559): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
,I/[LGHome]EVENT( 1485): [Launcher.java:717:onResume()]onResume
,I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/GeofencerStateMachine( 1420): Ignoring removeGeofence because network location is disabled.
D/AppUp4:Utils( 3674): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3674): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 3674):  isExcludedPackage  packagename = com.example.hello
D/AppUp4  ( 3674):  isExcludedPackage TRUE : com.example.hello
,W/System.err( 2614): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1445): getIsInUseVoLTE : false
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
W/System.err( 2614): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2614): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2614): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
,W/System.err( 2614): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2614): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2614): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2614): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
,W/System.err( 2614): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2614): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2614): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2614): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2614): 	at dalvik.system.NativeStart.main(Native Method)
,D/[BNRAppListMgrReceiver]( 3415): android.intent.action.PACKAGE_REMOVED : com.example.hello
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
,I/[LGHome]LGActivityUtil( 1485): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  960): GC_EXPLICIT freed 983K, 12% free 29066K/32688K, paused 3ms+7ms, total 123ms
,D/dalvikvm(  960): WAIT_FOR_CONCURRENT_GC blocked 79ms
,I/[LGHome]EVENT( 1485): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{4301ebb0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
,D/administrator(  960): Handling package changes for user 0
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
,I/PackageChangeReceiver( 3873): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 1814): Cleaning up data for package: com.example.hello
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1485): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
,D/PackageIntentReceiver( 2559): Not supported Hotkey customization function 
,W/Binder  ( 1307): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1307): java.lang.NullPointerException
W/Binder  ( 1307): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1307): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1307): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1307): 	at dalvik.system.NativeStart.run(Native Method)
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/InputMethodManagerService(  960): IME STATUS OFF
W/InputMethodManagerService(  960): Got RemoteException sending setActive(false) notification to pid 3975 uid 10311
,D/HideNavigationAppsReceiver( 2559): Receive package name : com.example.hello
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
,D/HideNavigationAppsReceiver( 2559): Delete mPackageMame : com.example.hello
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/IcingCorporaProvider( 2626): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/BackupManagerService(  960): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  960): removePackageParticipantsLocked: uid=10311 #1
I/InteractionManagerConfigurator(  960): updateIntentFilterConfig
I/InteractionManagerConfigurator(  960): com.example.hello isn't inclued in dragdropPackageList
,I/ActivityManager(  960): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4087 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1139): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1139): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+1ms, total 19ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
D/HyLog   ( 4087): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4087): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4087): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,D/dalvikvm(  960): GC_EXPLICIT freed 559K, 11% free 29133K/32688K, paused 4ms+12ms, total 181ms
,I/ActivityManager(  960): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4100 uid=10090 gids={50090}
I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/HyLog   ( 4100): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4100): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4100): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1485): GC_CONCURRENT freed 4782K, 8% free 60767K/65732K, paused 1ms+3ms, total 21ms
,D/dalvikvm( 1485): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
D/dalvikvm( 1139): GC_FOR_ALLOC freed 6561K, 13% free 69043K/78592K, paused 45ms, total 45ms
,I/LockScreenSettings( 4100): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,D/KeyguardModel( 1139): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1139): createShortcutInfo...
D/KeyguardModel( 1139): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1139): createShortcutInfo...
D/KeyguardModel( 1139): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1139): createShortcutInfo...
D/KeyguardModel( 1139): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1139): createShortcutInfo...
D/KeyguardModel( 1139): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1139): createShortcutInfo...
,D/KeyguardModel( 1139): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1139): createShortcutInfo...
,I/IcingCorporaProvider( 2626): UpdateCorporaTask done [took 137 ms] updated apps [took 137 ms] 
D/KeyguardModel( 1139): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1139): createShortcutInfo...
D/KeyguardModel( 1139): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1139): createShortcutInfo...
,D/KeyguardModel( 1139): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1139): createShortcutInfo...
,D/KeyguardModel( 1139): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1139): createShortcutInfo...
,I/dalvikvm( 3752): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3752): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3752): VFY: replacing opcode 0x6e at 0x0013
I/ActivityManager(  960): Killing 3270:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
,E/NetworkScheduler.SchedulerReceiver( 1532): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1532): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
,D/AndroidRuntime( 4036): Shutting down VM
,D/dalvikvm( 4036): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 1ms+0ms, total 2ms
,D/KeyguardModel( 1139): handleShortcutListChanged...
,D/KeyguardModel( 1139): handleShortcutListChanged...
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge( 1485): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/ActivityManager(  960): Killing 3309:android.process.media/u0a23 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,D/AccountUtils( 1939): Clearing selected account for com.example.hello
,D/PackageIntentReceiver( 2559): Not supported Hotkey customization function 
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
,D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  960): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4126 uid=10065 gids={50065, 1028, 4002}
I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/LocationSettingsChecker( 1939): Removing dialog suppression flag for package com.example.hello
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
D/HyLog   ( 4126): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4126): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4126): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): Delaying start of: ServiceRecord{432323e8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,D/GOOGLEHELP_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1939): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,D/Documents( 4126): Loading roots for com.android.externalstorage.documents
D/GOOGLEHELP_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/GOOGLEHELP_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/ActivityManager(  960): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4144 uid=10005 gids={50005, 1028, 1015, 1023}
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/ConfigFetchService( 1939): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigService( 1532): onCreate
,I/ActivityManager(  960): Killing 3847:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/WeatherAncestor( 1882): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:36:21
I/ActivityManager(  960): Killing 3831:com.google.android.partnersetup/u0a9 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 4144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4144): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
I/Icing   ( 1939): doRemovePackageData com.example.hello
I/PeopleContactsSync( 1939): CP2 sync disabled
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,D/ExternalStorage( 4144): After updating volumes, found 1 active roots
,D/Documents( 4126): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 4126): Loading roots for com.android.providers.downloads.documents
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,D/UpdateThreadPoolManager( 1882): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1882): 2 : quick cover state : opened : 0
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/WeatherService( 1882): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1882): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1882): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1882): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1882): 2 : TimeTick Receiver Register
,I/ActivityManager(  960): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4159 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WeatherAncestor( 1882): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:36:21
D/WeatherService( 1882): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1882): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1882): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1882): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1882): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1882): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1882): 2 : requestRefreshAppWidget, isUpdateStart : false
D/HyLog   ( 4159): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4159): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4159): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/UpdateThreadPoolManager( 1882): 2 : This is isUpdating : false
D/WeatherService( 1882): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1882): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1882): 2 : Map key string is -2
D/lim     ( 1882): 2 : time = 15:36
I/WeatherReflect( 1882): Model Name : LG-D802
D/WeatherTheme( 1882): 2 : Different view - status_min_formatted : 35 != 36
,D/WeatherTheme( 1882): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1882): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1882): 2 : Fixed theme : optimus
,I/ActivityManager(  960): Killing 3201:com.android.mms/u0a35 (adj 15): empty #17
,D/WeatherTheme( 1882): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,I/LocationManagerService(  960): remove 42b06670
D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
D/WeatherQuickCover( 1882): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1882): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1882): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1882): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/CountryDetector(  960): No listener is left
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b651d8 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): Delaying start of: ServiceRecord{430b14e8 u0 com.android.providers.downloads/.DownloadService}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,D/dalvikvm( 1485): GC_FOR_ALLOC freed 5102K, 9% free 62061K/67996K, paused 18ms, total 19ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1457): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1457): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1457): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1457): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{42cf5cb8 u0 com.lge.launcher2/.Launcher t1} time:49217
,D/Documents( 4126): Loading roots for com.android.providers.media.documents
,D/Documents( 4126): Loading roots for com.google.android.apps.docs.storage
,I/ActivityManager( 1485): Timeline: Activity_idle id: android.os.BinderProxy@427f2038 time:49265
,D/Documents( 4126): Update found 7 roots in 247ms
,D/Documents( 4126): Loading roots for com.android.externalstorage.documents
,D/Documents( 4126): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4126): Used cached roots for com.android.providers.media.documents
D/Documents( 4126): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4126): Update found 7 roots in 8ms
,D/dalvikvm( 1532): GC_EXPLICIT freed 595K, 29% free 17821K/24832K, paused 2ms+2ms, total 25ms
,W/DriveInitializer( 1939): Awaiting to be initialized
,W/DriveInitializer( 1939): Background init thread started
,E/SQLiteLog( 1939): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock112] disk I/O error
E/DocListDatabase( 1939): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1939): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1939): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1939): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/DocListDatabase( 1939): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/DocListDatabase( 1939): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1939): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/DocListDatabase( 1939): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1939): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1939): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,W/DriveInitializer( 1939): Background init thread ended
W/dalvikvm( 1939): threadid=24: thread exiting with uncaught exception (group=0x417b4e48)
,E/SQLiteLog( 1939): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 1939): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1939): Process: com.google.android.gms, PID: 1939
E/AndroidRuntime( 1939): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/AndroidRuntime( 1939): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1939): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 1939): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,E/DriveAsyncService( 1939): disk I/O error (code 3850)
E/DriveAsyncService( 1939): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1939): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1939): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/DriveAsyncService( 1939): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1939): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1939): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1939): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1939): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1939): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1939): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1939): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1939): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1939): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1939): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1939): 	at java.lang.Thread.run(Thread.java:841)
E/DropBoxManagerService(  960): Can't write: system_app_crash
E/DropBoxManagerService(  960): java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  960): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  960): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  960): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  960): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  960): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  960): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  960): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  960): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  960): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  960): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  960): 	... 5 more
,E/qdhwcomposer(  274): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  274): hwc_sync: acq_fen_fd_cnt=3 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  274): MdpData failed to play
E/qdoverlay(  274): == Dump MdpData start ==
E/qdoverlay(  274): == Dump OvFD fd=67 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  274): mOvData msmfb_overlay_data id=64
E/qdoverlay(  274): data msmfb_data offset=0 memid=73 id=0 flags=0x0 priv=0
E/qdoverlay(  274): == Dump MdpData end ==
E/qdhwcomposer(  274): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  274): hwc_set_primary: MDPComp draw failed
E/qdoverlay(  274): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  274): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  274): hwc_set_primary: display commit fail for 0 dpy!
,I/[LGHome]EVENT( 1485): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
E/qdhwcomposer(  274): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  274): hwc_sync: acq_fen_fd_cnt=3 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  274): MdpData failed to play
E/qdoverlay(  274): == Dump MdpData start ==
E/qdoverlay(  274): == Dump OvFD fd=67 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  274): mOvData msmfb_overlay_data id=64
E/qdoverlay(  274): data msmfb_data offset=0 memid=73 id=0 flags=0x0 priv=0
E/qdoverlay(  274): == Dump MdpData end ==
E/qdhwcomposer(  274): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  274): hwc_set_primary: MDPComp draw failed
E/qdoverlay(  274): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  274): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  274): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  274): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  274): hwc_sync: acq_fen_fd_cnt=3 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  274): MdpData failed to play
E/qdoverlay(  274): == Dump MdpData start ==
E/qdoverlay(  274): == Dump OvFD fd=67 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  274): mOvData msmfb_overlay_data id=64
E/qdoverlay(  274): data msmfb_data offset=0 memid=73 id=0 flags=0x0 priv=0
E/qdoverlay(  274): == Dump MdpData end ==
E/qdhwcomposer(  274): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  274): hwc_set_primary: MDPComp draw failed
E/qdoverlay(  274): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  274): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  274): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4159): DownloadService onCreate
,E/qdoverlay(  274): Cant open device /dev/graphics/fb0 err=1
E/qdoverlay(  274): Ctrl failed to init fbnum=0
E/qdoverlay(  274): Ctrl failed to init dpy=0
E/qdoverlay(  274): GenericPipe failed to init ctrl
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  274): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  274): == Bad OVInfo is:  mdp_overlay z=1 fg=0 alpha=77 mask=-1 flags=0x60000 id=8
E/qdoverlay(  274): src msmfb_img w=1152 h=384 format=13 MDP_RGBA_8888
E/qdoverlay(  274): src_rect mdp_rect x=0 y=0 w=960 h=377
E/qdoverlay(  274): dst_rect mdp_rect x=92 y=750 w=896 h=351
E/qdoverlay(  274): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  274): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888
E/qdoverlay(  274): src_rect mdp_rect x=0 y=0 w=1080 h=144
E/qdoverlay(  274): dst_rect mdp_rect x=0 y=1776 w=1080 h=144
E/qdoverlay(  274): Ctrl commit failed set overlay
E/qdhwcomposer(  274): configureNonSplit: commit failed for low res panel
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  274): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  274): == Bad OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  274): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  274): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  274): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  274): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  274): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888
E/qdoverlay(  274): src_rect mdp_rect x=0 y=0 w=1080 h=144
E/qdoverlay(  274): dst_rect mdp_rect x=0 y=1776 w=1080 h=144
E/qdoverlay(  274): Ctrl commit failed set overlay
E/qdhwcomposer(  274): configure: configMdp failed for dpy 0
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  274): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  274): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  274): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  274): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  274): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  274): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  274): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888
E/qdoverlay(  274): src_rect mdp_rect x=0 y=0 w=1080 h=144
E/qdoverlay(  274): dst_rect mdp_rect x=0 y=1776 w=1080 h=144
E/qdoverlay(  274): Ctrl commit failed set overlay
E/qdhwcomposer(  274): configure: configMdp failed for dpy 0
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  274): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  274): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  274): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  274): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  274): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  274): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  274): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888
E/qdoverlay(  274): src_rect mdp_rect x=0 y=0 w=1080 h=144
E/qdoverlay(  274): dst_rect mdp_rect x=0 y=1776 w=1080 h=144
E/qdoverlay(  274): Ctrl commit failed set overlay
E/qdhwcomposer(  274): configure: configMdp failed for dpy 0
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  274): MdpCtrl close error in unset
E/qdoverlay(  274): GenericPipe failed to close ctrl
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  274): MdpCtrl close error in unset
E,/qdoverlay(  274): GenericPipe failed to close ctrl
E/qdoverlay(  274): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  274): MdpCtrl close error in unset

```
