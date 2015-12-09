#### Test 5065027873d6a28_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/Vision  ( 1959): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1959): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1959): No vision deps
I/PeopleContactsSync( 1959): CP2 sync disabled
V/ConfigFetchTask( 1959): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WBKaowq0FQEaVXefge7sPhlxoH22bRvVhQk5gJ6IGaZQxHwOTFmeJV_o7bjQpvB1bXmk8x7V06l2CcUyI5bxUE7bc6xOSbr_1B2zJ0GKzlBIuDlBJRRzKUHGlazvT_Ov9GGy4MaiedCHED-UxQVnfPbJbBtR-4sQKKuOFaqbOpY_DdBRmVNR2jAZgZieu1oJu_nu5A
I/dalvikvm( 1959): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1959): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1959): VFY: replacing opcode 0x6e at 0x000e
I/GoogleURLConnFactory( 1959): Using platform SSLCertificateSocketFactory
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
E/DataScheduler( 1959): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =0
D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1959): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1959): fetch service done; releasing wakelock
I/ConfigFetchService( 1959): stopping self
,D/dalvikvm( 1959): GC_CONCURRENT freed 1571K, 27% free 18375K/24832K, paused 3ms+8ms, total 39ms
W/GAV2    ( 4087): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  961): Killing 3506:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300408 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ChimeraCfgMgr( 1959): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1959): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4129): 
D/AndroidRuntime( 4129): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4129): CheckJNI is OFF
D/dalvikvm( 4129): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4129): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4129): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4129): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4129): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4129): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4129): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4129): failed to load memtrack module: -2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4129): Calling main entry com.android.commands.am.Am
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4129
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300408 stackId=1, 2 tasks}
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  275): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (105 us)
I/Icing   ( 1959): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/dalvikvm(  961): GC_FOR_ALLOC freed 22086K, 51% free 28314K/57152K, paused 118ms, total 118ms
D/ActivityManager(  961): resumeTopActivityLocked: Pausing null
V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  961): setFocusedStack: mFocusedStack=ActivityStack{43300408 stackId=1, 2 tasks}
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/UsbSettingsControl( 2584): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2584): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/ActivityManager(  961): startService SlideAside
D/AndroidRuntime( 4129): Shutting down VM
I/SlideAside( 3563): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4129): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300408 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Restarting ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  961): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4155 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3563): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3563): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4155): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4155): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4155): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/Icing   ( 1959): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WebViewChromium( 4155): Binding Chromium to the background looper Looper (main, tid 1) {42880b18}
I/chromium( 4155): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4155): Initializing chromium process, renderers=0
W/chromium( 4155): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4155): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4155): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4155): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4155): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4155): Remote Branch: 
I/Adreno-EGL( 4155): Local Patches: 
I/Adreno-EGL( 4155): Reconstruct Branch: 
I/Icing   ( 1959): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/dalvikvm( 4155): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4155): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4155): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4155): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4155): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4155): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4155): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4155): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4155): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4155): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4155): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4155): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4155): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4155): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4155): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4155): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4155): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4155): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4155): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4155): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/BaseRuntimeLoader( 4155): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4155): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4155): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4155): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiController(  961): battery changed pluggedType: 2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4155): Enabling debug mode 0
W/AwContents( 4155): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  961): Displayed com.test.thalitest/.MainActivity: +408ms
W/AwContents( 4155): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  961): IME STATUS OFF
I/ActivityManager( 4155): Timeline: Activity_idle id: android.os.BinderProxy@428823d8 time:110723
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/JsMessageQueue( 4155): Set native->JS mode to OnlineEventsBridgeMode
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4155): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428864b8
D/dalvikvm( 4155): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428864b8
D/jxcore_app_log( 4155): JniHelper::setJavaVM(0x4174d838), pthread_self() = 1639249784
D/JX-Cordova( 4155): jxcore cordova android initializing
I/dalvikvm( 4155): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4155): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4155): VFY: replacing opcode 0x6e at 0x0045
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3} time:111036
D/ActivityManager(  961): no-history finish of ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  961): Finishing activity token=Token{432e30a8 ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2584): [AUTORUN] onStop()
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4155): GC_CONCURRENT freed 2773K, 12% free 21879K/24832K, paused 2ms+1ms, total 44ms
,D/dalvikvm( 4155): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 209K, 12% free 21859K/24832K, paused 23ms, total 23ms
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 186K, 12% free 21888K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 23.686MB for 143930-byte allocation
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 254K, 13% free 21935K/24976K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 23.800MB for 215890-byte allocation
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 366K, 13% free 22008K/25188K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 23.974MB for 323830-byte allocation
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 564K, 14% free 22129K/25508K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 24.248MB for 485740-byte allocation
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 859K, 15% free 22304K/25984K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 24.650MB for 728606-byte allocation
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 1275K, 16% free 22560K/26696K, paused 40ms, total 40ms
,D/dalvikvm( 4155): GC_CONCURRENT freed 1675K, 15% free 22932K/26696K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4155): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 356K, 15% free 22886K/26696K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 26.087MB for 1639352-byte allocation
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4155): GC_CONCURRENT freed 1592K, 18% free 23448K/28300K, paused 1ms+3ms, total 28ms
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 1436K, 17% free 23539K/28300K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 27.506MB for 2459024-byte allocation
,D/dalvikvm( 4155): GC_CONCURRENT freed 1995K, 21% free 24306K/30704K, paused 3ms+3ms, total 49ms
,D/dalvikvm( 4155): GC_CONCURRENT freed 2455K, 21% free 24465K/30704K, paused 1ms+7ms, total 51ms
,D/dalvikvm( 4155): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 265K, 21% free 24374K/30704K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 29.494MB for 3688532-byte allocation
,D/dalvikvm( 4155): GC_CONCURRENT freed 394K, 19% free 27909K/34308K, paused 2ms+3ms, total 45ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4155): GC_FOR_ALLOC freed 3023K, 26% free 25443K/34308K, paused 23ms, total 24ms
,W/jxcore-log( 4155): Initializing JXcore engine
,W/jxcore-log( 4155): JXcore engine is ready
,D/dalvikvm( 4155): GC_CONCURRENT freed 353K, 19% free 28062K/34308K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4155): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/jxcore-log( 4155): Starting JXcore engine
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.450943 Y: -0.392731 Z: 9.760483 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450943 .y:-0.392731 .z:9.760483
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,W/jxcore-log( 4155): Platform android
W/jxcore-log( 4155): 
,W/jxcore-log( 4155): Process ARCH arm
W/jxcore-log( 4155): 
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.456940 Y: -0.395905 Z: 9.745880 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456940 .y:-0.395905 .z:9.745880
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4155): JXcore Cordova bridge is ready!
I/jxcore-log( 4155): 
,W/jxcore-log( 4155): JXcore engine is started
,I/chromium( 4155): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4155): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4155): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/jxcore  ( 4155): Error!: missing ) after argument list
E/jxcore  ( 4155): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
V/ActivityManager(  961): Finishing activity token=Token{44146890 ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3 f}
I/chromium( 4155): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm(  961): GC_FOR_ALLOC freed 1108K, 50% free 29053K/57152K, paused 90ms, total 90ms
W/PluginManager( 4155): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 100ms. Plugin should use CordovaInterface.getThreadPool().
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300408 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  961): moveHomeStack:
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  961): resumeTopActivityLocked: Resumed ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  961): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/PhoneApp( 1447): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1820): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:3:59
D/UpdateThreadPoolManager( 1820): 2 : This is isUpdating : false
D/WeatherQuickCover( 1820): 2 : quick cover state : opened : 0
D/WeatherService( 1820): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1820): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1820): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1820): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1820): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1820): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:3:59
D/WeatherService( 1820): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1820): 2 : quick cover state : opened : 0
D/Weather.Utils( 1820): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1820): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1820): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1820): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1820): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1820): 2 : This is isUpdating : false
D/WeatherService( 1820): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1820): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1820): 2 : Map key string is -2
I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/lim     ( 1820): 2 : time = 03:03
I/WeatherReflect( 1820): Model Name : LG-D802
W/IInputConnectionWrapper( 4155): showStatusIcon on inactive InputConnection
D/WeatherTheme( 1820): 2 : Different view - status_min_formatted : 02 != 03
D/WeatherTheme( 1820): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1820): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1820): 2 : Fixed theme : optimus
D/WeatherTheme( 1820): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
I/InputMethodManagerService(  961): IME STATUS OFF
D/WeatherQuickCover( 1820): 2 : quick cover state : opened : 0
D/Weather.Utils( 1820): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1820): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1820): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
D/dalvikvm( 1142): GC_FOR_ALLOC freed 6237K, 12% free 69123K/78424K, paused 31ms, total 31ms
D/dalvikvm( 1487): GC_CONCURRENT freed 4832K, 8% free 60838K/65856K, paused 2ms+3ms, total 28ms
D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 25ms
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626640051, nextTick: 59981, mDrawingTime: 0
D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626640052, nextTick: 59981, mDrawingTime: 0
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WeatherService( 1820): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:4:0
D/WeatherService( 1820): 2 : TimeTick Intent And Screen On
D/WeatherService( 1820): 2 : SDK version : 19
D/WeatherQuickCover( 1820): 2 : quick cover state : opened : 0
D/Weather.Utils( 1820): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1820): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1820): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1820): 2 : requestRefreshAppWidget, isUpdateStart : false
D/WifiController(  961): battery changed pluggedType: 2
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/UpdateThreadPoolManager( 1820): 2 : This is isUpdating : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WeatherService( 1820): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1820): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1820): 2 : Map key string is -2
D/lim     ( 1820): 2 : time = 03:04
I/WeatherReflect( 1820): Model Name : LG-D802
D/WeatherTheme( 1820): 2 : Different view - status_min_formatted : 03 != 04
D/WeatherTheme( 1820): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1820): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1820): 2 : Fixed theme : optimus
D/WeatherTheme( 1820): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
D/WeatherService( 1820): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:4:0
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
D/dalvikvm( 1487): GC_FOR_ALLOC freed 5022K, 9% free 62061K/67976K, paused 17ms, total 18ms
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1} time:114151
I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@42885f60 time:114189
D/UsbSettings( 2584): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2584): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2584): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2584): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
E/libEGL  ( 4155): call to OpenGL ES API with no current context (logged once per thread)
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  961): Killing 3382:com.google.android.music:main/u0a107 (adj 15): empty #17
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
F/ActivityManager(  961): Service ServiceRecord{43101b28 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4315d7a8 3382:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  961): Service ServiceRecord{4308ce80 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4315d7a8 3382:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1}
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{43261b88 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1}
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{431ccab0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1}
,I/GAV2    ( 4087): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1551): onDestroy
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  292): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3727): [336] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3727): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.451416 Y: -0.380585 Z: 9.748474 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451416 .y:-0.380585 .z:9.748474
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.458527 Y: -0.378662 Z: 9.787338 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458527 .y:-0.378662 .z:9.787338
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/dalvikvm(  961): Jit: resizing JitTable from 8192 to 16384
,I/PowerManagerService(  961): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  961): [updateScreenState] screen on = false
,D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  961): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9048 usec
,D/qcom_sensors_hal(  961): hal_acquire_resources
,I/qcom_sensors_hal(  961): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  961): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  961): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  961): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  961): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  961): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  961): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.435593 Y: -0.372223 Z: 9.799561 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.435593 .y:-0.372223 .z:9.799561
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.447006 Y: -0.377838 Z: 9.806900 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447006 .y:-0.377838 .z:9.806900
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Sensors (  425): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  961): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  961): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  961): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  961): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  961): proximitySensorChanged  positive = true
I/KnockOnPowerController(  961): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.461899 Y: -0.394897 Z: 9.802490 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461899 .y:-0.394897 .z:9.802490
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.449387 Y: -0.397415 Z: 9.781021 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449387 .y:-0.397415 .z:9.781021
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.440125 Y: -0.386658 Z: 9.782303 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440125 .y:-0.386658 .z:9.782303
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.453125 Y: -0.378876 Z: 9.801849 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453125 .y:-0.378876 .z:9.801849
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  961): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43ad3f58)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  961): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/SurfaceFlinger(  275): Screen released, type=0 flinger=0xb743d450
,I/WindowManager(  961): No lock screen! windowToken=null
D/qdhwcomposer(  275): hwc_blank: Blanking display: 0
,E/SlideAside( 3563): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.452332 Y: -0.370972 Z: 9.787918 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452332 .y:-0.370972 .z:9.787918
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/WifiStateMachine(  961): handleScreenStateChanged: true
,D/WifiServiceExtension(  961): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
,D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=131127
D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): setSuspendOptimizations: 4 false
D/WifiStateMachine(  961): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiOffDelayIfNotUsed(  961): stopMonitoring
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 961
V/SRS_Proc(  278): ParamSet string: screen_state=on
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{432a5f48 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1820): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 3:4:24
,I/SlideAside( 3563): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1820): 2 : This is isUpdating : false
,D/WeatherAncestor( 1820): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 3:4:24
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1820): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1820): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1820): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1820): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.464935 Y: -0.384445 Z: 9.769943 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464935 .y:-0.384445 .z:9.769943
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
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
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.459610 Y: -0.374634 Z: 9.805832 
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.438522 Y: -0.367966 Z: 9.788071 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.459610 .y:-0.374634 .z:9.805832
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
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
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/qdhwcomposer(  275): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  961): Excessive delay in blankDisplay() while turning screen off: 410ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 5669K, 12% free 69104K/78424K, paused 30ms, total 30ms
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626665314, nextTick: 34718, mDrawingTime: 0
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626665339, nextTick: 34694, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/WeatherService( 1820): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:4:25
,D/WeatherService( 1820): 2 : ACTION screen on
,D/WeatherService( 1820): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1820): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:4:25
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  467): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  467): Reading a NULL string not supported here.
E/Parcel  (  467): Reading a NULL string not supported here.
,E/Parcel  (  467): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
,I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
,V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1}
D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
D/qcom_sensors_hal(  961): hal_acquire_resources
D/qcom_sensors_hal(  961): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  961): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  961): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  961): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  961): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  961): Vibrator off
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
,D/KeyguardViewMediator( 1142): handleNotifyScreenOff
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{42c9e9e0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/KeyguardViewManager( 1142): onScreenTurnedOff()
D/WifiStateMachine(  961): handleScreenStateChanged: false
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: InitialState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): setSuspendOptimizations: 4 true
D/WifiStateMachine(  961): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  961): handleMessage: X
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 961
V/SRS_Proc(  278): ParamSet string: screen_state=off
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
,D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
D/WifiController(  961): CMD_SCREEN_OFF 
D/WifiController(  961): shouldWifiStayAwake TRUE
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/VolumeVibrator( 1157): clear
I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1820): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:4:25
,D/WeatherService( 1820): 2 : ACTION screen off
,D/WeatherService( 1820): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:4:25
V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
E/Parcel  (  467): Reading a NULL string not supported here.
E/Parcel  (  467): Reading a NULL string not supported here.
E/Parcel  (  467): Reading a NULL string not supported here.
,E/Parcel  (  467): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1447): Emergency Service
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/NfcService( 1472): NFC-C OFF
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  425): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  292): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626678164026351; DSPS: 5128621; Offset: 1449626521650934310
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626698165860770; DSPS: 5784041; Offset: 1449626521650937675
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626700044, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626700054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626718166712274; DSPS: 6439429; Offset: 1449626521650934687
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626738167592370; DSPS: 7094817; Offset: 1449626521650960290
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626758168482726; DSPS: 7750207; Offset: 1449626521650935119
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626760043, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626760054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626778169754490; DSPS: 8405608; Offset: 1449626521650955662
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626798171868701; DSPS: 9061038; Offset: 1449626521650933643
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626818172754683; DSPS: 9716427; Offset: 1449626521650934615
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626820042, nextTick: 59969, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626820054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626838173608218; DSPS: 10371815; Offset: 1449626521650933658
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626858174154512; DSPS: 11027192; Offset: 1449626521650961153
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x42b7fe08: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3727): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3727): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3727): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3727): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3727): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3727): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LocationManagerService(  961): remove 43491be8
,D/LocationManagerService(  961): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2641): GC_CONCURRENT freed 7643K, 32% free 17009K/24832K, paused 4ms+2ms, total 50ms
,D/dalvikvm( 2641): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/dalvikvm( 2641): GC_CONCURRENT freed 1594K, 30% free 17462K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2641): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2641): GC_CONCURRENT freed 2108K, 30% free 17402K/24832K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2641): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Mlt MonitorService( 2641): parseLastkmsg to dump
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626878178070806; DSPS: 11682681; Offset: 1449626521650940680
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626880031, nextTick: 59991, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626880056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626898178938246; DSPS: 12338069; Offset: 1449626521650953627
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626918179956780; DSPS: 12993463; Offset: 1449626521650934564
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626938180379481; DSPS: 13648836; Offset: 1449626521650960536
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626940044, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449626940053, nextTick: 59980, mDrawingTime: 0,
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626958180820150; DSPS: 14304211; Offset: 1449626521650943442
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626978181717122; DSPS: 14959600; Offset: 1449626521650955404
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449626998182566021; DSPS: 15614988; Offset: 1449626521650949811
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627000034, nextTick: 59985, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627000041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627018183448877; DSPS: 16270377; Offset: 1449626521650947657,
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627038184753089; DSPS: 16925780; Offset: 1449626521650939613
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627058185681102; DSPS: 17581170; Offset: 1449626521650952099
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627060039, nextTick: 59968, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627060054, nextTick: 59979, mDrawingTime: 0
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,W/SocketClient(  271): write error (Broken pipe)
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627078186125261; DSPS: 18236545; Offset: 1449626521650938494
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627098187231399; DSPS: 18891941; Offset: 1449626521650945999
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627118188088475; DSPS: 19547329; Offset: 1449626521650948583
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627120032, nextTick: 59990, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627120048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627138189649925; DSPS: 20202740; Offset: 1449626521650953636
,I/ActivityManager(  961): Killing 2134:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627158190964553; DSPS: 20858143; Offset: 1449626521650956009
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x43b21390: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
E/PlayEventLogger( 3727): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3727): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3727): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3727): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3727): Ignoring header User-Agent because its value was null.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  961): GC_CONCURRENT freed 2079K, 48% free 30000K/57152K, paused 10ms+6ms, total 126ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627178192994494; DSPS: 21513570; Offset: 1449626521650941272
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627180045, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627180054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627198193923495; DSPS: 22168960; Offset: 1449626521650954745
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627218194855781; DSPS: 22824351; Offset: 1449626521650940987
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627238195289783; DSPS: 23479725; Offset: 1449626521650947742
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627240034, nextTick: 59984, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627240042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627258196142276; DSPS: 24135113; Offset: 1449626521650945743
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627278197502424; DSPS: 24790518; Offset: 1449626521650932600
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627298198325645; DSPS: 25445905; Offset: 1449626521650931847
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627300040, nextTick: 59976, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627300049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627318198765222; DSPS: 26101279; Offset: 1449626521650944178
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627338200085526; DSPS: 26756682; Offset: 1449626521650952226
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627358200523643; DSPS: 27412056; Offset: 1449626521650963097
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627360044, nextTick: 59973, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627360052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627378202203741; DSPS: 28067472; Offset: 1449626521650934210
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627398203527587; DSPS: 28722875; Offset: 1449626521650945800
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627418204449507; DSPS: 29378265; Offset: 1449626521650952193
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627420034, nextTick: 59989, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627420041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627438204802051; DSPS: 30033637; Offset: 1449626521650938526
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627458205690480; DSPS: 30689026; Offset: 1449626521650941945
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x43b6f9b8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3727): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3727): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3727): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3727): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3727): Ignoring header User-Agent because its value was null.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627478206549848; DSPS: 31344414; Offset: 1449626521650946821
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627480050, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627480054, nextTick: 59979, mDrawingTime: 0
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1959): Aggregate from 1449625435346 (log), 1449625435346 (data)
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627498207451663; DSPS: 31999804; Offset: 1449626521650933109
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627518208982280; DSPS: 32655214; Offset: 1449626521650937847
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627538210302429; DSPS: 33310617; Offset: 1449626521650945740
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627540043, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627540045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627558210740442; DSPS: 33965991; Offset: 1449626521650956507
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627578212253665; DSPS: 34621401; Offset: 1449626521650943851
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627598213116365; DSPS: 35276789; Offset: 1449626521650952059
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627600031, nextTick: 59986, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627600057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627618213563128; DSPS: 35932164; Offset: 1449626521650941058
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627638214116767; DSPS: 36587542; Offset: 1449626521650945381
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627658215406967; DSPS: 37242944; Offset: 1449626521650953842
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627660039, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627660053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627678215831490; DSPS: 37898318; Offset: 1449626521650951119
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627698216725336; DSPS: 38553707; Offset: 1449626521650959956
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627718217156631; DSPS: 39209082; Offset: 1449626521650933487
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627720036, nextTick: 59982, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627720044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627738217667924; DSPS: 39864458; Offset: 1449626521650956499
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627758218113543; DSPS: 40519833; Offset: 1449626521650944354
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1551): GC_EXPLICIT freed 1339K, 29% free 17813K/24832K, paused 2ms+6ms, total 53ms
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x4309cde8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3727): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3727): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3727): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3727): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3727): Ignoring header User-Agent because its value was null.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627778219018900; DSPS: 41175223; Offset: 1449626521650934184
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627780042, nextTick: 59969, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627780055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627798219456914; DSPS: 41830597; Offset: 1449626521650944952
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627818219904926; DSPS: 42485972; Offset: 1449626521650935200
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627838220361481; DSPS: 43141347; Offset: 1449626521650933991
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627840042, nextTick: 59967, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627840055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627858220800953; DSPS: 43796721; Offset: 1449626521650946217
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627878222385269; DSPS: 44452133; Offset: 1449626521650943619
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627898222825365; DSPS: 45107507; Offset: 1449626521650956469
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627900031, nextTick: 59982, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627900057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627918223744368; DSPS: 45762897; Offset: 1449626521650959945
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627938224617537; DSPS: 46418286; Offset: 1449626521650948104
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627958225050499; DSPS: 47073660; Offset: 1449626521650953820
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627960053, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449627960055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627978225511741; DSPS: 47729035; Offset: 1449626521650957298
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449627998226400535; DSPS: 48384425; Offset: 1449626521650930565
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628018226816882; DSPS: 49039798; Offset: 1449626521650950183
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628020047, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628020059, nextTick: 59967, mDrawingTime: 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628038227303020; DSPS: 49695174; Offset: 1449626521650948040
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628058227772074; DSPS: 50350549; Offset: 1449626521650959330
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x44ea6b00: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3727): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3727): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3727): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3727): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3727): Ignoring header User-Agent because its value was null.
D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628078228213369; DSPS: 51005924; Offset: 1449626521650942862
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628080055, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628080056, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628098228647059; DSPS: 51661298; Offset: 1449626521650949306
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628118229774552; DSPS: 52316695; Offset: 1449626521650947648
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628138230209440; DSPS: 52972069; Offset: 1449626521650955290
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628140041, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628140050, nextTick: 59978, mDrawingTime: 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628158231058651; DSPS: 53627457; Offset: 1449626521650950009
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628178231509634; DSPS: 54282832; Offset: 1449626521650943228
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628198232623740; DSPS: 54938229; Offset: 1449626521650928184
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628200053, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628200055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628218233045399; DSPS: 55593602; Offset: 1449626521650953114
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628238233496434; DSPS: 56248977; Offset: 1449626521650946386
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628258234020280; DSPS: 56904354; Offset: 1449626521650951433
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628260038, nextTick: 59973, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628260053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628278234452250; DSPS: 57559728; Offset: 1449626521650956157
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628298235594223; DSPS: 58215126; Offset: 1449626521650938462
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628318236116142; DSPS: 58870503; Offset: 1449626521650941582
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628320046, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628320050, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628338241857750; DSPS: 59526051; Offset: 1449626521650945885
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/ProcessStatsService(  961): Prepared write state in 16ms
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,I/ProcessStatsService(  961): Pruning old procstats: /data/system/procstats/state-2015-12-08-10-13-49.bin
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628358242287221; DSPS: 60181425; Offset: 1449626521650948110
,I/GLSUser ( 1551): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1551): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1551): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1551): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1551): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1551): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x43468568: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1551): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1551): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1551): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1551): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1551): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1551): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3727): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3727): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3727): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3727): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3727): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3727): Ignoring header User-Agent because its value was null.
,D/libc    (  271): _dns_getaddrinfo: iptype =0
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  961): GC_CONCURRENT freed 2847K, 47% free 30506K/57016K, paused 15ms+4ms, total 118ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628378242737369; DSPS: 60836800; Offset: 1449626521650940494
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
I/ActivityManager(  961): Killing 3799:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1814s
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628380045, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628380055, nextTick: 59978, mDrawingTime: 0
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628398243279862; DSPS: 61492178; Offset: 1449626521650933671
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628418243735948; DSPS: 62147552; Offset: 1449626521650962511
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1449628438244747242; DSPS: 62802946; Offset: 1449626521650936207
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,I/ActivityManager(  961): Killing 3681:com.android.gallery3d/u0a27 (adj 15): empty for 1804s
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
I/ActivityManager(  961): Killing 3666:com.android.contacts/u0a21 (adj 15): empty for 1805s
,I/ActivityManager(  961): Killing 4055:com.lge.bnr/1000 (adj 15): empty for 1805s
,I/ActivityManager(  961): Killing 3648:com.lge.appbox.client/u0a11 (adj 15): empty for 1805s
,I/ActivityManager(  961): Killing 4027:com.google.android.partnersetup/u0a9 (adj 15): empty for 1805s
,I/ActivityManager(  961): Killing 3995:com.android.defcontainer/u0a4 (adj 15): empty for 1805s
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628440078, nextTick: 59952, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449628440079, nextTick: 59953, mDrawingTime: 0
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bf5448 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,TIME-OUT KILL (timeout was 1800000ms)
```
