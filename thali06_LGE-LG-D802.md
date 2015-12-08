#### Test 50650278352fc1f_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
E/DataScheduler( 1877): isDataSchedulerEnabled():false
D/libc    (  269): _dns_getaddrinfo: iptype =0
D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1877): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/BaseAppContext( 1877): Using Auth Proxy for data requests.
I/ConfigFetchService( 1877): fetch service done; releasing wakelock
I/ConfigFetchService( 1877): stopping self
W/BaseAppContext( 1877): Using Auth Proxy for data requests.
W/BaseAppContext( 1877): Using Auth Proxy for data requests.
,D/dalvikvm( 1877): GC_CONCURRENT freed 1727K, 26% free 18426K/24832K, paused 1ms+4ms, total 27ms
W/GAV2    ( 4083): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  963): Killing 3422:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43226440 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1877): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1877): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4125): 
D/AndroidRuntime( 4125): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4125): CheckJNI is OFF
D/dalvikvm( 4125): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4125): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4125): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4125): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4125): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4125): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4125): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4125): failed to load memtrack module: -2
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1877): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4125): Calling main entry com.android.commands.am.Am
D/Icing   ( 1877): Loaded CLD2 Version V2.0 - 20141016
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4125
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43226440 stackId=1, 2 tasks}
D/PermissionCache(  272): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (112 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  963): startService SlideAside
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{43226440 stackId=1, 2 tasks}
D/UsbSettingsControl( 2560): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2560): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/AndroidRuntime( 4125): Shutting down VM
D/dalvikvm( 4125): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3548): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43226440 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  963): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4143 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3548): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/HyLog   ( 4143): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4143): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4143): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/SlideAside( 3548): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Icing   ( 1877): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4143): Binding Chromium to the background looper Looper (main, tid 1) {4282fcd8}
I/chromium( 4143): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4143): Initializing chromium process, renderers=0
W/chromium( 4143): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4143): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4143): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4143): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4143): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4143): Remote Branch: 
I/Adreno-EGL( 4143): Local Patches: 
I/Adreno-EGL( 4143): Reconstruct Branch: 
I/dalvikvm( 4143): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4143): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4143): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4143): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4143): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4143): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4143): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4143): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4143): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4143): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4143): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4143): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4143): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4143): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4143): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4143): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4143): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4143): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4143): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4143): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4143): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4143): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4143): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4143): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4143): Enabling debug mode 0
,W/AwContents( 4143): nativeOnDraw failed; clearing to background color.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/InputMethodManagerService(  963): IME STATUS OFF
,W/AwContents( 4143): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  963): Displayed com.test.thalitest/.MainActivity: +477ms
,I/ActivityManager( 4143): Timeline: Activity_idle id: android.os.BinderProxy@428313b8 time:109973
,D/JsMessageQueue( 4143): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4143): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428358d8
,D/dalvikvm( 4143): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428358d8
D/jxcore_app_log( 4143): JniHelper::setJavaVM(0x416fa838), pthread_self() = 1631935080
,D/JX-Cordova( 4143): jxcore cordova android initializing
I/dalvikvm( 4143): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4143): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4143): VFY: replacing opcode 0x6e at 0x0045
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3} time:110253
,D/UsbSettings( 2560): [AUTORUN] onStop()
D/ActivityManager(  963): no-history finish of ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{43278308 ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4143): GC_CONCURRENT freed 2777K, 12% free 21876K/24832K, paused 1ms+2ms, total 43ms
,D/dalvikvm( 4143): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4143): GC_FOR_ALLOC freed 227K, 12% free 21863K/24832K, paused 22ms, total 23ms
,D/dalvikvm( 4143): GC_FOR_ALLOC freed 192K, 12% free 21888K/24832K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4143): Grow heap (frag case) to 23.686MB for 143930-byte allocation
,D/dalvikvm( 4143): GC_FOR_ALLOC freed 255K, 13% free 21935K/24976K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4143): Grow heap (frag case) to 23.800MB for 215890-byte allocation
,D/dalvikvm( 4143): GC_FOR_ALLOC freed 367K, 13% free 22008K/25188K, paused 21ms, total 22ms
,I/dalvikvm-heap( 4143): Grow heap (frag case) to 23.975MB for 323830-byte allocation
,D/dalvikvm( 4143): GC_FOR_ALLOC freed 565K, 14% free 22129K/25508K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4143): Grow heap (frag case) to 24.248MB for 485740-byte allocation
,D/dalvikvm( 4143): GC_FOR_ALLOC freed 862K, 15% free 22305K/25984K, paused 22ms, total 23ms
I/dalvikvm-heap( 4143): Grow heap (frag case) to 24.650MB for 728606-byte allocation
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/dalvikvm( 4143): GC_FOR_ALLOC freed 1280K, 16% free 22561K/26696K, paused 25ms, total 26ms
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4143): GC_CONCURRENT freed 1677K, 15% free 22932K/26696K, paused 1ms+2ms, total 28ms
D/dalvikvm( 4143): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 4143): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 4143): GC_FOR_ALLOC freed 364K, 15% free 22887K/26696K, paused 22ms, total 22ms
I/dalvikvm-heap( 4143): Grow heap (frag case) to 26.087MB for 1639352-byte allocation
D/dalvikvm( 4143): GC_CONCURRENT freed 1709K, 17% free 23509K/28300K, paused 2ms+2ms, total 42ms
D/dalvikvm( 4143): GC_FOR_ALLOC freed 1334K, 17% free 23533K/28300K, paused 25ms, total 25ms
I/dalvikvm-heap( 4143): Grow heap (frag case) to 27.500MB for 2459024-byte allocation
D/dalvikvm( 4143): GC_CONCURRENT freed 1905K, 22% free 24216K/30704K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 4143): GC_CONCURRENT freed 2340K, 21% free 24461K/30704K, paused 2ms+4ms, total 37ms
,D/dalvikvm( 4143): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4143): GC_FOR_ALLOC freed 630K, 22% free 24229K/30704K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4143): Grow heap (frag case) to 29.352MB for 3688532-byte allocation
,D/dalvikvm( 4143): GC_CONCURRENT freed 2798K, 26% free 25421K/34308K, paused 1ms+3ms, total 44ms
,D/dalvikvm( 4143): GC_FOR_ALLOC freed 483K, 26% free 25437K/34308K, paused 23ms, total 23ms
,W/jxcore-log( 4143): Initializing JXcore engine
,W/jxcore-log( 4143): JXcore engine is ready
,D/dalvikvm( 4143): GC_CONCURRENT freed 348K, 19% free 28063K/34308K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 4143): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/jxcore-log( 4143): Starting JXcore engine
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/jxcore-log( 4143): Platform android
W/jxcore-log( 4143): 
,W/jxcore-log( 4143): Process ARCH arm
W/jxcore-log( 4143): 
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.448334 Y: -0.389160 Z: 9.788437 
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.440567 Y: -0.385834 Z: 9.759567 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.448334 .y:-0.389160 .z:9.788437
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
I/jxcore-log( 4143): JXcore Cordova bridge is ready!
I/jxcore-log( 4143): 
W/jxcore-log( 4143): JXcore engine is started
I/chromium( 4143): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.452286 Y: -0.377075 Z: 9.763229 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452286 .y:-0.377075 .z:9.763229
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
I/chromium( 4143): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4143): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
E/jxcore  ( 4143): Error!: missing ) after argument list
E/jxcore  ( 4143): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
V/ActivityManager(  963): Finishing activity token=Token{4368eeb8 ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
I/chromium( 4143): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3 f}
D/dalvikvm(  963): GC_FOR_ALLOC freed 23169K, 50% free 28804K/56644K, paused 110ms, total 110ms
W/PluginManager( 4143): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 118ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43226440 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  963): moveHomeStack:
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bc5dd0 stackId=0, 1 tasks}
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bc5dd0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1449): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1816): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:29:10
D/UpdateThreadPoolManager( 1816): 2 : This is isUpdating : false
I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/WeatherQuickCover( 1816): 2 : quick cover state : opened : 0
D/WeatherService( 1816): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1816): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1816): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1816): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1816): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1816): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:29:10
D/WeatherService( 1816): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1816): 2 : quick cover state : opened : 0
D/Weather.Utils( 1816): 2 : Utils getTopActivity com.lge.launcher2 / true
I/InputMethodManagerService(  963): IME STATUS OFF
W/IInputConnectionWrapper( 4143): showStatusIcon on inactive InputConnection
D/WeatherService( 1816): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1816): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1816): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1816): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1816): 2 : This is isUpdating : false
D/WeatherService( 1816): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1816): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1816): 2 : Map key string is -2
D/lim     ( 1816): 2 : time = 16:29
I/WeatherReflect( 1816): Model Name : LG-D802
D/WeatherTheme( 1816): 2 : Different view - status_min_formatted : 27 != 29
D/WeatherTheme( 1816): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1816): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1816): 2 : Fixed theme : optimus
D/WeatherTheme( 1816): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1816): 2 : quick cover state : opened : 0
D/Weather.Utils( 1816): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1816): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1816): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
D/dalvikvm( 1139): GC_FOR_ALLOC freed 6407K, 12% free 69057K/78424K, paused 26ms, total 28ms
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/dalvikvm( 1488): GC_CONCURRENT freed 5308K, 9% free 61080K/66572K, paused 2ms+2ms, total 22ms
D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 10ms
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@42833708 time:113298
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2560): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2560): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2560): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2560): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43221508 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bc5dd0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3 f}
,I/ActivityManager(  963): Killing 3365:com.google.android.music:main/u0a107 (adj 15): empty #17
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1} time:113386
V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4143): call to OpenGL ES API with no current context (logged once per thread)
,I/dalvikvm(  963): Jit: resizing JitTable from 8192 to 16384
,F/ActivityManager(  963): Service ServiceRecord{432dbcb8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4327c490 3365:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  963): Service ServiceRecord{4324d748 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4327c490 3365:com.google.android.music:main/u0a107} not same as in map: null
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bc5dd0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43c76770 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bc5dd0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4083): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1525): onDestroy
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1488): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  288): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3720): [342] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3720): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.454727 Y: -0.397461 Z: 9.797623 
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.454727 Y: -0.386368 Z: 9.764328 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.454727 .y:-0.397461 .z:9.797623
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.449493 Y: -0.385742 Z: 9.751999 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449493 .y:-0.385742 .z:9.751999
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/PowerManagerService(  963): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  963): [updateScreenState] screen on = false
,D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  963): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, enabled=1
,I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 7952 usec
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  963): hal_acquire_resources
,I/qcom_sensors_hal(  963): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  963): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  963): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  963): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  963): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  963): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  963): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  963): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.446518 Y: -0.394775 Z: 9.790161 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446518 .y:-0.394775 .z:9.790161
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.461288 Y: -0.391205 Z: 9.788818 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461288 .y:-0.391205 .z:9.788818
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Sensors (  328): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  963): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  963): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  963): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  963): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  963): proximitySensorChanged  positive = true
I/KnockOnPowerController(  963): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.448761 Y: -0.381088 Z: 9.776276 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448761 .y:-0.381088 .z:9.776276
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.432449 Y: -0.389786 Z: 9.772690 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.432449 .y:-0.389786 .z:9.772690
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.445190 Y: -0.377960 Z: 9.780502 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445190 .y:-0.377960 .z:9.780502
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.433029 Y: -0.380615 Z: 9.775177 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.433029 .y:-0.380615 .z:9.775177
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  963): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4318c080)
,D/KeyguardViewMediator( 1139): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1139): notifyScreenOnLocked
,D/KeyguardViewMediator( 1139): handleNotifyScreenOn
D/KeyguardViewManager( 1139): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  963): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
I/WindowManager(  963): No lock screen! windowToken=null
,D/SurfaceFlinger(  272): Screen released, type=0 flinger=0xb7a06450
,D/qdhwcomposer(  272): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.445419 Y: -0.362503 Z: 9.776306 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445419 .y:-0.362503 .z:9.776306
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,E/SlideAside( 3548): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  963): handleScreenStateChanged: true
,D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: InitialState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131127
D/WifiStateMachine(  963): processMsg: InitialState
,D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: InitialState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): setSuspendOptimizations: 4 false
D/WifiStateMachine(  963): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiServiceExtension(  963): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  963): stopMonitoring
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=on, calling pid 963
V/SRS_Proc(  275): ParamSet string: screen_state=on
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=on
V/voice   (  275): voice_set_parameters: enter: screen_state=on
,V/voice   (  275): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4320a9e0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1816): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:29:36
,I/SlideAside( 3548): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1816): 2 : This is isUpdating : false
,D/WeatherAncestor( 1816): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:29:36
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/WeatherService( 1816): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1816): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.453629 Y: -0.381226 Z: 9.797684 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453629 .y:-0.381226 .z:9.797684
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
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
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.435394 Y: -0.372070 Z: 9.774002 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.435394 .y:-0.372070 .z:9.774002
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
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
,D/qdlights( 1156): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1156): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1156): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 237, B = 237
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
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/qdhwcomposer(  272): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  963): Excessive delay in blankDisplay() while turning screen off: 411ms
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/dalvikvm( 1139): GC_FOR_ALLOC freed 5599K, 13% free 68967K/78424K, paused 25ms, total 28ms
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1139): changeTargets() succeeded. size: 20
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588576796, nextTick: 23237, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588576823, nextTick: 23209, mDrawingTime: 1
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
,D/WeatherService( 1816): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:29:36
,D/WeatherService( 1816): 2 : ACTION screen on
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1816): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:29:36
,D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
E/Parcel  (  584): Reading a NULL string not supported here.
E/Parcel  (  584): Reading a NULL string not supported here.
E/Parcel  (  584): Reading a NULL string not supported here.
,E/Parcel  (  584): Reading a NULL string not supported here.
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1139): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1139): notifyScreenOffLocked
,I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1}
D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/qcom_sensors_hal(  963): hal_acquire_resources
D/qcom_sensors_hal(  963): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  963): hal_smgr_report_delete: handle=0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  963): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  963): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: Rcvd success response from request
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
,V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,D/KeyguardViewMediator( 1139): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
D/KeyguardViewMediator( 1139): handleNotifyScreenOff
,D/KeyguardViewManager( 1139): onScreenTurnedOff()
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,I/LGImmersionVibrator(  963): Vibrator off
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{42bfa7f0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
,D/WifiStateMachine(  963): handleScreenStateChanged: false
D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: InitialState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: InitialState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): setSuspendOptimizations: 4 true
D/WifiStateMachine(  963): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  963): handleMessage: X
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=off
D/WifiController(  963): battery changed pluggedType: 2
D/WifiController(  963): CMD_SCREEN_OFF 
,D/WifiController(  963): shouldWifiStayAwake TRUE
V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=off, calling pid 963
V/SRS_Proc(  275): ParamSet string: screen_state=off
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1156): clear
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
D/qdlights( 1156): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 75, B = 75
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1156): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 69, B = 69
D/WeatherService( 1816): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:29:36
,D/WeatherService( 1816): 2 : ACTION screen off
,D/WeatherService( 1816): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:29:36
E/Parcel  (  584): Reading a NULL string not supported here.
E/Parcel  (  584): Reading a NULL string not supported here.
E/Parcel  (  584): Reading a NULL string not supported here.
,E/Parcel  (  584): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/qdlights( 1156): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 63, B = 63
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/NfcService( 1473): NFC-C OFF
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
D/qdlights( 1156): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 57, B = 57
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1156): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1156): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1156): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1156): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1156): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  328): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  288): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardViewMediator( 1139): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1139): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/KeyguardViewMediator( 1139): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1139): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588589568885101; DSPS: 5117901; Offset: 1449588433382941498
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588600042, nextTick: 59989, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588600043, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588609570176240; DSPS: 5773304; Offset: 1449588433382920381
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588629571565086; DSPS: 6428709; Offset: 1449588433382935936
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588649572430182; DSPS: 7084097; Offset: 1449588433382946540
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588660052, nextTick: 59979, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588660059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588669573529602; DSPS: 7739493; Offset: 1449588433382947327
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588689574359594; DSPS: 8394881; Offset: 1449588433382922827
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588709574786305; DSPS: 9050254; Offset: 1449588433382952809
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588720039, nextTick: 59992, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588720044, nextTick: 59966, mDrawingTime: 8
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588729575220256; DSPS: 9705629; Offset: 1449588433382928997
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588749576479675; DSPS: 10361030; Offset: 1449588433382937195
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588769576907897; DSPS: 11016404; Offset: 1449588433382938171
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=null, action=2
,W/GLSActivity( 1525): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1525): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1525): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1525): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1525): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/PlayEventLogger( 3720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3720): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3720): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3720): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3720): isDataSchedulerEnabled():false
D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,I/LocationManagerService(  963): remove 432a8348
,D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588780041, nextTick: 59985, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588780054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588789577349712; DSPS: 11671778; Offset: 1449588433382952740
,D/dalvikvm( 2618): GC_CONCURRENT freed 7676K, 32% free 16976K/24832K, paused 10ms+2ms, total 54ms
,D/dalvikvm( 2618): WAIT_FOR_CONCURRENT_GC blocked 45ms
,D/dalvikvm( 2618): GC_FOR_ALLOC freed 1620K, 32% free 17133K/24832K, paused 21ms, total 21ms
,I/Mlt MonitorService( 2618): parseLastkmsg to dump
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588809583470173; DSPS: 12327339; Offset: 1449588433382939168
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588829584945894; DSPS: 12982747; Offset: 1449588433382950045
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588840040, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588840048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588849586034950; DSPS: 13638143; Offset: 1449588433382940468
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588869586437337; DSPS: 14293516; Offset: 1449588433382946127
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588889592787018; DSPS: 14949084; Offset: 1449588433382948151
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588900041, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588900047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588909594054250; DSPS: 15604486; Offset: 1449588433382933645
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588929595112575; DSPS: 16259880; Offset: 1449588433382954372
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588949595601422; DSPS: 16915256; Offset: 1449588433382954938
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588960041, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449588960048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588969596946466; DSPS: 17570661; Offset: 1449588433382926691
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449588989599046719; DSPS: 18226089; Offset: 1449588433382951749
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589009599457648; DSPS: 18881463; Offset: 1449588433382935432
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589020040, nextTick: 59980, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589020047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589029605831287; DSPS: 19537032; Offset: 1449588433382930897
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589049607317894; DSPS: 20192441; Offset: 1449588433382922143
,I/ActivityManager(  963): Killing 3042:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bc5dd0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589069609851168; DSPS: 20847883; Offset: 1449588433382952975
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x43233270: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1525): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1525): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1525): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1525): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1525): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3720): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3720): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3720): Ignoring header User-Agent because its value was null.
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589080053, nextTick: 59967, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589080061, nextTick: 59970, mDrawingTime: 1
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  963): GC_CONCURRENT freed 1843K, 48% free 29926K/56644K, paused 9ms+6ms, total 134ms
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589089610716160; DSPS: 21503272; Offset: 1449588433382932957
,D/Finsky  ( 3720): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3720): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3720): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3720): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3720): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Finsky  ( 3720): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3720): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1423): client connected with version: 7571000
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589109611619070; DSPS: 22158661; Offset: 1449588433382950858
,D/Finsky  ( 3720): [342] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3720): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589129612954895; DSPS: 22814065; Offset: 1449588433382943909
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589140052, nextTick: 59975, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589140058, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589149613843429; DSPS: 23469454; Offset: 1449588433382947433
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589169614270140; DSPS: 24124828; Offset: 1449588433382946898
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589189618421538; DSPS: 24780324; Offset: 1449588433382947906
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589200029, nextTick: 59989, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589200052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589209618865905; DSPS: 25435699; Offset: 1449588433382934509
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589229619725430; DSPS: 26091087; Offset: 1449588433382939542
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589249620139693; DSPS: 26746461; Offset: 1449588433382926559
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589260052, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589260058, nextTick: 59973, mDrawingTime: 1,
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589269621598800; DSPS: 27401868; Offset: 1449588433382951340
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589289622825458; DSPS: 28057269; Offset: 1449588433382926777
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589309623235451; DSPS: 28712642; Offset: 1449588433382940041
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589320036, nextTick: 59992, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589320038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589329624307006; DSPS: 29368037; Offset: 1449588433382943481
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589349625594707; DSPS: 30023440; Offset: 1449588433382918926
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589369625999490; DSPS: 30678813; Offset: 1449588433382926981
,D/dalvikvm( 1525): GC_EXPLICIT freed 1371K, 29% free 17814K/24832K, paused 6ms+6ms, total 54ms
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GLSActivity( 1525): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1525): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1525): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1525): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1525): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3720): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3720): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3720): Ignoring header User-Agent because its value was null.
D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x4311e0e8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589380052, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589380055, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589389626859535; DSPS: 31334201; Offset: 1449588433382932534
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589409632244370; DSPS: 31989737; Offset: 1449588433382946275
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589429633499624; DSPS: 32645138; Offset: 1449588433382950308
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589440059, nextTick: 59971, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589440060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589449634957533; DSPS: 33300546; Offset: 1449588433382943373
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589469636210494; DSPS: 33955947; Offset: 1449588433382945114
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589489638438038; DSPS: 34611380; Offset: 1449588433382944874
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589500032, nextTick: 59991, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589500038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589509640050948; DSPS: 35266793; Offset: 1449588433382940353
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589529641292451; DSPS: 35922194; Offset: 1449588433382930635
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589549642839787; DSPS: 36577605; Offset: 1449588433382921575
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589560040, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589560043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589569644338737; DSPS: 37233014; Offset: 1449588433382925163
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589589645584042; DSPS: 37888414; Offset: 1449588433382949765
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589609646843826; DSPS: 38543816; Offset: 1449588433382927811
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589620039, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589620042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589629648501111; DSPS: 39199230; Offset: 1449588433382937147
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589649649762249; DSPS: 39854631; Offset: 1449588433382947064
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589669651011720; DSPS: 40510032; Offset: 1449588433382945314
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x432d2af0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1525): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1525): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1525): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1525): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1525): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3720): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3720): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3720): Ignoring header User-Agent because its value was null.
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  269): write error (Broken pipe)
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589680030, nextTick: 59991, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589680051, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589689652543015; DSPS: 41165442; Offset: 1449588433382950730
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589709654021184; DSPS: 41820851; Offset: 1449588433382933538
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589729655265551; DSPS: 42476252; Offset: 1449588433382926684
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589740041, nextTick: 59966, mDrawingTime: 10
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589740059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589749656551794; DSPS: 43131654; Offset: 1449588433382931189
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,W/SocketClient(  269): write error (Broken pipe)
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589769657863610; DSPS: 43787057; Offset: 1449588433382930749
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589789659128133; DSPS: 44442458; Offset: 1449588433382944051
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589800039, nextTick: 59986, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589800042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589809660742292; DSPS: 45097871; Offset: 1449588433382940779
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589829661991972; DSPS: 45753272; Offset: 1449588433382939238
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589849663554568; DSPS: 46408683; Offset: 1449588433382945438
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589860041, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589860059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589869664843779; DSPS: 47064086; Offset: 1449588433382922393
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589889666087261; DSPS: 47719486; Offset: 1449588433382945172
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589909667396212; DSPS: 48374889; Offset: 1449588433382941867
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589920049, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589920052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589929668827819; DSPS: 49030296; Offset: 1449588433382939148
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589949670078593; DSPS: 49685697; Offset: 1449588433382938701
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589969671339731; DSPS: 50341098; Offset: 1449588433382948618
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x44367248: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1525): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1525): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1525): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1525): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1525): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3720): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3720): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3720): Ignoring header User-Agent because its value was null.
,D/libc    (  269): _dns_getaddrinfo: iptype =0
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  269): write error (Broken pipe)
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589980039, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449589980048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449589989672245400; DSPS: 50996488; Offset: 1449588433382938760
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590009673493100; DSPS: 51651889; Offset: 1449588433382935239
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590029674850750; DSPS: 52307294; Offset: 1449588433382919598
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590040036, nextTick: 59985, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590040042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590049676196679; DSPS: 52962697; Offset: 1449588433382953271
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590069678130890; DSPS: 53618121; Offset: 1449588433382934357
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590089679388748; DSPS: 54273522; Offset: 1449588433382940995
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590100041, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590100048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590109680910146; DSPS: 54928932; Offset: 1449588433382936514
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590129682206858; DSPS: 55584334; Offset: 1449588433382951487
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590149683446849; DSPS: 56239735; Offset: 1449588433382940258
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590160039, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590160045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590169684737259; DSPS: 56895137; Offset: 1449588433382948929
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590189686039022; DSPS: 57550540; Offset: 1449588433382938437
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590209687289431; DSPS: 58205941; Offset: 1449588433382937625
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590220040, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590220043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590229689141870; DSPS: 58861362; Offset: 1449588433382928492
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590249690018114; DSPS: 59516750; Offset: 1449588433382950243
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590269691346908; DSPS: 60172154; Offset: 1449588433382936264
,I/ProcessStatsService(  963): Prepared write state in 41ms
,I/GLSUser ( 1525): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1525): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1525): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1525): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1525): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1525): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  963): GC_CONCURRENT freed 2871K, 46% free 30426K/56296K, paused 12ms+10ms, total 155ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 146ms
D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 145ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 145ms
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x44c796f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1525): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1525): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1525): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1525): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1525): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1525): 	at dalvik.system.NativeStart.run(Native Method)
E/PlayEventLogger( 3720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3720): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3720): 	at dalvik.system.NativeStart.run(Native Method)
W/System  ( 3720): Ignoring header User-Agent because its value was null.
D/libc    (  269): _dns_getaddrinfo: iptype =0
D/libc    (  269): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/ProcessStatsService(  963): Pruning old procstats: /data/system/procstats/state-2015-12-07-15-36-35.bin
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
I/ActivityManager(  963): Killing 3790:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1803s
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590280049, nextTick: 59965, mDrawingTime: 7
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590280061, nextTick: 59971, mDrawingTime: 0
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bc5dd0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590289692616015; DSPS: 60827556; Offset: 1449588433382923633
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590309694087309; DSPS: 61482964; Offset: 1449588433382930083
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590329695622874; DSPS: 62138374; Offset: 1449588433382939769
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590340034, nextTick: 59975, mDrawingTime: 10
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1449590340050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1449590349696899585; DSPS: 62793776; Offset: 1449588433382934742
,TIME-OUT KILL (timeout was 1800000ms)
```
