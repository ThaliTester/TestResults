#### Test 513350282ff9e94_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1951): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1951): launchTask
W/dalvikvm( 1951): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1951): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1951): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1951): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1951): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1951): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1951): No vision deps
V/ConfigFetchTask( 1951): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XQ1P_6NSiK8Z8fA91FIERo9fpbmbvaNvzfhtK38p1VJJz0peIw0z9pApsGLqVPM2-gCgZK8zcqzRHARa7qhdQZ9DYA6GJWKzhh3oJAbLD-8XKAMWtJ6GbABiveXumh30GN1Auo50uEkkHEz0x6pWW-2GSGbhXw1RjA5wx75e6cidjsYLtxgr9O2wDDlV99FzypRqqI
I/GoogleURLConnFactory( 1951): Using platform SSLCertificateSocketFactory
W/BaseAppContext( 1951): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1951): CP2 sync disabled
W/BaseAppContext( 1951): Using Auth Proxy for data requests.
I/dalvikvm( 1951): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1951): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1951): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1951): Using Auth Proxy for data requests.
D/dalvikvm( 1552): null clazz in OP_INSTANCE_OF, single-stepping
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
W/BaseAppContext( 1951): Using Auth Proxy for data requests.
E/DataScheduler( 1951): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
W/BaseAppContext( 1951): Using Auth Proxy for data requests.
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1951): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1951): fetch service done; releasing wakelock
I/ConfigFetchService( 1951): stopping self
W/GAV2    ( 4078): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  954): Killing 3444:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  954): resumeTopActivitiesLocked(): target Stack:ActivityStack{43299ff0 stackId=1, 1 tasks}
D/ActivityManager(  954): resumeTopActivityLocked: Top activity resumed ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ChimeraCfgMgr( 1951): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1951): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1951): GC_CONCURRENT freed 1510K, 26% free 18454K/24832K, paused 2ms+3ms, total 26ms
D/AndroidRuntime( 4122): 
D/AndroidRuntime( 4122): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4122): CheckJNI is OFF
D/dalvikvm( 4122): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4122): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4122): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4122): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4122): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4122): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4122): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4122): failed to load memtrack module: -2
I/Icing   ( 1951): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4122): Calling main entry com.android.commands.am.Am
D/Icing   ( 1951): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  954): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4122
I/ActivityManager(  954): resumeTopActivitiesLocked(): target Stack:ActivityStack{43299ff0 stackId=1, 2 tasks}
V/ActivityManager(  954): Moving to PAUSING: ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (160 us)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ActivityManager(  954): resumeTopActivityLocked: Pausing null
V/ActivityManager(  954): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  954): startService SlideAside
W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  954): setFocusedStack: mFocusedStack=ActivityStack{43299ff0 stackId=1, 2 tasks}
D/AndroidRuntime( 4122): Shutting down VM
D/UsbSettingsControl( 2542): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2542): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  954): allPausedActivitiesComplete: r=ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/dalvikvm( 4122): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
V/ActivityManager(  954): Moving to PAUSED: ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  954): resumeTopActivitiesLocked(): target Stack:ActivityStack{43299ff0 stackId=1, 2 tasks}
D/ActivityManager(  954): resumeTopActivityLocked: Restarting ActivityRecord{43b83170 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  954): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4154 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3572): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/SlideAside( 3572): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3572): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  954): Moving to RESUMED: ActivityRecord{43b83170 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4154): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4154): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4154): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Icing   ( 1951): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4154): Binding Chromium to the background looper Looper (main, tid 1) {42895e58}
I/chromium( 4154): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4154): Initializing chromium process, renderers=0
I/Adreno-EGL( 4154): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4154): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4154): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4154): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4154): Remote Branch: 
I/Adreno-EGL( 4154): Local Patches: 
I/Adreno-EGL( 4154): Reconstruct Branch: 
W/chromium( 4154): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/dalvikvm( 4154): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4154): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4154): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4154): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4154): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4154): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4154): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4154): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4154): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4154): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4154): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4154): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4154): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4154): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4154): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4154): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4154): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4154): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4154): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4154): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4154): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4154): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4154): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4154): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4154): Enabling debug mode 0
W/AwContents( 4154): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  954): Displayed com.test.thalitest/.MainActivity: +360ms
I/ActivityManager( 4154): Timeline: Activity_idle id: android.os.BinderProxy@42897718 time:110951
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/JsMessageQueue( 4154): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4154): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4289bc30
D/dalvikvm( 4154): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4289bc30
D/jxcore_app_log( 4154): JniHelper::setJavaVM(0x4175f838), pthread_self() = 1631985328
D/JX-Cordova( 4154): jxcore cordova android initializing
I/dalvikvm( 4154): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 4154): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4154): VFY: replacing opcode 0x6e at 0x0045
I/ActivityManager(  954): Timeline: Activity_windows_visible id: ActivityRecord{43b83170 u0 com.test.thalitest/.MainActivity t3} time:111351
D/UsbSettings( 2542): [AUTORUN] onStop()
D/ActivityManager(  954): no-history finish of ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  954): Finishing activity token=Token{432ed058 ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  954): Moving to FINISHING: ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  954): resumeTopActivityLocked: Top activity resumed ActivityRecord{43b83170 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  954): Moving to STOPPING: ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  954): Moving to STOPPED: ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4154): GC_CONCURRENT freed 2852K, 13% free 21794K/24832K, paused 3ms+2ms, total 36ms
D/dalvikvm( 4154): WAIT_FOR_CONCURRENT_GC blocked 23ms
I/dalvikvm-heap( 4154): Grow heap (frag case) to 23.550MB for 98002-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4154): GC_FOR_ALLOC freed 254K, 13% free 21757K/24928K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 23.560MB for 146998-byte allocation
,D/dalvikvm( 4154): GC_FOR_ALLOC freed 263K, 14% free 21798K/25072K, paused 21ms, total 22ms
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 23.671MB for 220492-byte allocation
,D/dalvikvm( 4154): GC_FOR_ALLOC freed 376K, 14% free 21874K/25288K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 23.850MB for 330734-byte allocation
,D/dalvikvm( 4154): GC_FOR_ALLOC freed 580K, 15% free 21998K/25612K, paused 21ms, total 22ms
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 24.129MB for 496096-byte allocation
,D/dalvikvm( 4154): GC_FOR_ALLOC freed 882K, 16% free 22176K/26100K, paused 22ms, total 22ms
,D/dalvikvm( 4154): GC_FOR_ALLOC freed 1305K, 15% free 22437K/26100K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 25.149MB for 1116206-byte allocation
,D/dalvikvm( 4154): GC_CONCURRENT freed 1739K, 17% free 22822K/27192K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 4154): GC_FOR_ALLOC freed 331K, 17% free 22791K/27192K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 26.027MB for 1674304-byte allocation
,D/dalvikvm( 4154): GC_CONCURRENT freed 1849K, 19% free 23429K/28828K, paused 1ms+3ms, total 46ms
,D/dalvikvm( 4154): GC_FOR_ALLOC freed 1291K, 19% free 23424K/28828K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 27.444MB for 2511452-byte allocation
,D/dalvikvm( 4154): GC_CONCURRENT freed 259K, 18% free 25771K/31284K, paused 2ms+2ms, total 28ms
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.556152 Y: -0.387726 Z: 9.710968 
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.556152 .y:-0.387726 .z:9.710968
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.565994 Y: -0.373749 Z: 9.719055 
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565994 .y:-0.373749 .z:9.719055
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4154): GC_CONCURRENT freed 4408K, 22% free 24419K/31284K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 4154): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 29.613MB for 3767174-byte allocation
,D/dalvikvm( 4154): GC_CONCURRENT freed 2942K, 27% free 25557K/34964K, paused 2ms+4ms, total 50ms
,W/jxcore-log( 4154): Initializing JXcore engine
,W/jxcore-log( 4154): JXcore engine is ready
,D/dalvikvm( 4154): GC_CONCURRENT freed 582K, 20% free 27983K/34964K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 4154): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4154): Starting JXcore engine
,W/jxcore-log( 4154): Platform android
W/jxcore-log( 4154): 
,W/jxcore-log( 4154): Process ARCH arm
W/jxcore-log( 4154): 
,I/jxcore-log( 4154): JXcore Cordova bridge is ready!
I/jxcore-log( 4154): 
W/jxcore-log( 4154): JXcore engine is started
I/chromium( 4154): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/chromium( 4154): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4154): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/jxcore-log( 4154): Toggling radios to true
I/jxcore-log( 4154): 
D/BluetoothManagerService(  954): Message: 20
D/BluetoothManagerService(  954): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4498d080:true
D/BluetoothAdapter( 4154): enable(): BT is already enabled..!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4078): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1552): onDestroy
,D/BluetoothManagerService(  954): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4154): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): my name is : LGE-LG-D802_PT7882
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): attempting to connect to test coordinator
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): check test folder
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): found test : ./testFindPeers.js
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): found test : ./testReConnect.js
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): found test : ./testSendData.js
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): Test app app.js loaded
I/jxcore-log( 4154): 
,I/Choreographer( 4154): Skipped 111 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/chromium( 4154): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4154): 
,E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  954): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  954): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3708): [345] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3708): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.559525 Y: -0.381470 Z: 9.747406 
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.559525 .y:-0.381470 .z:9.747406
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.561386 Y: -0.381485 Z: 9.744080 
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.561386 .y:-0.381485 .z:9.744080
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/PowerManagerService(  954): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  954): [updateScreenState] screen on = false
D/KnockOnPowerController(  954): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  954): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  954): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  954): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  954): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  954): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  954): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  954): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8528 usec
D/KnockOnPowerController(  954): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  954): hal_acquire_resources
,I/qcom_sensors_hal(  954): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  954): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  954): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  954): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  954): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  954): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  954): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.535843 Y: -0.367020 Z: 9.756317 
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.535843 .y:-0.367020 .z:9.756317
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.545242 Y: -0.374741 Z: 9.771790 
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.545242 .y:-0.374741 .z:9.771790
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,I/Sensors (  592): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  954): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  954): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  954): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  954): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  954): proximitySensorChanged  positive = true
I/KnockOnPowerController(  954): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.546417 Y: -0.378021 Z: 9.763443 
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.546417 .y:-0.378021 .z:9.763443
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.540482 Y: -0.381973 Z: 9.745041 
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.540482 .y:-0.381973 .z:9.745041
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.545334 Y: -0.384720 Z: 9.745728 
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.545334 .y:-0.384720 .z:9.745728
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.545990 Y: -0.365860 Z: 9.748337 
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.545990 .y:-0.365860 .z:9.748337
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.540634 Y: -0.352478 Z: 9.755539 
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.540634 .y:-0.352478 .z:9.755539
,D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb700a450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/KeyguardServiceDelegate(  954): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43bc69c0)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1143): notifyScreenOnLocked
,D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  954): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
I/WindowManager(  954): No lock screen! windowToken=null
,D/NfcServiceBRCM( 1477): NFC is already turned off.
,D/WifiStateMachine(  954): handleScreenStateChanged: true
,D/WifiStateMachine(  954): handleMessage: E msg.what=131154
D/WifiStateMachine(  954): processMsg: InitialState
,D/WifiStateMachine(  954): processMsg: DefaultState
,D/WifiStateMachine(  954): handleMessage: X
D/WifiStateMachine(  954): handleMessage: E msg.what=131127
,D/WifiStateMachine(  954): processMsg: InitialState
D/WifiStateMachine(  954): processMsg: DefaultState
D/WifiStateMachine(  954): handleMessage: X
,D/WifiStateMachine(  954): handleMessage: E msg.what=131158
D/WifiStateMachine(  954): processMsg: InitialState
D/WifiStateMachine(  954): processMsg: DefaultState
,D/WifiStateMachine(  954): setSuspendOptimizations: 4 false
D/WifiStateMachine(  954): mSuspendOptNeedsDisabled 4
D/WifiStateMachine(  954): handleMessage: X
,D/WifiServiceExtension(  954): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  954): stopMonitoring
,E/AudioSystem(  954): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 954
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4323e2f0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,E/SlideAside( 3572): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1827): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:47:38
,I/SlideAside( 3572): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1827): 2 : This is isUpdating : false
,D/WeatherAncestor( 1827): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:47:38
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1827): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1827): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1827): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  954): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
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
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  954): Excessive delay in blankDisplay() while turning screen off: 419ms
D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365658879, nextTick: 21154, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,I/dalvikvm(  954): Jit: resizing JitTable from 8192 to 16384
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365658909, nextTick: 21124, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/NfcServiceBRCM( 1477): NFC is already turned off.
,V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  954): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  954): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  954): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  954): hal_process_report_ind: X: -0.542023 Y: -0.371735 Z: 9.757477 
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.542023 .y:-0.371735 .z:9.757477
D/qcom_sensors_hal(  954): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=0
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/WeatherService( 1827): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:47:38
,D/WeatherService( 1827): 2 : ACTION screen on
D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/WeatherService( 1827): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1827): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:47:38
,V/PhoneApp( 1453): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  954): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  954): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  954): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  954): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
,D/qcom_sensors_hal(  954): hal_acquire_resources
D/qcom_sensors_hal(  954): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  954): hal_smgr_report_delete: handle=0
,V/ActivityManager(  954): Moving to PAUSING: ActivityRecord{43b83170 u0 com.test.thalitest/.MainActivity t3}
D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
D/qcom_sensors_hal(  954): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  954): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  954): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  954): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  954): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
W/ProcessCpuTracker(  954): Skipping unknown process pid 4261
W/ProcessCpuTracker(  954): Skipping unknown process pid 4262
W/ProcessCpuTracker(  954): Skipping unknown process pid 4265
W/ProcessCpuTracker(  954): Skipping unknown process pid 4267
D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
W/ProcessCpuTracker(  954): Skipping unknown process pid 4271
V/ActivityManager(  954): Moving to PAUSED: ActivityRecord{43b83170 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  954): Moving to STOPPING: ActivityRecord{43b83170 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,I/rmt_storage(  625): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8ed8178
I/rmt_storage(  625): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  625): wakelock acquired: 1, error no: 42
,I/rmt_storage(  625): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1192394184)
D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/UsbSettings( 2542): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/ActivityManager(  954): Moving to DESTROYING: ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/LGImmersionVibrator(  954): Vibrator off
D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/UsbSettings( 2542): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2542): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2542): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
V/ActivityManager(  954): Moving to STOPPED: ActivityRecord{43b83170 u0 com.test.thalitest/.MainActivity t3} (stop complete)
,D/WifiStateMachine(  954): handleScreenStateChanged: false
,D/WifiStateMachine(  954): handleMessage: E msg.what=131154
D/WifiStateMachine(  954): processMsg: InitialState
D/WifiStateMachine(  954): processMsg: DefaultState
,D/WifiStateMachine(  954): handleMessage: X
,D/WifiStateMachine(  954): handleMessage: E msg.what=131158
D/WifiStateMachine(  954): processMsg: InitialState
,D/WifiStateMachine(  954): processMsg: DefaultState
D/WifiStateMachine(  954): setSuspendOptimizations: 4 true
,D/WifiStateMachine(  954): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  954): handleMessage: X
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  954): CMD_SCREEN_OFF 
,D/WifiController(  954): shouldWifiStayAwake TRUE
E/AudioSystem(  954): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 954
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/ActivityManager(  954): Moving to DESTROYED: ActivityRecord{432ecef0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  954): resumeTopActivitiesLocked(): target Stack:ActivityStack{43299ff0 stackId=1, 1 tasks}
D/ActivityManager(  954): resumeTopActivityLocked: Going to sleep and all paused
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1157): clear
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/KeyguardViewMediator( 1143): handleNotifyScreenOff
,D/KeyguardViewManager( 1143): onScreenTurnedOff()
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  954): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
D/NfcServiceBRCM( 1477): NFC is already turned off.
,I/[LGHome]EVENT( 1491): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
V/TelephonyAutoProfiling(  954): [getValue] FEATURE key : trf_based_vzw, value : null
,V/LGRssiData(  954): [loadRssi] File not exist 
E/Parcel  (  613): Reading a NULL string not supported here.
E/Parcel  (  613): Reading a NULL string not supported here.
E/Parcel  (  613): Reading a NULL string not supported here.
,E/Parcel  (  613): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1453): [PhoneIntfMgr] sigLevel = 0
D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1827): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:47:39
D/WeatherService( 1827): 2 : ACTION screen off
D/WeatherService( 1827): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:47:39
V/PhoneApp( 1453): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1465): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,I/rmt_storage(  625): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  625): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  625): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1192394184) wakelock released: 1, error no: 0
I/rmt_storage(  625): 
E/Diag_Lib(  698): [IMS_FATAL]| 2912 | 703 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,I/rmt_storage(  625): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8ed8178
D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  592): sns_pwr.c(320):releasing wakelock
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/WifiController(  954): battery changed pluggedType: 2
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,E/ThermalEngine(  287): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365671983053435; DSPS: 5115196; Offset: 1448365515879659881
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365680036, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365680042, nextTick: 59975, mDrawingTime: 5
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  954): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  954): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  954): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365691984739833; DSPS: 5770611; Offset: 1448365515879667812
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365711986518524; DSPS: 6426030; Offset: 1448365515879645966
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365731988380964; DSPS: 7081451; Offset: 1448365515879646834
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365740029, nextTick: 60000, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365740056, nextTick: 59975, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365751989992571; DSPS: 7736863; Offset: 1448365515879671527
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365771991848657; DSPS: 8392284; Offset: 1448365515879666040
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365791993715472; DSPS: 9047705; Offset: 1448365515879671283
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365800049, nextTick: 59980, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365800058, nextTick: 59966, mDrawingTime: 3
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365811995525882; DSPS: 9703125; Offset: 1448365515879650638
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365831998331030; DSPS: 10358577; Offset: 1448365515879648169
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  954): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  954): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  954): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365851999896907; DSPS: 11013988; Offset: 1448365515879657650
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  954): updateLightListLocked :r=null, action=2
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3708): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3708): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3708): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3708): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 3708): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3708): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365860050, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365860056, nextTick: 59974, mDrawingTime: 2
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/dalvikvm( 2597): GC_CONCURRENT freed 7737K, 32% free 16907K/24832K, paused 18ms+3ms, total 101ms
,D/dalvikvm( 2597): WAIT_FOR_CONCURRENT_GC blocked 57ms
,D/dalvikvm( 2597): GC_CONCURRENT freed 1830K, 32% free 17125K/24832K, paused 4ms+1ms, total 29ms
,D/dalvikvm( 2597): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2597): GC_CONCURRENT freed 1219K, 29% free 17854K/24832K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 2597): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Mlt MonitorService( 2597): parseLastkmsg to dump
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365872001480233; DSPS: 11669400; Offset: 1448365515879654062
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  954): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365892002844184; DSPS: 12324805; Offset: 1448365515879644722
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365912007962510; DSPS: 12980332; Offset: 1448365515879666612
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365920045, nextTick: 59984, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365920048, nextTick: 59978, mDrawingTime: 3
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365932009834481; DSPS: 13635754; Offset: 1448365515879646493
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365952010443900; DSPS: 14291134; Offset: 1448365515879645561
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365972011557747; DSPS: 14946530; Offset: 1448365515879660775
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365980041, nextTick: 59967, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448365980057, nextTick: 59975, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448365992013455657; DSPS: 15601952; Offset: 1448365515879666595
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366012015303982; DSPS: 16257373; Offset: 1448365515879653348
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366032016414339; DSPS: 16912769; Offset: 1448365515879665072
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366040051, nextTick: 59967, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366040060, nextTick: 59968, mDrawingTime: 2
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366052018382196; DSPS: 17568194; Offset: 1448365515879649286
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366072020002708; DSPS: 18223607; Offset: 1448365515879652367
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366092021194785; DSPS: 18879006; Offset: 1448365515879654258
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366100039, nextTick: 59980, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366100048, nextTick: 59980, mDrawingTime: 2
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366112026854881; DSPS: 19534551; Offset: 1448365515879668602
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366132028832895; DSPS: 20189976; Offset: 1448365515879662974
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/ActivityManager(  954): Killing 3392:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  954): Service ServiceRecord{432f5b30 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43138e18 3392:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  954): Service ServiceRecord{432b4ac0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43138e18 3392:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  954): resumeTopActivitiesLocked(): target Stack:ActivityStack{43299ff0 stackId=1, 1 tasks}
,D/ActivityManager(  954): resumeTopActivityLocked: Going to sleep and all paused
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366152030855908; DSPS: 20845403; Offset: 1448365515879641309
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  954): GC_EXPLICIT freed 22846K, 48% free 29433K/56216K, paused 5ms+13ms, total 239ms
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  954): updateLightListLocked :r=NotificationRecord(0x441170a0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  954): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3708): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3708): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3708): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3708): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3708): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366160040, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366160048, nextTick: 59980, mDrawingTime: 2
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/Finsky  ( 3708): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  954): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  954): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  954): handleInetConditionChange: no active default network - ignore
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3708): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3708): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 3708): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3708): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3708): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3708): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1428): client connected with version: 7571000
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366172032607723; DSPS: 21500820; Offset: 1448365515879653622
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/Finsky  ( 3708): [345] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3708): [1] 5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366192034533706; DSPS: 22156243; Offset: 1448365515879656998
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366212036175520; DSPS: 22811657; Offset: 1448365515879650862
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366220043, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366220058, nextTick: 59974, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366232037606137; DSPS: 23467064; Offset: 1448365515879647153
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366252039159776; DSPS: 24122475; Offset: 1448365515879644396
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366272041039195; DSPS: 24777896; Offset: 1448365515879662242
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366280051, nextTick: 59971, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366280057, nextTick: 59974, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366292043558459; DSPS: 25433339; Offset: 1448365515879648547
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366312045467305; DSPS: 26088761; Offset: 1448365515879665304
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366332047296620; DSPS: 26744181; Offset: 1448365515879663564
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366340046, nextTick: 59980, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366340050, nextTick: 59981, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366352048698384; DSPS: 27399587; Offset: 1448365515879661519
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366372050449313; DSPS: 28055005; Offset: 1448365515879642429
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366392052118993; DSPS: 28710419; Offset: 1448365515879664160
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366400049, nextTick: 59970, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366400057, nextTick: 59976, mDrawingTime: 0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366412053882892; DSPS: 29365837; Offset: 1448365515879658039
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366432055839343; DSPS: 30021261; Offset: 1448365515879661365
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366452057490533; DSPS: 30676675; Offset: 1448365515879664606
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  954): updateLightListLocked :r=NotificationRecord(0x43cd0650: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  954): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3708): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3708): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3708): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3708): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3708): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366460064, nextTick: 59965, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366460065, nextTick: 59968, mDrawingTime: 0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366472059305734; DSPS: 31332095; Offset: 1448365515879648752
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366492061168746; DSPS: 31987516; Offset: 1448365515879650192
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366512063163427; DSPS: 32642941; Offset: 1448365515879661230
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366520045, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366520048, nextTick: 59982, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366532064574096; DSPS: 33298347; Offset: 1448365515879668091
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366552066484922; DSPS: 33953770; Offset: 1448365515879656309
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366572068481216; DSPS: 34609196; Offset: 1448365515879638443
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366580051, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366580056, nextTick: 59972, mDrawingTime: 2
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366592070243865; DSPS: 35264613; Offset: 1448365515879661590
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366612071621615; DSPS: 35920018; Offset: 1448365515879666049
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366632074225517; DSPS: 36575464; Offset: 1448365515879645439
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366640038, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366640046, nextTick: 59959, mDrawingTime: 10
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366652076212488; DSPS: 37230889; Offset: 1448365515879648768
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366672077610501; DSPS: 37886295; Offset: 1448365515879642972
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366692079515389; DSPS: 38541717; Offset: 1448365515879655770
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366700032, nextTick: 59993, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366700057, nextTick: 59972, mDrawingTime: 3
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366712081320433; DSPS: 39197136; Offset: 1448365515879660277
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366732083802406; DSPS: 39852577; Offset: 1448365515879670326
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366752085589898; DSPS: 40507996; Offset: 1448365515879657281
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/dalvikvm( 1552): GC_EXPLICIT freed 1569K, 29% free 17807K/24832K, paused 11ms+6ms, total 103ms
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  954): updateLightListLocked :r=NotificationRecord(0x43ac9758: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,D/NotificationService(  954): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
E/PlayEventLogger( 3708): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3708): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3708): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3708): 	at dalvik.system.NativeStart.run(Native Method)
W/System  ( 3708): Ignoring header User-Agent because its value was null.
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366760057, nextTick: 59960, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366760066, nextTick: 59964, mDrawingTime: 2
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366772087202390; DSPS: 41163409; Offset: 1448365515879652342
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366792088961705; DSPS: 41818827; Offset: 1448365515879641637
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  954): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  954): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  954): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366812090646802; DSPS: 42474242; Offset: 1448365515879648267
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366820045, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366820047, nextTick: 59981, mDrawingTime: 2
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366832093317733; DSPS: 43129689; Offset: 1448365515879664169
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366852095057881; DSPS: 43785106; Offset: 1448365515879664815
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366872096949279; DSPS: 44440528; Offset: 1448365515879664123
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366880050, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366880060, nextTick: 59965, mDrawingTime: 3
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366892098703647; DSPS: 45095946; Offset: 1448365515879648472
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366912100669576; DSPS: 45751370; Offset: 1448365515879661276
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366932102733944; DSPS: 46406798; Offset: 1448365515879650448
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366940043, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448366940048, nextTick: 59973, mDrawingTime: 5
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366952104300864; DSPS: 47062209; Offset: 1448365515879660972
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366972106248876; DSPS: 47717633; Offset: 1448365515879655859
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448366992107730066; DSPS: 48373042; Offset: 1448365515879641688
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367000038, nextTick: 59966, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367000057, nextTick: 59975, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367012109804590; DSPS: 49028469; Offset: 1448365515879671534
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  954): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367032111570467; DSPS: 49683887; Offset: 1448365515879667391
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367052113830409; DSPS: 50339321; Offset: 1448365515879669033
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  954): updateLightListLocked :r=NotificationRecord(0x43b8a188: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  954): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/PlayEventLogger( 3708): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3708): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3708): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3708): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3708): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/dalvikvm(  954): GC_CONCURRENT freed 2891K, 48% free 29672K/56216K, paused 10ms+7ms, total 133ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367060032, nextTick: 59991, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367060059, nextTick: 59965, mDrawingTime: 3
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367072115107172; DSPS: 50994723; Offset: 1448365515879664057
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367092116938257; DSPS: 51650143; Offset: 1448365515879664088
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367112118802000; DSPS: 52305564; Offset: 1448365515879666258
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367120038, nextTick: 59957, mDrawingTime: 15
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367120062, nextTick: 59968, mDrawingTime: 2
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367132120725325; DSPS: 52960987; Offset: 1448365515879666976
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367152122399432; DSPS: 53616402; Offset: 1448365515879662616
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367172124323436; DSPS: 54271825; Offset: 1448365515879664013
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367180019, nextTick: 59992, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367180060, nextTick: 59972, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367192126174417; DSPS: 54927246; Offset: 1448365515879653421
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367212128168525; DSPS: 55582671; Offset: 1448365515879663887
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367232129619037; DSPS: 56238079; Offset: 1448365515879649555
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367240021, nextTick: 60002, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367240062, nextTick: 59971, mDrawingTime: 0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367252131249290; DSPS: 56893492; Offset: 1448365515879662376
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367272133448450; DSPS: 57548924; Offset: 1448365515879664271
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367292135141723; DSPS: 58204340; Offset: 1448365515879648559
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367300057, nextTick: 59968, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367300062, nextTick: 59968, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367312136814163; DSPS: 58859755; Offset: 1448365515879642533
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367332137910510; DSPS: 59515150; Offset: 1448365515879670764
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367352139898731; DSPS: 60170576; Offset: 1448365515879644825
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/ProcessStatsService(  954): Prepared write state in 38ms
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  954): updateLightListLocked :r=NotificationRecord(0x448e2018: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  954): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3708): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3708): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3708): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3708): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3708): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3708): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ProcessStatsService(  954): Pruning old procstats: /data/system/procstats/state-2015-11-23-20-21-39.bin
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/ActivityManager(  954): Killing 3815:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1800s
,I/ActivityManager(  954): Killing 3027:android.process.media/u0a23 (adj 15): empty for 1801s
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367360044, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367360047, nextTick: 59983, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ActivityManager(  954): resumeTopActivitiesLocked(): target Stack:ActivityStack{43299ff0 stackId=1, 1 tasks}
,D/ActivityManager(  954): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  954): resumeTopActivitiesLocked(): target Stack:ActivityStack{43299ff0 stackId=1, 1 tasks}
,D/ActivityManager(  954): resumeTopActivityLocked: Going to sleep and all paused
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367372141700494; DSPS: 60825995; Offset: 1448365515879646051
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367392143801946; DSPS: 61481424; Offset: 1448365515879641790
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367412145522875; DSPS: 62136840; Offset: 1448365515879653735
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367420034, nextTick: 59967, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448367420054, nextTick: 59977, mDrawingTime: 1
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,D/qcom_sensors_hal(  954): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  954): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  954): hal_ts_offset_is: Apps: 1448367432147311461; DSPS: 62792259; Offset: 1448365515879641784
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,I/jxcore-log( 4154): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4154): 
,TIME-OUT KILL (timeout was 1800000ms)
```
