#### Test 50650278b1aec71_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
E/DataScheduler( 1945): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1945): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1945): fetch service done; releasing wakelock
I/ConfigFetchService( 1945): stopping self
,W/GAV2    ( 3995): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  959): Killing 3343:com.google.android.music:main/u0a107 (adj 15): empty #17
F/ActivityManager(  959): Service ServiceRecord{43218068 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4322d560 3343:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  959): Service ServiceRecord{432177e0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4322d560 3343:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ccb18 stackId=1, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  959): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
D/dalvikvm( 1945): GC_CONCURRENT freed 1562K, 26% free 18430K/24832K, paused 3ms+2ms, total 58ms
D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595680045, nextTick: 59985, mDrawingTime: 1
D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595680048, nextTick: 59984, mDrawingTime: 0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4040): 
D/AndroidRuntime( 4040): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4040): CheckJNI is OFF
D/dalvikvm( 4040): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4040): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4040): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4040): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4040): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4040): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1945): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
E/memtrack( 4040): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4040): failed to load memtrack module: -2
D/Icing   ( 1945): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1945): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/AndroidRuntime( 4040): Calling main entry com.android.commands.am.Am
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  959): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  959): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4040
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ccb18 stackId=1, 2 tasks}
V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (336 us)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  959): resumeTopActivityLocked: Pausing null
V/ActivityManager(  959): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  959): setFocusedStack: mFocusedStack=ActivityStack{432ccb18 stackId=1, 2 tasks}
I/ActivityManager(  959): startService SlideAside
W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/UsbSettingsControl( 2529): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2529): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  959): allPausedActivitiesComplete: r=ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/AndroidRuntime( 4040): Shutting down VM
D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/SlideAside( 3516): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/dalvikvm( 4040): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 4ms
D/WifiController(  959): battery changed pluggedType: 2
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ccb18 stackId=1, 2 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Restarting ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  959): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4071 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3516): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3516): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/dalvikvm(  269): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
V/ActivityManager(  959): Moving to RESUMED: ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4071): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4071): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4071): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 17ms
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
V/WebViewChromium( 4071): Binding Chromium to the background looper Looper (main, tid 1) {428341e8}
I/chromium( 4071): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4071): Initializing chromium process, renderers=0
W/chromium( 4071): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4071): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4071): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4071): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4071): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4071): Remote Branch: 
I/Adreno-EGL( 4071): Local Patches: 
I/Adreno-EGL( 4071): Reconstruct Branch: 
I/dalvikvm( 4071): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4071): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4071): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4071): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4071): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4071): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4071): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4071): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4071): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4071): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4071): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4071): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4071): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4071): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4071): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4071): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4071): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4071): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4071): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4071): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4071): Enabling debug mode 0
W/AwContents( 4071): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  959): IME STATUS OFF
W/AwContents( 4071): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  959): Displayed com.test.thalitest/.MainActivity: +474ms
I/ActivityManager( 4071): Timeline: Activity_idle id: android.os.BinderProxy@428358c8 time:111418
D/JsMessageQueue( 4071): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  959): Timeline: Activity_windows_visible id: ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3} time:111702
D/ActivityManager(  959): no-history finish of ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  959): Finishing activity token=Token{4322c8d0 ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  959): Moving to FINISHING: ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3}
D/UsbSettings( 2529): [AUTORUN] onStop()
V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  959): Moving to STOPPED: ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4071): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428399a8
D/dalvikvm( 4071): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428399a8
D/jxcore_app_log( 4071): JniHelper::setJavaVM(0x416f6838), pthread_self() = 1631922184
D/JX-Cordova( 4071): jxcore cordova android initializing
I/dalvikvm( 4071): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4071): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0045
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4071): GC_CONCURRENT freed 2770K, 13% free 21850K/24832K, paused 2ms+1ms, total 51ms
,D/dalvikvm( 4071): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 130K, 13% free 21832K/24832K, paused 28ms, total 28ms
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 118K, 12% free 21863K/24832K, paused 28ms, total 28ms
I/dalvikvm-heap( 4071): Grow heap (frag case) to 23.616MB for 95956-byte allocation
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 191K, 13% free 21887K/24928K, paused 26ms, total 26ms
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 253K, 13% free 21934K/24928K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4071): Grow heap (frag case) to 23.800MB for 215890-byte allocation
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.460770 Y: -0.408859 Z: 9.747314 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460770 .y:-0.408859 .z:9.747314
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 366K, 13% free 22007K/25140K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4071): Grow heap (frag case) to 23.974MB for 323830-byte allocation
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 564K, 14% free 22129K/25460K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4071): Grow heap (frag case) to 24.247MB for 485740-byte allocation
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.461899 Y: -0.382172 Z: 9.758545 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461899 .y:-0.382172 .z:9.758545
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 859K, 15% free 22304K/25936K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4071): Grow heap (frag case) to 24.650MB for 728606-byte allocation
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 1278K, 16% free 22560K/26648K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4071): Grow heap (frag case) to 25.247MB for 1092904-byte allocation
,D/dalvikvm( 4071): GC_CONCURRENT freed 1905K, 17% free 23014K/27716K, paused 1ms+5ms, total 49ms
,D/dalvikvm( 4071): GC_CONCURRENT freed 1744K, 16% free 23454K/27716K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 4071): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 4071): GC_FOR_ALLOC freed 1413K, 16% free 23538K/27716K, paused 24ms, total 24ms
I/dalvikvm-heap( 4071): Grow heap (frag case) to 27.504MB for 2459024-byte allocation
D/dalvikvm( 4071): GC_CONCURRENT freed 335K, 15% free 25858K/30120K, paused 2ms+4ms, total 39ms
D/dalvikvm( 4071): GC_FOR_ALLOC freed 4263K, 19% free 24496K/30120K, paused 27ms, total 34ms
I/dalvikvm-heap( 4071): Grow heap (frag case) to 29.613MB for 3688532-byte allocation
D/dalvikvm( 4071): GC_CONCURRENT freed 2827K, 25% free 25404K/33724K, paused 2ms+2ms, total 30ms
D/dalvikvm( 4071): GC_FOR_ALLOC freed 695K, 25% free 25461K/33724K, paused 23ms, total 23ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
W/jxcore-log( 4071): Initializing JXcore engine
W/jxcore-log( 4071): JXcore engine is ready
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4071): GC_CONCURRENT freed 375K, 17% free 28062K/33724K, paused 2ms+1ms, total 27ms
D/dalvikvm( 4071): WAIT_FOR_CONCURRENT_GC blocked 24ms
W/jxcore-log( 4071): Starting JXcore engine
W/jxcore-log( 4071): Platform android
W/jxcore-log( 4071): 
W/jxcore-log( 4071): Process ARCH arm
W/jxcore-log( 4071): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4071): JXcore Cordova bridge is ready!
I/jxcore-log( 4071): 
,W/jxcore-log( 4071): JXcore engine is started
,I/chromium( 4071): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4071): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4071): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 4071): Error!: missing ) after argument list
E/jxcore  ( 4071): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,V/ActivityManager(  959): Finishing activity token=Token{43e518f0 ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
,V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3 f}
,I/chromium( 4071): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  959): GC_FOR_ALLOC freed 22268K, 50% free 28783K/56680K, paused 111ms, total 111ms
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ccb18 stackId=1, 2 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  959): moveHomeStack:
,W/PluginManager( 4071): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 129ms. Plugin should use CordovaInterface.getThreadPool().
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
V/ActivityManager(  959): Moving to RESUMED: ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  959): resumeTopActivityLocked: Resumed ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  959): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1491): [Launcher.java:4947:onStart()]onStart
I/[LGHome]EVENT( 1491): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1491): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1453): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1491): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1491): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1846): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:28:4
D/UpdateThreadPoolManager( 1846): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1846): 2 : quick cover state : opened : 0
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1846): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1846): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1846): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,I/[LGHome]EVENT( 1491): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/WeatherService( 1846): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1846): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:28:4
D/WeatherService( 1846): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1846): 2 : quick cover state : opened : 0
D/Weather.Utils( 1846): 2 : Utils getTopActivity com.lge.launcher2 / true
W/IInputConnectionWrapper( 4071): showStatusIcon on inactive InputConnection
D/WeatherService( 1846): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1846): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1846): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1846): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/InputMethodManagerService(  959): IME STATUS OFF
D/UpdateThreadPoolManager( 1846): 2 : This is isUpdating : false
D/WeatherService( 1846): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1846): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1846): 2 : Map key string is -2
D/lim     ( 1846): 2 : time = 18:28
I/WeatherReflect( 1846): Model Name : LG-D802
D/WeatherTheme( 1846): 2 : Different view - status_min_formatted : 26 != 28
D/WeatherTheme( 1846): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1846): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1846): 2 : Fixed theme : optimus
,D/WeatherTheme( 1846): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1846): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1846): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  959): Killing 2130:android.process.media/u0a23 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 6048K, 12% free 69317K/78244K, paused 22ms, total 22ms
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1491): GC_CONCURRENT freed 5375K, 9% free 61087K/66644K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 1491): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/GAV2    ( 3995): Thread[GAThread,5,main]: No campaign data found.
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager( 1491): Timeline: Activity_idle id: android.os.BinderProxy@4282f060 time:115161
,D/UsbSettings( 2529): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2529): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2529): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2529): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  959): Moving to DESTROYING: ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{42c4ac38 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/ActivityManager(  959): Moving to FINISHING: ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3 f}
,I/ActivityManager(  959): Timeline: Activity_windows_visible id: ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1} time:115220
I/ActivityManager(  959): Killing 3763:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
V/ActivityManager(  959): Moving to DESTROYING: ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4071): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{43c1aa50 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1}
,I/ConfigService( 1550): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1491): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3688): [336] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3688): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.449692 Y: -0.399399 Z: 9.748093 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449692 .y:-0.399399 .z:9.748093
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.455643 Y: -0.394791 Z: 9.754822 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455643 .y:-0.394791 .z:9.754822
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,I/dalvikvm(  959): Jit: resizing JitTable from 8192 to 16384
,I/PowerManagerService(  959): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  959): [updateScreenState] screen on = false
,D/KnockOnPowerController(  959): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  959): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  959): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/KnockOnPowerController(  959): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  959): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  959): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  959): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8608 usec
,D/qcom_sensors_hal(  959): hal_acquire_resources
,I/qcom_sensors_hal(  959): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  959): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  959): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  959): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  959): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  959): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  959): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  959): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.454712 Y: -0.398499 Z: 9.774063 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454712 .y:-0.398499 .z:9.774063
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.457169 Y: -0.397156 Z: 9.760742 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457169 .y:-0.397156 .z:9.760742
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,I/Sensors (  633): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  959): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  959): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  959): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  959): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  959): proximitySensorChanged  positive = true
I/KnockOnPowerController(  959): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.455093 Y: -0.385986 Z: 9.754227 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455093 .y:-0.385986 .z:9.754227
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.467560 Y: -0.380417 Z: 9.759277 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467560 .y:-0.380417 .z:9.759277
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.473663 Y: -0.379303 Z: 9.760010 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473663 .y:-0.379303 .z:9.760010
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.448135 Y: -0.385422 Z: 9.778152 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448135 .y:-0.385422 .z:9.778152
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  959): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43dfef80)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  959): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
I/WindowManager(  959): No lock screen! windowToken=null
,D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb8ddb450
,D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,E/SlideAside( 3516): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1478): setPowerMode; state=4
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.467743 Y: -0.408340 Z: 9.765839 
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.455551 Y: -0.397247 Z: 9.744736 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.467743 .y:-0.408340 .z:9.765839
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  959): handleScreenStateChanged: true
,D/WifiStateMachine(  959): handleMessage: E msg.what=131154
D/WifiStateMachine(  959): processMsg: InitialState
D/WifiStateMachine(  959): processMsg: DefaultState
,D/WifiStateMachine(  959): handleMessage: X
D/WifiStateMachine(  959): handleMessage: E msg.what=131127
,D/WifiStateMachine(  959): processMsg: InitialState
D/WifiStateMachine(  959): processMsg: DefaultState
,D/WifiStateMachine(  959): handleMessage: X
D/WifiStateMachine(  959): handleMessage: E msg.what=131158
D/WifiStateMachine(  959): processMsg: InitialState
,D/WifiStateMachine(  959): processMsg: DefaultState
D/WifiStateMachine(  959): setSuspendOptimizations: 4 false
D/WifiStateMachine(  959): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  959): handleMessage: X
,D/WifiServiceExtension(  959): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  959): stopMonitoring
,E/AudioSystem(  959): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 959
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
,D/WeatherAncestor( 1846): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:28:27
,I/SlideAside( 3516): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{432624f8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/UpdateThreadPoolManager( 1846): 2 : This is isUpdating : false
,D/WeatherAncestor( 1846): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:28:27
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1846): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1846): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
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
,D/qdlights( 1156): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1156): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1156): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 237, B = 237
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  959): Excessive delay in blankDisplay() while turning screen off: 410ms
,D/qdlights( 1156): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1156): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.466248 Y: -0.382690 Z: 9.777527 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466248 .y:-0.382690 .z:9.777527
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 5582K, 13% free 68781K/78244K, paused 28ms, total 29ms
D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595708054, nextTick: 31979, mDrawingTime: 0
D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595708079, nextTick: 31954, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1478): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.473312 Y: -0.378937 Z: 9.775345 
,D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473312 .y:-0.378937 .z:9.775345
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/WeatherService( 1846): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:28:28
D/WeatherService( 1846): 2 : ACTION screen on
,D/WeatherService( 1846): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1846): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:28:28
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  959): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  665): Reading a NULL string not supported here.
E/Parcel  (  665): Reading a NULL string not supported here.
E/Parcel  (  665): Reading a NULL string not supported here.
,E/Parcel  (  665): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/GsmSST  ( 1453): Emergency Service
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1453): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1453): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1453): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  959): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  959): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  959): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
,I/[LGHome]EVENT( 1491): [Launcher.java:894:onPause()]onPause
D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
D/qcom_sensors_hal(  959): hal_acquire_resources
D/qcom_sensors_hal(  959): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  959): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=1000
V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1}
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  959): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  959): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  959): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,I/LGImmersionVibrator(  959): Vibrator off
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/[LGHome]EVENT( 1491): [Launcher.java:4955:onStop()]onStop
,D/WifiStateMachine(  959): handleScreenStateChanged: false
,D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
D/WifiStateMachine(  959): handleMessage: E msg.what=131154
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
D/WifiStateMachine(  959): processMsg: InitialState
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,V/ActivityManager(  959): Moving to STOPPED: ActivityRecord{42b5f698 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiStateMachine(  959): processMsg: DefaultState
D/WifiStateMachine(  959): handleMessage: X
D/WifiStateMachine(  959): handleMessage: E msg.what=131158
D/WifiStateMachine(  959): processMsg: InitialState
D/WifiStateMachine(  959): processMsg: DefaultState
D/WifiStateMachine(  959): setSuspendOptimizations: 4 true
D/WifiStateMachine(  959): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  959): handleMessage: X
,E/AudioSystem(  959): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 959
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WifiController(  959): CMD_SCREEN_OFF 
D/WifiController(  959): shouldWifiStayAwake TRUE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
D/VolumeVibrator( 1156): clear
,D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
,D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1478): setPowerMode; state=2
D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,I/[LGHome]EVENT( 1491): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1846): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:28:28
D/WeatherService( 1846): 2 : ACTION screen off
,D/WeatherService( 1846): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:28:28
D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,V/TelephonyAutoProfiling(  959): [getValue] FEATURE key : trf_based_vzw, value : null
,E/Parcel  (  665): Reading a NULL string not supported here.
E/Parcel  (  665): Reading a NULL string not supported here.
E/Parcel  (  665): Reading a NULL string not supported here.
E/Parcel  (  665): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1453): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1453): Emergency Service
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1453): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_roaming_state, value : null
D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1453): Action intent recieved:android.intent.action.SCREEN_OFF
D/BrcmNfcJni( 1478): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1478): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/NfcService( 1478): NFC-C OFF
,D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1466): [TangibleIO] LCD is off. Remove tangible if exist.
,D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
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
,D/qdlights( 1156): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1156): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  633): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  959): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
,D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595721099505778; DSPS: 5115731; Offset: 1449595564979785320
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595740044, nextTick: 59971, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595740056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595741099953948; DSPS: 5771106; Offset: 1449595564979775726
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  959): handleInetConditionChange: no active default network - ignore
W/SocketClient(  264): write error (Broken pipe)
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595761102548627; DSPS: 6426551; Offset: 1449595564979776411
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595781105466641; DSPS: 7082006; Offset: 1449595564979795255
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595800042, nextTick: 59967, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595800057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595801106392207; DSPS: 7737397; Offset: 1449595564979774776
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
D/WifiController(  959): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595821106828501; DSPS: 8392771; Offset: 1449595564979783824
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595841108224898; DSPS: 9048177; Offset: 1449595564979776412
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595860033, nextTick: 59980, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595860052, nextTick: 59972, mDrawingTime: 3
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595861109777913; DSPS: 9703588; Offset: 1449595564979773031
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595881110632592; DSPS: 10358975; Offset: 1449595564979803735
,I/LocationManagerService(  959): remove 42b05f48
,D/LocationManagerService(  959): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  959): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  959): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  959): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  959): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595901111625241; DSPS: 11014368; Offset: 1449595564979789304
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  959): updateLightListLocked :r=null, action=2
,W/GLSActivity( 1550): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1550): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1550): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1550): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1550): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3688): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3688): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3688): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3688): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 3688): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3688): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595920025, nextTick: 59991, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595920048, nextTick: 59982, mDrawingTime: 2
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  959): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595921114472369; DSPS: 11669821; Offset: 1449595564979798297
,D/dalvikvm(  959): GC_CONCURRENT freed 1826K, 48% free 29914K/56680K, paused 2ms+5ms, total 94ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595941115804236; DSPS: 12325225; Offset: 1449595564979787391
,D/dalvikvm( 2609): GC_CONCURRENT freed 7628K, 32% free 17024K/24832K, paused 4ms+2ms, total 51ms
,D/dalvikvm( 2609): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 2609): GC_FOR_ALLOC freed 1598K, 32% free 17128K/24832K, paused 21ms, total 21ms
,I/Mlt MonitorService( 2609): parseLastkmsg to dump
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595961117118969; DSPS: 12980628; Offset: 1449595564979789868
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595980032, nextTick: 59991, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449595980055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449595981118465783; DSPS: 13636032; Offset: 1449595564979793908
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596001119767077; DSPS: 14291435; Offset: 1449595564979782947
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596021121044726; DSPS: 14946837; Offset: 1449595564979778857
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596040041, nextTick: 59967, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596040056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596041122364250; DSPS: 15602240; Offset: 1449595564979786125
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  959): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596061124259035; DSPS: 16257662; Offset: 1449595564979788821
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596081125559548; DSPS: 16913065; Offset: 1449595564979777078
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596100023, nextTick: 60001, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596100047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596101126909019; DSPS: 17568469; Offset: 1449595564979783775
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596121128427293; DSPS: 18223879; Offset: 1449595564979776170
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596141129964629; DSPS: 18879289; Offset: 1449595564979787628
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596160046, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596160056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596161131315089; DSPS: 19534693; Offset: 1449595564979795314
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596181132675499; DSPS: 20190098; Offset: 1449595564979782433
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596201134566533; DSPS: 20845520; Offset: 1449595564979781377
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  959): updateLightListLocked :r=NotificationRecord(0x44d67cc8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  959): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1550): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1550): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1550): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1550): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1550): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3688): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3688): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3688): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3688): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3688): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596220051, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596220055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596221135975953; DSPS: 21500926; Offset: 1449595564979786989
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596241137519591; DSPS: 22156337; Offset: 1449595564979774230
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596261139113853; DSPS: 22811749; Offset: 1449595564979781578
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596280052, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596280056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596281140707961; DSPS: 23467161; Offset: 1449595564979788772
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596301142009724; DSPS: 24122564; Offset: 1449595564979778279
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596321143923206; DSPS: 24777986; Offset: 1449595564979799671
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596340030, nextTick: 59997, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596340058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596341145292990; DSPS: 25433391; Offset: 1449595564979796164
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596361146605378; DSPS: 26088794; Offset: 1449595564979796296
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596381147873704; DSPS: 26744196; Offset: 1449595564979782884
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596400039, nextTick: 59967, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596400057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596401149273540; DSPS: 27399602; Offset: 1449595564979778912
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596421150805511; DSPS: 28055012; Offset: 1449595564979785004
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596441152082691; DSPS: 28710414; Offset: 1449595564979780445
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596460024, nextTick: 60001, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596460052, nextTick: 59972, mDrawingTime: 3
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596461153555965; DSPS: 29365822; Offset: 1449595564979788876
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  959): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1945): Aggregate from 1449594680121 (log), 1449594666115 (data)
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596481154898405; DSPS: 30021226; Offset: 1449595564979788542
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596501156189804; DSPS: 30676628; Offset: 1449595564979798203
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  959): updateLightListLocked :r=NotificationRecord(0x431c5f90: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1550): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1550): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1550): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1550): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1550): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  959): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3688): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3688): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3688): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3688): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3688): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596520039, nextTick: 59973, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596520052, nextTick: 59975, mDrawingTime: 3
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596521157586046; DSPS: 31332034; Offset: 1449595564979790636
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596541158943069; DSPS: 31987439; Offset: 1449595564979774368
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596561160217541; DSPS: 32642840; Offset: 1449595564979797620
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596580051, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596580056, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596581161557950; DSPS: 33298244; Offset: 1449595564979795255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  959): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1466): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1466): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1466): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1466): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596601162936641; DSPS: 33953649; Offset: 1449595564979800655
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596621164855696; DSPS: 34609072; Offset: 1449595564979797103
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596640055, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596640056, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596641166219750; DSPS: 35264477; Offset: 1449595564979787866
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596661167527451; DSPS: 35919880; Offset: 1449595564979783311
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596681169088120; DSPS: 36575291; Offset: 1449595564979787583
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596700046, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596700048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596701170695040; DSPS: 37230704; Offset: 1449595564979777072
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596721171991855; DSPS: 37886106; Offset: 1449595564979792148
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596741173625754; DSPS: 38541520; Offset: 1449595564979778098
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596760036, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596760042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596761174978975; DSPS: 39196924; Offset: 1449595564979788546
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596781176298551; DSPS: 39852327; Offset: 1449595564979795866
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596801177579116; DSPS: 40507729; Offset: 1449595564979794693
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  959): updateLightListLocked :r=NotificationRecord(0x4323c220: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  959): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1550): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1550): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1550): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1550): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1550): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3688): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3688): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3688): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3688): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3688): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596820041, nextTick: 59974, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596820054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596821179020359; DSPS: 41163136; Offset: 1449595564979801609
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596841180564466; DSPS: 41818547; Offset: 1449595564979789320
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596861182086489; DSPS: 42473957; Offset: 1449595564979785464
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596880031, nextTick: 59987, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596880040, nextTick: 59991, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596881183552993; DSPS: 43129365; Offset: 1449595564979787124
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596901184860641; DSPS: 43784768; Offset: 1449595564979782516
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596921186160060; DSPS: 44440170; Offset: 1449595564979800197
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596940035, nextTick: 59983, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449596940044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596941187742865; DSPS: 45095582; Offset: 1449595564979796088
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596961189080357; DSPS: 45750986; Offset: 1449595564979790807
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449596981190356392; DSPS: 46406388; Offset: 1449595564979785103
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597000044, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597000056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597001192134977; DSPS: 47061806; Offset: 1449595564979793669
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597021194052106; DSPS: 47717229; Offset: 1449595564979788190
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597041195335380; DSPS: 48372631; Offset: 1449595564979789726
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597060044, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597060057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597061196675424; DSPS: 49028035; Offset: 1449595564979786997
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597081198236301; DSPS: 49683446; Offset: 1449595564979791477
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597101199787544; DSPS: 50338857; Offset: 1449595564979786324
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  959): updateLightListLocked :r=NotificationRecord(0x44e5c088: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1550): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1550): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1550): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1550): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1550): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  959): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3688): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3688): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3688): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3688): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3688): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597120050, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597120056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597121201351702; DSPS: 50994268; Offset: 1449595564979794085
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597141202654403; DSPS: 51649671; Offset: 1449595564979784530
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597161204569917; DSPS: 52305094; Offset: 1449595564979777437
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597180051, nextTick: 59969, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597180058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597181206170534; DSPS: 52960506; Offset: 1449595564979791140
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597201207953027; DSPS: 53615925; Offset: 1449595564979773096
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597221209429269; DSPS: 54271333; Offset: 1449595564979784494
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597240053, nextTick: 59971, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597240058, nextTick: 59974, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597241210840302; DSPS: 54926739; Offset: 1449595564979791719
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597261212134878; DSPS: 55582142; Offset: 1449595564979774039
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597281214227059; DSPS: 56237570; Offset: 1449595564979791024
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597300043, nextTick: 59968, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597300056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597301215646373; DSPS: 56892977; Offset: 1449595564979776012,
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597321216942512; DSPS: 57548379; Offset: 1449595564979790413
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597341218217087; DSPS: 58203781; Offset: 1449595564979783250
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597360036, nextTick: 59985, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597360042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597361219570205; DSPS: 58859185; Offset: 1449595564979793594
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  959): GC_CONCURRENT freed 3145K, 47% free 30037K/56628K, paused 6ms+10ms, total 147ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597381220547176; DSPS: 59514577; Offset: 1449595564979794003
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/ProcessStatsService(  959): Prepared write state in 21ms
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  959): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocationManagerService(  959): getAllProviders()=[passive, gps, network]
D/QcConnectivityService(  959): handleInetConditionChange: no active default network - ignore
,I/ProcessStatsService(  959): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-12-57.bin
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1550): GC_EXPLICIT freed 1613K, 29% free 17810K/24832K, paused 1ms+3ms, total 23ms
,I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597401221437116; DSPS: 60169966; Offset: 1449595564979798933
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  959): updateLightListLocked :r=NotificationRecord(0x4486dbc8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1550): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1550): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1550): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1550): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1550): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1550): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  959): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3688): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3688): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3688): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3688): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3688): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3688): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
I/ActivityManager(  959): Killing 3199:com.android.mms/u0a35 (adj 15): empty for 1811s
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597420033, nextTick: 59979, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597420046, nextTick: 59986, mDrawingTime: 0
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/CountryDetector(  959): No listener is left
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597421223024817; DSPS: 60825378; Offset: 1449595564979799720
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597441224966945; DSPS: 61480802; Offset: 1449595564979788723
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597461226250948; DSPS: 62136204; Offset: 1449595564979790988
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
I/ActivityManager(  959): Killing 3649:com.android.gallery3d/u0a27 (adj 15): empty for 1800s
I/ActivityManager(  959): Killing 3635:com.android.contacts/u0a21 (adj 15): empty for 1801s
I/ActivityManager(  959): Killing 3965:com.lge.bnr/1000 (adj 15): empty for 1801s
I/ActivityManager(  959): Killing 3614:com.lge.appbox.client/u0a11 (adj 15): empty for 1801s
I/ActivityManager(  959): Killing 3936:com.google.android.partnersetup/u0a9 (adj 15): empty for 1801s
I/ActivityManager(  959): Killing 3881:com.android.defcontainer/u0a4 (adj 15): empty for 1801s
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597480080, nextTick: 59947, mDrawingTime: 5
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1449597480084, nextTick: 59949, mDrawingTime: 0
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb5700 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  959): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  959): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  959): hal_ts_offset_is: Apps: 1449597481227593232; DSPS: 62791608; Offset: 1449595564979790498
,TIME-OUT KILL (timeout was 1800000ms)
```
