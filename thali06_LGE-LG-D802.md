#### Test 56672827039a409_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1854): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1854): launchTask
W/dalvikvm( 1854): VFY: unable to find class referenced in signature (Landroid/net/Network;)
--------- beginning of /dev/log/system
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
V/ConfigFetchTask( 1854): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1W--v35K7q4IsPtfZd0h-wgoyLN9ummpkHhJ9myYH-eG-gBUh_gRAhFKeb4ZS0s0ZQ5qHFljtOCcXUQZLnFELQEejjM3TZIKAEOkl_Y8x8oORfLbj8nOjJvSf27r8kO8PPxird2Go2Wtqg04A1hkFQuerExU2bNK8fGApPYlp2YESQgP14znaKooRQwltGI_nRooRCq
I/GoogleURLConnFactory( 1854): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/Vision  ( 1854): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1854): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1854): No vision deps
D/libc    (  272): _dns_getaddrinfo: iptype =1
D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1854): CP2 sync disabled
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
I/dalvikvm( 1854): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1854): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1854): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
W/GAV2    ( 4557): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
W/BaseAppContext( 1854): Using Auth Proxy for data requests.
I/ActivityManager(  967): Killing 4013:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{430c2758 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2}
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 1519): GC_EXPLICIT freed 1162K, 29% free 17820K/24832K, paused 1ms+3ms, total 30ms
D/AndroidRuntime( 4607): 
D/AndroidRuntime( 4607): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4607): CheckJNI is OFF
D/dalvikvm( 4607): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4607): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4607): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4607): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4607): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 1854): GC_CONCURRENT freed 1605K, 22% free 19428K/24832K, paused 4ms+3ms, total 46ms
D/dalvikvm( 1854): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/dalvikvm( 1854): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 4607): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/ConfigFetchService( 1854): fetch service done; releasing wakelock
I/ConfigFetchService( 1854): stopping self
D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1854): Module APK com.google.android.play.games already loaded
I/Icing   ( 1854): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
E/memtrack( 4607): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4607): failed to load memtrack module: -2
D/Icing   ( 1854): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1854): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4607): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4607
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{430c2758 stackId=1, 2 tasks}
D/PermissionCache(  275): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (298 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  967): GC_FOR_ALLOC freed 24410K, 54% free 27997K/59844K, paused 111ms, total 111ms
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  967): startService SlideAside
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{430c2758 stackId=1, 2 tasks}
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/AndroidRuntime( 4607): Shutting down VM
D/UsbSettingsControl( 2621): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2621): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4607): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3994): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{430c2758 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3994): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4624 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/SlideAside( 3994): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4624): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4624): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4624): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
D/HeadsetStateMachine( 1226): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
V/WebViewChromium( 4624): Binding Chromium to the background looper Looper (main, tid 1) {4289d2f8}
I/chromium( 4624): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4624): Initializing chromium process, renderers=0
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
W/chromium( 4624): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4624): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4624): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4624): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4624): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4624): Remote Branch: 
I/Adreno-EGL( 4624): Local Patches: 
I/Adreno-EGL( 4624): Reconstruct Branch: 
I/dalvikvm( 4624): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4624): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4624): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4624): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4624): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4624): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4624): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4624): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4624): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4624): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4624): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4624): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4624): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4624): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4624): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4624): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4624): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4624): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4624): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4624): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4624): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4624): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4624): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4624): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4624): Enabling debug mode 0
W/AwContents( 4624): nativeOnDraw failed; clearing to background color.
W/AwContents( 4624): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  967): IME STATUS OFF
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +335ms
I/ActivityManager( 4624): Timeline: Activity_idle id: android.os.BinderProxy@4289e9d8 time:111901
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
D/JsMessageQueue( 4624): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4624): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a2ab8
D/dalvikvm( 4624): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a2ab8
D/jxcore_app_log( 4624): JniHelper::setJavaVM(0x41761838), pthread_self() = 1639881320
I/chromium( 4624): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2074): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3} time:112318
D/ActivityManager(  967): no-history finish of ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{428cca30 ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3}
D/UsbSettings( 2621): [AUTORUN] onStop()
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/chromium( 4624): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4624): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/dalvikvm( 4624): GC_CONCURRENT freed 2638K, 12% free 22014K/24832K, paused 2ms+1ms, total 34ms
,D/dalvikvm( 4624): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4624): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 410K, 10% free 22358K/24832K, paused 23ms, total 23ms
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 85K, 10% free 22382K/24832K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 24.092MB for 63974-byte allocation
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457626 Y: -0.409927 Z: 9.786438 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457626 .y:-0.409927 .z:9.786438
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 143K, 11% free 22385K/24896K, paused 24ms, total 24ms
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/dalvikvm-heap( 4624): Grow heap (frag case) to 24.125MB for 95956-byte allocation
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.458755 Y: -0.418823 Z: 9.779221 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458755 .y:-0.418823 .z:9.779221
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 179K, 11% free 22419K/24992K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 24.205MB for 143930-byte allocation
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 254K, 11% free 22467K/25136K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 24.320MB for 215890-byte allocation
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 366K, 12% free 22541K/25348K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 24.495MB for 323830-byte allocation
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 566K, 12% free 22661K/25668K, paused 23ms, total 24ms
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 861K, 12% free 22837K/25668K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 25.170MB for 728606-byte allocation
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 1278K, 13% free 23093K/26380K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 25.767MB for 1092904-byte allocation
,D/dalvikvm( 4624): GC_CONCURRENT freed 1920K, 15% free 23497K/27448K, paused 2ms+3ms, total 41ms
D/dalvikvm( 4624): GC_FOR_ALLOC freed 150K, 15% free 23386K/27448K, paused 23ms, total 24ms
I/dalvikvm-heap( 4624): Grow heap (frag case) to 26.575MB for 1639352-byte allocation
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 4624): GC_CONCURRENT freed 1828K, 18% free 24006K/29052K, paused 1ms+3ms, total 31ms
D/dalvikvm( 4624): GC_FOR_ALLOC freed 1059K, 18% free 23990K/29052K, paused 25ms, total 26ms
I/dalvikvm-heap( 4624): Grow heap (frag case) to 27.946MB for 2459024-byte allocation
D/dalvikvm( 4624): GC_CONCURRENT freed 411K, 17% free 26386K/31456K, paused 2ms+2ms, total 38ms
D/dalvikvm( 4624): GC_FOR_ALLOC freed 4095K, 21% free 25014K/31456K, paused 31ms, total 31ms
I/dalvikvm-heap( 4624): Grow heap (frag case) to 30.120MB for 3688532-byte allocation
D/dalvikvm( 4624): GC_CONCURRENT freed 338K, 19% free 28462K/35060K, paused 2ms+4ms, total 37ms
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4624): GC_FOR_ALLOC freed 4403K, 26% free 26137K/35060K, paused 34ms, total 34ms
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/WifiController(  967): battery changed pluggedType: 2
W/jxcore-log( 4624): Initializing JXcore engine
,W/jxcore-log( 4624): JXcore engine is ready
,D/dalvikvm( 4624): GC_CONCURRENT freed 420K, 18% free 28941K/35060K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 4624): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 4624): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 4624): Starting JXcore engine
,W/jxcore-log( 4624): Platform android
W/jxcore-log( 4624): 
,W/jxcore-log( 4624): Process ARCH arm
W/jxcore-log( 4624): 
,I/jxcore-log( 4624): JXcore Cordova bridge is ready!
I/jxcore-log( 4624): 
,W/jxcore-log( 4624): JXcore engine is started
,E/jxcore  ( 4624): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4624): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4624): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  967): Finishing activity token=Token{43b2e900 ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  967): GC_FOR_ALLOC freed 292K, 51% free 29580K/59844K, paused 71ms, total 72ms
,I/dalvikvm-heap(  967): Grow heap (frag case) to 31.882MB for 856096-byte allocation
,D/dalvikvm(  967): GC_FOR_ALLOC freed 868K, 52% free 29548K/60684K, paused 67ms, total 67ms
,W/PluginManager( 4624): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 152ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{430c2758 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1} (in existing)
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
D/PhoneApp( 1449): getIsInUseVoLTE : false
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=2ms
I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1824): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:15:58
D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1824): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1824): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1824): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1824): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:15:58
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/InputMethodManagerService(  967): IME STATUS OFF
W/IInputConnectionWrapper( 4624): showStatusIcon on inactive InputConnection
D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1824): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1824): 2 : Map key string is -2
,D/lim     ( 1824): 2 : time = 18:15
I/WeatherReflect( 1824): Model Name : LG-D802
D/WeatherTheme( 1824): 2 : Different view - status_min_formatted : 14 != 15
,D/WeatherTheme( 1824): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1824): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1824): 2 : Fixed theme : optimus
,D/WeatherTheme( 1824): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 2880K, 9% free 71536K/78432K, paused 25ms, total 25ms
,D/dalvikvm( 1489): GC_FOR_ALLOC freed 5584K, 9% free 60775K/66648K, paused 18ms, total 18ms
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ActivityManager(  967): Killing 4102:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1}
,D/dalvikvm( 1489): GC_FOR_ALLOC freed 4801K, 9% free 61983K/67444K, paused 18ms, total 19ms
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@42899fe8 time:115401
,D/UsbSettings( 2621): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2621): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2621): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2621): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{431ae758 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1} time:115450
,E/libEGL  ( 4624): call to OpenGL ES API with no current context (logged once per thread)
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  967): Killing 3851:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{43c57df8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1}
,I/GAV2    ( 4557): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/ConfigService( 1519): onDestroy
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1824): 2 : TimeTick Intent has been received, Time(hour:min:sec) 18:16:0
,D/WeatherService( 1824): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1824): 2 : SDK version : 19
,D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1824): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1824): 2 : Map key string is -2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396560045, nextTick: 59987, mDrawingTime: 0
,D/lim     ( 1824): 2 : time = 18:16
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396560048, nextTick: 59982, mDrawingTime: 1
,I/WeatherReflect( 1824): Model Name : LG-D802
D/WeatherTheme( 1824): 2 : Different view - status_min_formatted : 15 != 16
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,D/WeatherTheme( 1824): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,D/WeatherTheme( 1824): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1824): 2 : Fixed theme : optimus
,D/WeatherTheme( 1824): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1489): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,D/WeatherService( 1824): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 18:16:0
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  292): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.460800 Y: -0.423584 Z: 9.780151 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460800 .y:-0.423584 .z:9.780151
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.466309 Y: -0.430283 Z: 9.790405 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466309 .y:-0.430283 .z:9.790405
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4190): [393] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4190): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8101 usec
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.453690 Y: -0.410126 Z: 9.813919 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453690 .y:-0.410126 .z:9.813919
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.458633 Y: -0.418411 Z: 9.813919 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458633 .y:-0.418411 .z:9.813919
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  353): sns_pwr.c(292):acquiring wakelock
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
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.462326 Y: -0.412354 Z: 9.810135 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462326 .y:-0.412354 .z:9.810135
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449860 Y: -0.421082 Z: 9.787445 
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.448761 Y: -0.413315 Z: 9.801865 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.449860 .y:-0.421082 .z:9.787445
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.470795 Y: -0.412170 Z: 9.811890 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470795 .y:-0.412170 .z:9.811890
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.451340 Y: -0.410034 Z: 9.812729 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451340 .y:-0.410034 .z:9.812729
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@444cfd30)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1142): notifyScreenOnLocked
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,I/WindowManager(  967): No lock screen! windowToken=null
D/SurfaceFlinger(  275): Screen released, type=0 flinger=0xb7bff450
D/qdhwcomposer(  275): hwc_blank: Blanking display: 0
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.446625 Y: -0.410599 Z: 9.812729 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446625 .y:-0.410599 .z:9.812729
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WeatherAncestor( 1824): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:16:21
,E/SlideAside( 3994): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3994): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2074): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,D/wpa_supplicant( 2074): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2074): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2074): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  967): handleMessage: X
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
,V/SRS_Proc(  278): ParamSet string: screen_state=on
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2),
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433c1c60 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
,D/WeatherAncestor( 1824): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:16:21
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1824): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
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
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.455536 Y: -0.425186 Z: 9.800919 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455536 .y:-0.425186 .z:9.800919
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
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
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/qdlights( 1156): set_light_notifications: 2,ff00e7e7,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 231, B = 231
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.453995 Y: -0.421463 Z: 9.809784 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453995 .y:-0.421463 .z:9.809784
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/qdlights( 1156): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 225, B = 225
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdhwcomposer(  275): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 401ms
D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 5259K, 13% free 69568K/79764K, paused 22ms, total 22ms
D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396581917, nextTick: 38115, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396581935, nextTick: 38098, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:16:21
,D/WeatherService( 1824): 2 : ACTION screen on
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:16:21
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1142): notifyScreenOffLocked
,D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
,I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1}
,D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
,V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
,I/LGImmersionVibrator(  967): Vibrator off
,D/WifiStateMachine(  967): handleScreenStateChanged: false
E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  278): ParamSet string: screen_state=off
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{429cc678 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  967): CMD_SCREEN_OFF 
,D/WifiController(  967): shouldWifiStayAwake TRUE
D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1156): clear
D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
,D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:16:22
,D/WeatherService( 1824): 2 : ACTION screen off
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:16:22
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/NfcService( 1475): NFC-C OFF
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
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
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1156): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 39, B = 39
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
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
,I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  353): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  292): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396599789052866; DSPS: 5281328; Offset: 1453396438615713023
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396619789926452; DSPS: 5936717; Offset: 1453396438615701599
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396620042, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396620054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396639791819206; DSPS: 6592139; Offset: 1453396438615702263
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1519): Vacuum at: now=1453396644631 tag=VacuumService
,I/GoogleURLConnFactory( 1519): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1519): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1519): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1519): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1519): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1519): No account for auth token provided
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1519): No account for auth token provided
,W/Uploader( 1519): No account for auth token provided
,W/Uploader( 1519):  no longer exists, so no auth token.
,W/Uploader( 1519): No account for auth token provided
,D/wpa_supplicant( 2074): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396659793229928; DSPS: 7247545; Offset: 1453396438615709177
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396679793740024; DSPS: 7902922; Offset: 1453396438615700474
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396680042, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396680055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396699795057516; DSPS: 8558325; Offset: 1453396438615705710
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396719796337196; DSPS: 9213727; Offset: 1453396438615703652
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396739797650261; DSPS: 9869130; Offset: 1453396438615704461
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396740032, nextTick: 59983, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396740050, nextTick: 59974, mDrawingTime: 3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396759798941659; DSPS: 10524532; Offset: 1453396438615714120
,D/dalvikvm( 2676): GC_CONCURRENT freed 7767K, 33% free 16861K/24832K, paused 3ms+1ms, total 39ms
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x428b99d8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1519): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1519): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1519): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1519): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1519): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1519): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1519): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1519): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4190): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4190): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4190): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4190): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4190): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4190): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4190): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4190): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4190): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4190): isDataSchedulerEnabled():false
D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396779799834308; DSPS: 11179921; Offset: 1453396438615721760
,I/LocationManagerService(  967): remove 430c30f0
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2676): GC_CONCURRENT freed 1597K, 31% free 17311K/24832K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2676): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/Mlt MonitorService( 2676): parseLastkmsg to dump
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396799800708832; DSPS: 11835310; Offset: 1453396438615711274
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396800024, nextTick: 59994, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396800056, nextTick: 59974, mDrawingTime: 2
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/WifiController(  967): battery changed pluggedType: 2
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396819802724189; DSPS: 12490736; Offset: 1453396438615712471
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396839803810536; DSPS: 13146132; Offset: 1453396438615700185
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396859805084954; DSPS: 13801534; Offset: 1453396438615692865
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396860049, nextTick: 59971, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396860056, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396879805510312; DSPS: 14456907; Offset: 1453396438615721494
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396899806378064; DSPS: 15112296; Offset: 1453396438615704236
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396919806814516; DSPS: 15767670; Offset: 1453396438615713442
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396920043, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396920054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396939807253622; DSPS: 16423045; Offset: 1453396438615694785
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396959807710177; DSPS: 17078419; Offset: 1453396438615724094
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396979808143033; DSPS: 17733794; Offset: 1453396438615699186
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396980048, nextTick: 59978, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453396980053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453396999808583078; DSPS: 18389168; Offset: 1453396438615711985
,D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2074): nl80211: Disconnect event
D/wpa_supplicant( 2074): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2074): wlan0: Deauthentication notification
D/wpa_supplicant( 2074): wlan0:  * reason 0
D/wpa_supplicant( 2074): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2074): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2074): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2074): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2074): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/WifiStateMachine(  967): processMsg: ConnectedState,
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState,
D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP,
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1,
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb85c7d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2074):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2074): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
,D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine(  967): addressRemoved: 192.168.1.155/24 on wlan0 flags 128 scope 0
D/DhcpStateMachine(  967): RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 2074): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2074): wlan0: nl80211: scan request
,D/wpa_supplicant( 2074): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2074): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2074): wlan0: nl80211: Scan trigger
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiHS20(  967): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
D/QCNEA   (  392): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  392): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  392): |CAC| updateNetCfgInfo
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC|                   Netconfig               
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  392): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  392): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  392): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  392): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  392): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  392): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| Received bssid= 
D/QCNEA   (  392): |CAC| net type = 3
V/QCNEA   (  392): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  392): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  392): |CAC| 	ssid           =NG700
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  392): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  392): |CAC| dispatchNetCfg: updating:0xb7fe08dc
,D/QCNEA   (  392): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.,
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5222 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  967): handleMessage: X
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5222): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5222): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5222): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,I/PCSuite ( 5222): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5222): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5222): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  272): RouteController
W/NetworkManagementService(  967): route cmd failed: 
W/NetworkManagementService(  967): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  967): '
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  967): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  967): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  967): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  967): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x6146d520 clazz=0x69c00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5263 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  967): Killing 2142:android.process.media/u0a23 (adj 15): empty #17
V/NativeCrypto( 1519): Read error: ssl=0x639ca540: I/O error during system call, Connection timed out
V/NativeCrypto( 1519): SSL shutdown failed: ssl=0x639ca540: I/O error during system call, Broken pipe
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/dalvikvm(  276): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 31ms
D/DhcpStateMachine(  967): StoppedState
,D/HyLog   ( 5263): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5263): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5263): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/wpa_supplicant( 2074): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QRemote ( 5263): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 25ms
,D/QRemote ( 5263): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5263): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 5263): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5263): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5263): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5263): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5263): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 4291:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/SocketClient(  272): write error (Broken pipe)
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2074): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2074): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2074): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2074): nl80211: Survey data missing
D/wpa_supplicant( 2074): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2074): wlan0: BSS: Add new id 3 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Add new id 4 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Add new id 5 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Add new id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2074): wlan0: New scan results available
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2074): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2074): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2074): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2074): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2074): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2074): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2074): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2074): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-83
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-83 wps
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: No APs found - clear blacklist and try again
,D/wpa_supplicant( 2074): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear),
,D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 2074): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2074): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2074): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2074): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85c95a8  current_ssid=0x0
D/wpa_supplicant( 2074): scard is not null..
D/wpa_supplicant( 2074): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2074): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2074): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2074): wlan0: Cancelling scan request
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): wlan0: WPA: clearing own WPA/RSN IE
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 38:f8:89:11:e9:11]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 64:7c:34:12:7f:81]
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 2074): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2074): RSN: PMKSA cache search - network_ctx=0xb85c95a8 try_opportunistic=0
D/wpa_supplicant( 2074): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2074): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2074): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2074): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2074): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2074): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2074): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2074): WPA: Set own W,PA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2074): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2074): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2074): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2074): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2074): nl80211: Unsubscribe mgmt frames handle 0xb85c8590 (mode change)
D/wpa_supplicant( 2074): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590,
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2074): nl80211: Connect (ifindex=23)
,D/wpa_supplicant( 2074):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074):   * freq=2412
,D/wpa_supplicant( 2074):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2074):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074):   * Auth Type 0,
D/wpa_supplicant( 2074):   * WPA Versions 0x2
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2074): nl80211: Connect request send successfully,
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec,
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2074): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  967): handleMessage: X,
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity
,D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2074): nl80211: Connect event
D/wpa_supplicant( 2074): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2074): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2074): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2074): wlan0: Association info event
D/wpa_supplicant( 2074): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2074): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2074): wlan0: freq=2412 MHz
D/wpa_supplicant( 2074): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2074): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2074): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2074): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): scard is not null..
D/wpa_supplicant( 2074): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2074): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2074): TDLS: Remove peers on association
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2074): EAPOL: enable timer tick
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2074): wlan0: Cancelling scan request
,D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5300 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 9c 9b 03 0a e9 b8 35 70 76 99 2e d1 be 98 a5 ...
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2074): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2074): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2074): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2074): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2074):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2074):   key_nonce - hexdump(len=32): 9c 9b 03 0a e9 b8 35 70 76 99 2e d1 be 98 a5 0d 20 f9 af 06 fa 8d a0 e4 82 35 d7 2b 10 fc 03 c7
D/wpa_supplicant( 2074):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 9c 9b 03 0a e9 b8 35 70 76 99 2e d1 be 98 a5 ...
D/wpa_supplicant( 2074): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2074): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2074): Get randomness: len=32 entropy=5
D/wpa_supplicant( 2074): WPA: Renewed SNonce - hexdump(len=32): 57 d4 ea ad d1 0d b1 47 e4 e4 61 9c f2 e5 c1 25 3b d3 46 22 fb 05 84 bd 85 f3 d1 f1 53 35 1d 77
D/wpa_supplicant( 2074): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): WPA: Nonce1 - hexdump(len=32): 57 d4 ea ad d1 0d b1 47 e4 e4 61 9c f2 e5 c1 25 3b d3 46 22 fb 05 84 bd 85 f3 d1 f1 53 35 1d 77
D/wpa_supplicant( 2074): WPA: Nonce2 - hexdump(len=32): 9c 9b 03 0a e9 b8 35 70 76 99 2e d1 be 98 a5 0d 20 f9 af 06 fa 8d a0 e4 82 35 d7 2b 10 fc 03 c7
D/wpa_supplicant( 2074): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2074): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2074): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2074): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2074): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): WPA: Derived Key MIC - hexdump(len=16): ba ca 62 e7 62 e0 0d da e4 a5 f7 f4 75 d2 00 49
,D/wpa_supplicant( 2074): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 57 d4 ea ad d1 0d b1 47 e4 e4 61 9c f2 e5 c1 ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 9c 9b 03 0a e9 b8 35 70 76 99 2e d1 be 98 a5 ...
D/wpa_supplicant( 2074): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2074): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2074): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2074): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2074):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2074):   key_nonce - hexdump(len=32): 9c 9b 03 0a e9 b8 35 70 76 99 2e d1 be 98 a5 0d 20 f9 af 06 fa 8d a0 e4 82 35 d7 2b 10 fc 03 c7
D/wpa_supplicant( 2074):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_rsc - hexdump(len=8): b4 40 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_mic - hexdump(len=16): 87 74 a8 1f 04 eb fb a2 06 2f d1 4f bc dd 64 5e
D/wpa_supplicant( 2074): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 9c 9b 03 0a e9 b8 35 70 76 99 2e d1 be 98 a5 ...
D/wpa_supplicant( 2074): RSN: encrypted key data - hexdump(len=56): 08 1d 70 fc 03 ae 37 b1 19 d6 ec 2b 74 e1 b3 e4 1a 80 4f 90 ad 63 d5 44 0f 76 7d f4 d3 43 8f 04 ...
D/wpa_supplicant( 2074): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2074): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2074): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 73 0b ...
D/wpa_supplicant( 2074): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2074): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2074): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): WPA: Derived Key MIC - hexdump(len=16): 45 8a b8 0c ed 5e b1 75 ab 84 cf d8 e3 65 fb ee
,D/wpa_supplicant( 2074): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2074): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb85c8c54 key_idx=0 set_tx=1 seq_len=6 key_len=16,
,D/wpa_supplicant( 2074):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2074): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2074): WPA: RSC - hexdump(len=6): b4 40 00 00 00 00
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2803a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2074):    broadcast key
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2074): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2074): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2074): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2074): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2074): EAPOL authentication completed successfully
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967):, processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
D/WifiNative-wlan0(  967): doString: STATUS
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2074): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
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
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
E/Parcel  (  392): Reading a NULL string not supported here.
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-17ms what=147462 obj=android.net.wifi.StateChangeResult@447b34d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/HyLog   ( 5300): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/Parcel  (  392): Reading a NULL string not supported here.
D/HyLog   ( 5300): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5300): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/DhcpStateMachine(  967): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  967): ObtainingIpState{ when=-14ms what=147462 obj=android.net.wifi.StateChangeResult@447b0348 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-13ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
V/DownloadManager( 5300): DownloadService onCreate
,E/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
,E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,I/DownloadManager( 5300): in removeSpuriousFiles
,D/EAS     ( 4539): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4539): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/CommandListener(  272): Setting iface cfg
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432a9890 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432a9890 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
D/CommandListener(  272): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/eas_req ( 4539): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
D/WifiStateMachine(  967): processMsg: ObtainingIpState
V/DownloadManager( 5300): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428d83e0 on behalf of 5300
V/DownloadManager( 5300): DownloadService onStartCommand
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
I/DownloadManager( 5300): in trimDatabase
V/DownloadManager( 5300): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
V/DownloadManager( 5300): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428d9e88 on behalf of 5300
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428dc080 on behalf of 5300
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): DHCP successful
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
W/linker  ( 4539): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
D/HtmlEditor( 4539): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4539): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4539): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/LgeMiscReceiver( 4254): networkInfo.isConnected() = false
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): send additional Connectivity Action
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
E/Parcel  (  392): Reading a NULL string not supported here.
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
I/dalvikvm( 4539): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/HtmlEditor( 4539): register_HtmlEditor, Success
D/HtmlEditor( 4539): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4539): register_HtmlEditorTimer, Success
D/HtmlEditor( 4539): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4539): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4539): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4539): register_HtmlEditorFont, Success
D/HtmlEditor( 4539): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4539): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4539): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4539): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4539): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4539): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4539): JNI_OnLoad Success
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  967): handleMessage: X
,I/HubEmail( 4539): JNI_OnLoad()
I/HubEmail( 4539): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4539): registerNatives()
I/HubEmail( 4539): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 4539): registerNativeMethods()
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5337 uid=10052 gids={50052, 3003}
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,I/HubEmail( 4539): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/dalvikvm(  967): GC_CONCURRENT freed 2240K, 50% free 30585K/60684K, paused 5ms+11ms, total 155ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 102ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 106ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 105ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 105ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 94ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 96ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 106ms
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 105ms
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,W/Settings( 4539): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5300): DownloadService onDestroy
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,E/Parcel  (  392): Reading a NULL string not supported here.
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
D/HyLog   ( 5337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5337): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  272): RouteController
I/ActivityManager(  967): Killing 4460:com.android.defcontainer/u0a4 (adj 15): empty #17
,V/        (  272): RouteController
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,V/        (  272): RouteController
,V/        (  272): RouteController
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5337): [loadRssi] File not exist 
V/        (  272): RouteController
,V/LGRssiData( 5337): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5337): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 5337): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5337): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5337): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5337): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 5337): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5337): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5337): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 5337): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5337): onReceive CONNECTIVITY_CHANGE networkType=1
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5375 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4498:com.google.android.partnersetup/u0a9 (adj 15): empty #17
E/PhoneMonitor( 5337): onOtaspChanged old =0, new =3
V/PhoneMonitor( 5337): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  392): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  392): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  392): |CAC| updateNetCfgInfo
V/QCNEA   (  392): |CAC| *********************************************
,V/QCNEA   (  392): |CAC|                   Netconfig               
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  392): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  392): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  392): |CAC| 	NetConfig: ip4        =192.168.1.155
V/QCNEA   (  392): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  392): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  392): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  392): |CAC| net type = 1
V/QCNEA   (  392): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  392): |CAC| Received ssid= NG700
V/QCNEA   (  392): |CAC| 	ssid           =NG700
V/QCNEA   (  392): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  392): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  392): |CAC| dispatchNetCfg: updating:0xb7fe08dc
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QCNEA   (  392): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/HyLog   ( 5375): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5375): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5375): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1854): Checking schedule, now: 1453397015562 next: 1453396503748
,I/CheckinService( 1854): active receiver: enabled
,I/CheckinService( 1854): Preparing to send checkin request
,I/EventLogService( 1854): Accumulating logs since 1453396471167
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5392 uid=10066 gids={50066, 4002, 3003, 1028}
E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 5392): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5392): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5392): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  967): Killing 4527:com.lge.bnr/1000 (adj 15): empty #17
D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5405 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5405): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5405): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5405): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5405): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5405): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5419 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  967): Killing 4152:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5419): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5419): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5419): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 5419): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5419): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 5419): intf.getDisplayName() = lo
,I/Wireless_Storage( 5419): intf.getDisplayName() = sit0
I/Wireless_Storage( 5419): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5419): intf.getDisplayName() = teql0
,I/Wireless_Storage( 5419): intf.getDisplayName() = wlan0
D/NFS     ( 5419): interface name:wlan0 name:wlan0
,D/NFS     ( 5419): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5419): interface name:wlan0 name:wlan0
D/NFS     ( 5419): addr:192.168.1.155 broadcast:192.168.1.255
,I/Wireless_Storage( 5419): CONNECT : WIFI_CONNECT
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5434 uid=10104 gids={50104, 3003, 1028, 1015}
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  967): Killing 4169:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,D/HyLog   ( 5434): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5434): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5434): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1519): GC_CONCURRENT freed 1690K, 28% free 18105K/24832K, paused 7ms+4ms, total 41ms
,D/dalvikvm( 1519): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x431e4b48: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
,W/GAV2    ( 5434): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5451 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5451): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5451): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5451): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5451): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5451): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5451): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5451): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5451): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5451): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5451): install
,I/MultiDex( 5451): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5451): loading existing secondary dex files
,I/MultiDex( 5451): load found 3 secondary dex files
,I/MultiDex( 5451): install done
,D/dalvikvm( 5451): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5451): VFY: unable to resolve instance field 61
,D/dalvikvm( 5451): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5451): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5451): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5451): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5451): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5451): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5451): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5451): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5451): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5451): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a2450
,D/dalvikvm( 5451): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a2450
,D/dalvikvm( 5451): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a2450, skipping init
,D/dalvikvm( 5451): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a2450
D/dalvikvm( 5451): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a2450
,V/JNIHelp ( 5451): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/wpa_supplicant( 2074): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2074): EAPOL: disable timer tick
,D/dalvikvm( 5451): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a2450
,D/dalvikvm( 5451): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428a2450
D/dalvikvm( 5451): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a2450
,D/dalvikvm( 5451): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428a2450
,V/WebViewChromium( 5434): Binding Chromium to the main looper Looper (main, tid 1) {42899670}
,I/chromium( 5434): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5434): Initializing chromium process, renderers=0
,W/chromium( 5434): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5434): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5434): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5434): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5434): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5434): Remote Branch: 
I/Adreno-EGL( 5434): Local Patches: 
I/Adreno-EGL( 5434): Reconstruct Branch: 
,I/ProviderInstaller( 5451): Installed default security provider GmsCore_OpenSSL
,I/NSApplication( 5434): Starting up...
,I/ActivityManager(  967): Killing 4557:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 5263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5263): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/dalvikvm( 5451): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5451): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5451): VFY: replacing opcode 0x6e at 0x000d
,D/QRemote ( 5263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5263): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/dalvikvm( 5451): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5451): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5451): VFY: replacing opcode 0x6e at 0x0201
,D/QRemote ( 5263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5263): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5222): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5222): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5263): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5263): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5263): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5263): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1519): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1519): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1519): Proximity feature is not enabled.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d5e000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d5e000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/WearableService( 1737): callingUid 10006, callindPid: 1737
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,E/MDM     ( 1424): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/LocationInitializer( 1854): Restart initialization of location
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=2382847615
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 5451): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42abf010
,D/dalvikvm( 5451): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42abf010
,D/dalvikvm( 5451): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42abf010, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3959605187
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
,V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5451): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5524): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5451): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5451): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 87ms
,I/Adreno-EGL( 5451): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5451): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5451): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5451): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5451): Remote Branch: 
I/Adreno-EGL( 5451): Local Patches: 
I/Adreno-EGL( 5451): Reconstruct Branch: 
,I/Adreno-EGL( 5451): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5451): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5451): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5451): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5451): Remote Branch: 
I/Adreno-EGL( 5451): Local Patches: 
I/Adreno-EGL( 5451): Reconstruct Branch: 
,I/Adreno-EGL( 5451): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5451): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5451): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5451): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5451): Remote Branch: 
I/Adreno-EGL( 5451): Local Patches: 
I/Adreno-EGL( 5451): Reconstruct Branch: 
,W/Settings( 5451): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,V/NativeCrypto( 1854): SSL shutdown failed: ssl=0x6bed1bd0: I/O error during system call, Connection timed out
D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1854): Sending checkin request (11461 bytes)
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3728): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3728): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3728): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3728): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3728): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4539): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5300): DownloadService onCreate
,D/EAS     ( 4539): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4539): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4254): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 5337): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5337): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5405): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5405): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5419): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5419): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 5300): in removeSpuriousFiles
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 5300): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5300): DownloadService onStartCommand
,V/DownloadManager( 5300): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428e42c0 on behalf of 5300
,W/Settings( 4539): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428e4508 on behalf of 5300
,I/DownloadManager( 5300): in trimDatabase
,V/DownloadManager( 5300): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5300): DownloadService onDestroy
,V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428e64f0 on behalf of 5300
,D/GCM     ( 1519): Connected
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1519): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/dalvikvm(  967): GC_EXPLICIT freed 1766K, 50% free 30553K/60684K, paused 4ms+10ms, total 140ms
I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5300): DownloadService onCreate
,D/EAS     ( 4539): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4539): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 5300): in removeSpuriousFiles
,V/DownloadManager( 5300): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428ea2d0 on behalf of 5300
,I/DownloadManager( 5300): in trimDatabase
,V/DownloadManager( 5300): DownloadService onStartCommand
,V/DownloadManager( 5300): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5300): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428ebba8 on behalf of 5300
,V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428ed438 on behalf of 5300
I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4254): networkInfo.isConnected() = true
,D/PhoneState( 4254): setPdpRejectCasuse : false
,W/Settings( 4539): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 5337): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5337): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5300): DownloadService onDestroy
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5405): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 5419): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5419): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 5405): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43104530: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,I/CheckinTask( 1854): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1854): Checking schedule, now: 1453397018809 next: 1453974414805
,I/CheckinService( 1854): active receiver: disabled
,I/CheckinService( 1854): Checking schedule, now: 1453397018847 next: 1453974414805
,I/CheckinService( 1854): active receiver: disabled
,D/dalvikvm( 1854): GC_CONCURRENT freed 1812K, 22% free 19570K/24832K, paused 4ms+3ms, total 47ms
,D/GCM     ( 1519): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397019812038697; DSPS: 19044641; Offset: 1453396438615719117
,D/EAS     ( 4539): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5300): DownloadService onCreate
,D/EAS     ( 4539): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4254): networkInfo.isConnected() = true
,D/PhoneState( 4254): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5337): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5337): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5405): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5405): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5419): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5419): CONNECT : WIFI_CONNECT
,W/Settings( 4539): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/DownloadManager( 5300): in removeSpuriousFiles
,V/DownloadManager( 5300): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428f1b28 on behalf of 5300
I/DownloadManager( 5300): in trimDatabase
V/DownloadManager( 5300): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428f3998 on behalf of 5300
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 5300): DownloadService onStartCommand
V/DownloadManager( 5300): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 5300): created cursor android.database.sqlite.SQLiteCursor@428f5690 on behalf of 5300
,V/DownloadManager( 5300): DownloadService onDestroy
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 5434): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  967): Killing 5222:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): Killing 4190:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5630 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/administrator(  967): Handling package changes for user 0
,E/SlideAside( 3994): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3994): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
D/HyLog   ( 5630): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5630): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5630): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5630): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5630): MmsConfig.loadMmsSettings
I/Babel   ( 5630): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5630): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5630): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5630): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5630): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 5630): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 5630): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5630): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5630): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5630): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 5630): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5630): MmsConfig.loadFromResources
,E/Babel   ( 5630): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5630): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5630): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5630): [loadRssi] File not exist 
,V/LGRssiData( 5630): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5630): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5630): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5630): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5630): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3728): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3728): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3728): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3728): begin check event
D/AppUp4:Utils( 3728): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3728): Event For Nothing, skip.
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5680 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5680): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5680): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5680): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5680): BUILD Country: EU
,I/SystemConfig( 5680): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 5263:com.lge.qremote/u0a96 (adj 15): empty #17
I/ActivityManager(  967): Killing 5300:android.process.media/u0a23 (adj 15): empty #17
,D/dalvikvm( 2676): GC_CONCURRENT freed 2503K, 33% free 16728K/24832K, paused 1ms+1ms, total 15ms
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5696 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/SystemConfig( 5680): systemFeature RCS result false
,D/SystemConfig( 5680): refreshRcsSupport() :false
,D/HyLog   ( 5696): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5696): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5696): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  276): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+5ms, total 42ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 3ms+4ms, total 36ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 27ms
,I/ActivityManager(  967): Killing 4539:com.lge.email/u0a24 (adj 15): empty #17
I/IcingCorporaProvider( 2691): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5713 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5713): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5713): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5713): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5713): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5713): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5713): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5713): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5713): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 5713): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5713): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5713): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5713): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5713): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5713): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5713): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5713): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5713): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5713): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5713): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5713): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 5713): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5713): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5713): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5713): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5713): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5713): VFY: replacing opcode 0x6e at 0x029a
,I/IcingCorporaProvider( 2691): UpdateCorporaTask done [took 271 ms] updated apps [took 271 ms] 
,I/ActivityManager(  967): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=5751 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 5713): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 5713): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5713): VFY: replacing opcode 0x6e at 0x001a
,D/HyLog   ( 5751): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5751): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5751): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5713): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5713): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5713): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5713): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5713): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1854): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1854): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 5751): DownloadService onCreate
,I/DownloadManager( 5751): in removeSpuriousFiles
,V/DownloadManager( 5751): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5751): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428d9040 on behalf of 5713
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428da7b8 on behalf of 5751
,I/DownloadManager( 5751): in trimDatabase
,V/DownloadManager( 5751): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/Finsky  ( 5713): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428dd340 on behalf of 5751
,V/DownloadManager( 5751): DownloadService onStartCommand
,V/DownloadManager( 5751): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428e07d0 on behalf of 5751
,D/Finsky  ( 5713): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/DownloadManager( 5751): DownloadService onDestroy
I/ActivityManager(  967): Killing 5337:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5713): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5713): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5713): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5713): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5713): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  967): GC_EXPLICIT freed 2156K, 49% free 30690K/59972K, paused 5ms+15ms, total 174ms
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5713): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 5713): Total arena pages for JIT: 11
,I/dalvikvm( 5713): Total arena pages for JIT: 12
I/dalvikvm( 5713): Total arena pages for JIT: 13
,I/dalvikvm( 5713): Total arena pages for JIT: 14
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5713): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5713): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5713): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5713): [1] DailyHygiene.reschedule: Scheduling new run in 82 minutes (failures=3)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 5630): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  967): Killing 5375:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397039813465669; DSPS: 19700048; Offset: 1453396438615711763
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397040038, nextTick: 59991, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397040046, nextTick: 59972, mDrawingTime: 5
,D/Finsky  ( 5713): [460] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5713): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397059814835556; DSPS: 20355453; Offset: 1453396438615708359
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397079816152005; DSPS: 21010856; Offset: 1453396438615712552
,W/ProcessCpuTracker(  967): Skipping unknown process pid 5860
,W/ProcessCpuTracker(  967): Skipping unknown process pid 5862
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397099817523561; DSPS: 21666261; Offset: 1453396438615710817
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397100042, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397100045, nextTick: 59970, mDrawingTime: 7
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397119817951574; DSPS: 22321635; Offset: 1453396438615711584
,D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2074): nl80211: Disconnect event
D/wpa_supplicant( 2074): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2074): wlan0: Deauthentication notification
D/wpa_supplicant( 2074): wlan0:  * reason 0
D/wpa_supplicant( 2074): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2074): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2074): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2074): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2074): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb85c7d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2074):    addr=c0:ff:d4:d3:aa:48,
,D/wpa_supplicant( 2074): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=0,
,D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
,D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): addressRemoved: 192.168.1.155/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
D/QCNEA   (  392): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  392): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  392): |CAC| updateNetCfgInfo
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC|                   Netconfig               
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  392): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  392): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  392): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  392): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  392): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  392): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| Received bssid= 
D/QCNEA   (  392): |CAC| net type = 3
V/QCNEA   (  392): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  392): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  392): |CAC| 	ssid           =NG700
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  392): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  392): |CAC| dispatchNetCfg: updating:0xb7fe08dc
,D/QCNEA   (  392): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/WifiHS20(  967): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2074): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2074): wlan0: nl80211: scan request
,D/wpa_supplicant( 2074): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/wpa_supplicant( 2074): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2074): wlan0: nl80211: Scan trigger
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5904 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 5904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5904): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,I/PCSuite ( 5904): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  272): RouteController
,D/PCSuite ( 5904): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5904): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/NetworkManagementService(  967): route cmd failed: 
W/NetworkManagementService(  967): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  967): '
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  967): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  967): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  967): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  967): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x6146d520 clazz=0xb3c00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
,V/NativeCrypto( 1519): Read error: ssl=0x63b297a8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1519): SSL shutdown failed: ssl=0x63b297a8: I/O error during system call, Broken pipe
I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5948 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  967): Killing 5392:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5948): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5948): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5948): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  967): StoppedState
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 5948): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 5948): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 5948): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 5948): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5948): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5948): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5948): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5948): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5948): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 5405:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397139818937974; DSPS: 22977027; Offset: 1453396438615721422
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/SocketClient(  272): write error (Broken pipe)
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2074): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2074): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2074): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 2074): nl80211: Survey data missing
D/wpa_supplicant( 2074): wlan0: BSS: Start scan result update 3
,D/wpa_supplicant( 2074): wlan0: BSS: Add new id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2074): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 2074): wlan0: New scan results available
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2074): WPS: AP c0:ff:d4:d3:aa:48 type 0 added,
,D/wpa_supplicant( 2074): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2074): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2074): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1,
D/wpa_supplicant( 2074): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2074): wlan0: Selecting BSS from priority group 1
,D/wpa_supplicant( 2074): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2074): wlan0: 2: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-53 wps
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-83
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-86,
,D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2074): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2074): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2074): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2074): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
,D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2074): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2074): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85c95a8  current_ssid=0x0
D/wpa_supplicant( 2074): scard is not null..
D/wpa_supplicant( 2074): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00,
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2074): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2074): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2074): wlan0: Cancelling scan request
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): wlan0: WPA: clearing own WPA/RSN IE,
D/wpa_supplicant( 2074): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2074): RSN: PMKSA cache search - network_ctx=0xb85c95a8 try_opportunistic=0
,D/wpa_supplicant( 2074): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2074): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2074): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2074): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2074): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2074): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2074): wlan0: WPA: using KEY_MGMT WPA-PSK,
D/wpa_supplicant( 2074): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0,
D/wpa_supplicant( 2074): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
,D/wpa_supplicant( 2074): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2074): wlan0: State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2074): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0),
D/wpa_supplicant( 2074): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2074): nl80211: Unsubscribe mgmt frames handle 0xb85c8590 (mode change)
D/wpa_supplicant( 2074): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
,D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0e
,D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2074): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2074):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074):   * freq=2412
,D/wpa_supplicant( 2074):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2074):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074):   * Auth Type 0
D/wpa_supplicant( 2074):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 06:7c:34:12:7f:81]
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE ,
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/WifiStateMachine(  967): processMsg: DisconnectedState,
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2074): nl80211: Connect request send successfully
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0,
,D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37,
D/wpa_supplicant( 2074): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2074): nl80211: Connect event
D/wpa_supplicant( 2074): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2074): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2074): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2074): wlan0: Association info event
D/wpa_supplicant( 2074): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2074): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2074): wlan0: freq=2412 MHz
D/wpa_supplicant( 2074): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2074): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2074): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2074): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): scard is not null..
D/wpa_supplicant( 2074): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2074): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2074): TDLS: Remove peers on association
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2074): EAPOL: enable timer tick
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2074): wlan0: Cancelling scan request
,D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 78 12 ae 3d fa 2a d4 f4 a0 22 4a a9 6c a2 aa ...
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2074): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2074): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2074): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2074): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2074):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2074):   key_nonce - hexdump(len=32): 78 12 ae 3d fa 2a d4 f4 a0 22 4a a9 6c a2 aa 40 cb 61 ce ec 3d 25 55 00 a6 68 dd ed aa ca c5 32
D/wpa_supplicant( 2074):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 78 12 ae 3d fa 2a d4 f4 a0 22 4a a9 6c a2 aa ...
D/wpa_supplicant( 2074): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2074): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2074): Get randomness: len=32 entropy=6
D/wpa_supplicant( 2074): WPA: Renewed SNonce - hexdump(len=32): 37 c0 fd ba 39 c5 ef 17 4f ea 09 a9 a0 f8 34 1f a8 a1 33 49 7e e8 47 db 89 61 a9 ac d7 92 4d e5
D/wpa_supplicant( 2074): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2074): WPA: Nonce1 - hexdump(len=32): 37 c0 fd ba 39 c5 ef 17 4f ea 09 a9 a0 f8 34 1f a8 a1 33 49 7e e8 47 db 89 61 a9 ac d7 92 4d e5
D/wpa_supplicant( 2074): WPA: Nonce2 - hexdump(len=32): 78 12 ae 3d fa 2a d4 f4 a0 22 4a a9 6c a2 aa 40 cb 61 ce ec 3d 25 55 00 a6 68 dd ed aa ca c5 32
D/wpa_supplicant( 2074): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2074): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2074): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2074): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2074): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): WPA: Derived Key MIC - hexdump(len=16): f2 63 3e b8 82 c9 0c 1d f1 53 a7 32 4b 94 ef 37
,D/wpa_supplicant( 2074): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 37 c0 fd ba 39 c5 ef 17 4f ea 09 a9 a0 f8 34 ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700],
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 78 12 ae 3d fa 2a d4 f4 a0 22 4a a9 6c a2 aa ...
D/wpa_supplicant( 2074): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2074): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2074): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2074): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2074):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2074):   key_nonce - hexdump(len=32): 78 12 ae 3d fa 2a d4 f4 a0 22 4a a9 6c a2 aa 40 cb 61 ce ec 3d 25 55 00 a6 68 dd ed aa ca c5 32
D/wpa_supplicant( 2074):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_rsc - hexdump(len=8): 0f 41 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_mic - hexdump(len=16): 2e 28 b6 5a fd 05 7b a2 1b b3 c8 bb 92 67 e9 19
D/wpa_supplicant( 2074): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 78 12 ae 3d fa 2a d4 f4 a0 22 4a a9 6c a2 aa ...
D/wpa_supplicant( 2074): RSN: encrypted key data - hexdump(len=56): 00 fe 0c ed ad bf aa 24 9f 3e af f1 f1 03 50 99 ce fd 4c 17 3a fc 0f 25 51 55 91 09 d8 d3 66 89 ...
D/wpa_supplicant( 2074): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2074): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2074): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 73 0b ...
D/wpa_supplicant( 2074): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2074): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2074): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): WPA: Derived Key MIC - hexdump(len=16): a1 3d 81 01 7b 35 d1 54 8f b5 e8 a6 e3 45 df 76
D/wpa_supplicant( 2074): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2074): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb85c8c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2074):    addr=c0:ff:d4:d3:aa:48
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2074): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2074): WPA: RSC - hexdump(len=6): 0f 41 00 00 00 00
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2803a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2074):    broadcast key
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2074): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2074): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2074): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2074): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2074): EAPOL authentication completed successfully
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): Network connection established
,D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2074): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  967):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  967): ssid=NG700
D/WifiNative-wlan0(  967): id=0
D/WifiNative-wlan0(  967): mode=station
D/WifiNative-wlan0(  967): pairwise_cipher=CCMP
D/WifiNative-wlan0(  967): group_cipher=CCMP
D/WifiNative-wlan0(  967): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  967): wpa_state=COMPLETED
D/WifiNative-wlan0(  967): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  967): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  967): ObtainingIpState{ when=-40ms what=147462 obj=android.net.wifi.StateChangeResult@433eced0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/AppUp4:CustFacade( 3728): isOpenOperator : true
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/AppUp4:CustFacade( 3728): isPhone : true
D/WifiStateMachine(  967): ObtainingIpState{ when=-39ms what=147462 obj=android.net.wifi.StateChangeResult@430ff480 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-40ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-9ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity
,I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=5994 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 5994): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5994): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5994): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring up wlan0
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432a9890 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432a9890 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,I/LGEmail ( 5994): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
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
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
E/Parcel  (  392): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
,D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  392): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
,V/        (  272): RouteController
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  272): RouteController
,V/        (  272): RouteController
,D/LGEmail ( 5994): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,W/BaseRuntimeLoader( 5994): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5994): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5994): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5994): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  392): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  392): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  392): |CAC| updateNetCfgInfo
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC|                   Netconfig               
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  392): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  392): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  392): |CAC| 	NetConfig: ip4        =192.168.1.155
V/QCNEA   (  392): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  392): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  392): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  392): |CAC| net type = 1
V/QCNEA   (  392): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  392): |CAC| Received ssid= NG700
V/QCNEA   (  392): |CAC| 	ssid           =NG700
V/QCNEA   (  392): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  392): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  392): |CAC| dispatchNetCfg: updating:0xb7fe08dc
D/QCNEA   (  392): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/EAS     ( 5994): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5994): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/eas_req ( 5994): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4254): networkInfo.isConnected() = false
,W/linker  ( 5994): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 5994): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 5994): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 5994): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 5994): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 5994): register_HtmlEditor, Success
D/HtmlEditor( 5994): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 5994): register_HtmlEditorTimer, Success
D/HtmlEditor( 5994): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 5994): register_HtmlEditorDownloader, Success
D/HtmlEditor( 5994): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5994): register_HtmlEditorFont, Success
,D/HtmlEditor( 5994): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5994): register_HtmlEditorDrawText, Success
D/HtmlEditor( 5994): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5994): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 5994): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5994): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 5994): JNI_OnLoad Success
,I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6028 uid=10052 gids={50052, 3003}
I/HubEmail( 5994): JNI_OnLoad()
I/HubEmail( 5994): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5994): registerNatives()
I/HubEmail( 5994): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5994): registerNativeMethods()
I/HubEmail( 5994): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 5994): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HyLog   ( 6028): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6028): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6028): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 5419:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,V/LGRssiData( 6028): [loadRssi] File not exist 
,V/LGRssiData( 6028): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6028): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 6028): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/BaseRuntimeLoader( 6028): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6028): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 6028): onReceive CONNECTIVITY_CHANGE networkType=1
W/BaseRuntimeLoader( 6028): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6028): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 6028): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6028): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6028): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6047 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 5434:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
E/PhoneMonitor( 6028): onOtaspChanged old =0, new =3
V/PhoneMonitor( 6028): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/CheckinService( 1854): Checking schedule, now: 1453397142773 next: 1453397048805
I/CheckinService( 1854): active receiver: enabled
,I/CheckinService( 1854): Preparing to send checkin request
,I/EventLogService( 1854): Accumulating logs since 1453397015596
D/HyLog   ( 6047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6047): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6064 uid=10066 gids={50066, 4002, 3003, 1028}
,E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 6064): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6064): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6064): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): Killing 5451:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6077 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 6077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6077): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1519): GC_EXPLICIT freed 1478K, 28% free 17985K/24832K, paused 2ms+3ms, total 40ms
,D/LGDMSGCM( 6077): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6077): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6091 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  967): Killing 4624:com.test.thalitest/u0a304 (adj 15): empty #17
,D/HyLog   ( 6091): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6091): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6091): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 6091): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6091): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6091): intf.getDisplayName() = lo
I/Wireless_Storage( 6091): intf.getDisplayName() = sit0
I/Wireless_Storage( 6091): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6091): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6091): intf.getDisplayName() = wlan0
D/NFS     ( 6091): interface name:wlan0 name:wlan0
D/NFS     ( 6091): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6091): interface name:wlan0 name:wlan0
D/NFS     ( 6091): addr:192.168.1.155 broadcast:192.168.1.255
,I/Wireless_Storage( 6091): CONNECT : WIFI_CONNECT
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6103 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 5630:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/dalvikvm(  276): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+2ms, total 21ms
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6103): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6103): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6103): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x42f32698: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6116 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6116): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6116): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6116): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 6116): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6116): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6116): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6116): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6116): install
,I/MultiDex( 6116): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6116): loading existing secondary dex files
,I/MultiDex( 6116): load found 3 secondary dex files
,D/dalvikvm(  967): GC_EXPLICIT freed 2256K, 49% free 30960K/59972K, paused 5ms+14ms, total 184ms
,I/MultiDex( 6116): install done
,W/GAV2    ( 6103): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 6116): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6116): VFY: unable to resolve instance field 61
D/dalvikvm( 6116): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6116): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6116): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 6116): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6116): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6116): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 6116): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6116): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 6116): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
D/dalvikvm( 6116): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289ade8
D/dalvikvm( 6116): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289ade8
D/dalvikvm( 6116): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289ade8, skipping init
D/dalvikvm( 6116): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289ade8
D/dalvikvm( 6116): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289ade8
V/JNIHelp ( 6116): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/wpa_supplicant( 2074): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2074): EAPOL: disable timer tick
,D/dalvikvm( 6116): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289ade8
,D/dalvikvm( 6116): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4289ade8
D/dalvikvm( 6116): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289ade8
,D/dalvikvm( 6116): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4289ade8
,I/ProviderInstaller( 6116): Installed default security provider GmsCore_OpenSSL
,V/WebViewChromium( 6103): Binding Chromium to the main looper Looper (main, tid 1) {4289f608}
,I/chromium( 6103): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6103): Initializing chromium process, renderers=0
,I/dalvikvm( 6116): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 6116): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6116): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6116): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6116): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6116): VFY: replacing opcode 0x6e at 0x0201
,W/chromium( 6103): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6103): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6103): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6103): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6103): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6103): Remote Branch: 
I/Adreno-EGL( 6103): Local Patches: 
I/Adreno-EGL( 6103): Reconstruct Branch: 
,I/NSApplication( 6103): Starting up...
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d5e000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d5e000
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Killing 5680:com.android.contacts/u0a21 (adj 15): empty #17
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/dalvikvm( 6116): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.a.a
W/dalvikvm( 6116): VFY: unable to resolve virtual method 299: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 6116): VFY: replacing opcode 0x6e at 0x0013
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,W/dalvikvm( 6116): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 6116): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 6116): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 6116): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 6116): VFY: unable to resolve virtual method 727: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 6116): VFY: replacing opcode 0x6e at 0x00bb
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,I/GoogleURLConnFactory( 6116): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  967): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=6164 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=2986903513
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,E/DataScheduler( 6116): isDataSchedulerEnabled():false
D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/HyLog   ( 6164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6164): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 6164): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4289b918
,D/dalvikvm( 6164): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4289b918
,D/jxcore_app_log( 6164): JniHelper::setJavaVM(0x41761838), pthread_self() = 1074590036
,E/JX-Cordova( 6164): JXcore wasn't initialized yet
,D/QRemote ( 5948): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5948): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5948): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5948): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5948): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5948): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5904): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5904): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5948): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5948): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5948): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5948): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1519): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1519): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1519): Proximity feature is not enabled.
,I/ActivityManager(  967): Killing 5696:com.android.gallery3d/u0a27 (adj 15): empty #17
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/WearableService( 1737): callingUid 10006, callindPid: 1737
,D/LocationInitializer( 1854): Restart initialization of location
,E/MDM     ( 1424): [66] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,D/dalvikvm( 6116): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c202f0
,D/dalvikvm( 6116): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c202f0
,D/dalvikvm( 6116): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c202f0, skipping init
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 6116): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 6116): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6214): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 6116): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6116): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 98ms
,I/Adreno-EGL( 6116): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6116): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6116): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6116): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6116): Remote Branch: 
I/Adreno-EGL( 6116): Local Patches: 
I/Adreno-EGL( 6116): Reconstruct Branch: 
,I/Adreno-EGL( 6116): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6116): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6116): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6116): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6116): Remote Branch: 
I/Adreno-EGL( 6116): Local Patches: 
I/Adreno-EGL( 6116): Reconstruct Branch: 
,I/Adreno-EGL( 6116): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6116): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6116): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6116): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6116): Remote Branch: 
I/Adreno-EGL( 6116): Local Patches: 
I/Adreno-EGL( 6116): Reconstruct Branch: 
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1760928676
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1854): Sending checkin request (11577 bytes)
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
,D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3728): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3728): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 3728): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3728): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3728): handleAsyncCustNotification do not startCustService
,D/EAS     ( 5994): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5751): DownloadService onCreate
,D/EAS     ( 5994): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 5994): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4254): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6028): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6028): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6077): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6077): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6091): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6091): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 5751): in removeSpuriousFiles
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5751): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428e7e50 on behalf of 5751
I/DownloadManager( 5751): in trimDatabase
W/Settings( 5994): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 5751): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428e9818 on behalf of 5751
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/DownloadManager( 5751): DownloadService onStartCommand
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 5751): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428eb550 on behalf of 5751
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 5751): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5751): DownloadService onCreate
,I/DownloadManager( 5751): in removeSpuriousFiles
,D/EAS     ( 5994): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 5751): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 5994): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5751): DownloadService onStartCommand
,V/DownloadManager( 5751): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428f1d18 on behalf of 5751
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428f0610 on behalf of 5751
I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4254): networkInfo.isConnected() = true
,D/PhoneState( 4254): setPdpRejectCasuse : false
,W/Settings( 5994): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 6028): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,I/DownloadManager( 5751): in trimDatabase
V/DownloadManager( 5751): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/MobileConnectivityChangeReceiver( 6028): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428f3aa8 on behalf of 5751
,V/DownloadManager( 5751): DownloadService onDestroy
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6077): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 6077): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 6091): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6091): CONNECT : WIFI_CONNECT
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43103130: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/GCM     ( 1519): Connected
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1519): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,I/CheckinTask( 1854): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1854): Checking schedule, now: 1453397146730 next: 1453974542725
,I/CheckinService( 1854): active receiver: disabled
,I/CheckinService( 1854): Checking schedule, now: 1453397146766 next: 1453974542725
,I/CheckinService( 1854): active receiver: disabled
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1519): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 5994): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 5751): DownloadService onCreate
,D/EAS     ( 5994): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 5751): in removeSpuriousFiles
,V/DownloadManager( 5751): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428f7538 on behalf of 5751
I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 5994): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4254): networkInfo.isConnected() = true
,D/PhoneState( 4254): setPdpRejectCasuse : false
,I/DownloadManager( 5751): in trimDatabase
,V/DownloadManager( 5751): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428f8628 on behalf of 5751
V/DownloadManager( 5751): DownloadService onStartCommand
,D/MobileConnectivityChangeReceiver( 6028): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/DownloadManager( 5751): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 6028): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5751): created cursor android.database.sqlite.SQLiteCursor@428fb0f8 on behalf of 5751
,V/DownloadManager( 5751): DownloadService onDestroy
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6077): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 6077): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
I/NFS     ( 6091): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6091): CONNECT : WIFI_CONNECT
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 6103): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  967): Killing 5904:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): Killing 5713:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3994): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3994): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  967): Handling package changes for user 0
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6304 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,D/HyLog   ( 6304): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6304): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6304): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mmsto"
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 6304): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6304): MmsConfig.loadMmsSettings
,I/Babel   ( 6304): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6304): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6304): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 6304): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 6304): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6304): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/Settings( 6304): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BaseRuntimeLoader( 6304): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6304): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6304): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6304): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6304): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6304): MmsConfig.loadFromResources
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3728): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3728): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3728): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,E/Babel   ( 6304): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6304): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,V/LGRssiData( 6304): [loadRssi] File not exist 
V/LGRssiData( 6304): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 6304): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,V/TelephonyAutoProfiling( 6304): [getMatchedProfile] selected file : /cust/config/featureset.xml
,V/TelephonyAutoProfiling( 6304): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6304): [getValue] FEATURE key : vzw_roaming_state, value : null
I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,D/AppUp4:Utils( 3728): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3728): Event For Nothing, skip.
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6353 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/HyLog   ( 6353): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6353): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6353): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6353): BUILD Country: EU
,I/SystemConfig( 6353): BUILD Operator: OPEN
,D/dalvikvm(  967): GC_EXPLICIT freed 2702K, 49% free 30735K/59972K, paused 2ms+7ms, total 85ms
,I/SystemConfig( 6353): systemFeature RCS result false
,D/SystemConfig( 6353): refreshRcsSupport() :false
I/ActivityManager(  967): Killing 5948:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): Killing 5751:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6369 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,D/HyLog   ( 6369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6369): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): Killing 5994:com.lge.email/u0a24 (adj 15): empty #17
,I/IcingCorporaProvider( 2691): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6385 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 6385): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6385): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6385): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1854): GC_CONCURRENT freed 1986K, 22% free 19563K/24832K, paused 9ms+3ms, total 45ms
,I/dalvikvm( 6385): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 6385): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6385): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6385): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6385): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 6385): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6385): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6385): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6385): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6385): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6385): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6385): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/IcingCorporaProvider( 2691): UpdateCorporaTask done [took 305 ms] updated apps [took 305 ms] 
,W/Settings( 6385): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6385): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6385): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6385): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6385): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 6385): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6385): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6385): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6385): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6385): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6385): VFY: replacing opcode 0x6e at 0x029a
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6385): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6385): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6385): VFY: replacing opcode 0x6e at 0x001a
I/ActivityManager(  967): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6423 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 6423): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6423): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6423): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6385): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 6385): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6385): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6385): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6385): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1854): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1854): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6423): DownloadService onCreate
,I/DownloadManager( 6423): in removeSpuriousFiles
,V/DownloadManager( 6423): DownloadService onStartCommand
,V/DownloadManager( 6423): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428de030 on behalf of 6423
,V/DownloadManager( 6423): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6423): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 6423): in trimDatabase
,V/DownloadManager( 6423): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428e3e18 on behalf of 6423
V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428e5308 on behalf of 6423
,V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428e4c10 on behalf of 6385
,V/DownloadManager( 6423): DownloadService onDestroy
,D/Finsky  ( 6385): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  967): Killing 6028:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/Finsky  ( 6385): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6385): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6385): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6385): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6385): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6385): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1519): GC_EXPLICIT freed 1150K, 28% free 17989K/24832K, paused 2ms+6ms, total 46ms
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6385): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6385): Total arena pages for JIT: 11
,I/dalvikvm( 6385): Total arena pages for JIT: 12
,I/dalvikvm( 6385): Total arena pages for JIT: 13
,I/dalvikvm( 6385): Total arena pages for JIT: 14
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6385): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6385): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Finsky  ( 6385): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6385): [1] DailyHygiene.reschedule: Scheduling new run in 257 minutes (failures=4)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6304): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  967): Killing 6047:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397159820296885; DSPS: 23632432; Offset: 1453396438615707042
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397160042, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397160055, nextTick: 59977, mDrawingTime: 1
,D/Finsky  ( 6385): [507] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6385): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397179821768775; DSPS: 24287840; Offset: 1453396438615714088
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397199822241026; DSPS: 24943216; Offset: 1453396438615698058
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397219822677515; DSPS: 25598590; Offset: 1453396438615707301
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397220042, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397220054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397239823127501; DSPS: 26253965; Offset: 1453396438615699523
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397259824024150; DSPS: 26909354; Offset: 1453396438615711162
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397279824473929; DSPS: 27564729; Offset: 1453396438615703178
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397280047, nextTick: 59982, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397280050, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397299825387087; DSPS: 28220119; Offset: 1453396438615700808
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397319825849656; DSPS: 28875494; Offset: 1453396438615705614
,D/wpa_supplicant( 2074): wlan0: BSS: Remove id 3 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Remove id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Remove id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Remove id 5 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 64:7c:34:12:7f:81]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 38:f8:89:11:e9:11]
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397339826300032; DSPS: 29530869; Offset: 1453396438615698226
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397340036, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397340044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397359828204488; DSPS: 30186291; Offset: 1453396438615710592
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397379829082043; DSPS: 30841680; Offset: 1453396438615703137
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397399829952593; DSPS: 31497068; Offset: 1453396438615719195
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397400042, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397400055, nextTick: 59978, mDrawingTime: 0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397419830422777; DSPS: 32152444; Offset: 1453396438615701098
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397439833985385; DSPS: 32807921; Offset: 1453396438615693149
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43223368: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1519): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1519): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1519): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1519): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1519): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1519): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1519): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1519): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 6385): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6385): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6385): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6385): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6385): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6385): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6385): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6385): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 6385): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6385): isDataSchedulerEnabled():false
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397459835316519; DSPS: 33463324; Offset: 1453396438615712027
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397460039, nextTick: 59969, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397460053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397479836692747; DSPS: 34118729; Offset: 1453396438615714964
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397499837608773; DSPS: 34774119; Offset: 1453396438615715463
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397519838910145; DSPS: 35429522; Offset: 1453396438615704579
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397520031, nextTick: 59982, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397520058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397539840222756; DSPS: 36084925; Offset: 1453396438615704934
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397559841618245; DSPS: 36740331; Offset: 1453396438615696615
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397579842481305; DSPS: 37395719; Offset: 1453396438615705182
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397580035, nextTick: 59987, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397580053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397599843376514; DSPS: 38051108; Offset: 1453396438615715382
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397619844356023; DSPS: 38706500; Offset: 1453396438615718328
,D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2074): nl80211: Disconnect event
D/wpa_supplicant( 2074): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2074): wlan0: Deauthentication notification
D/wpa_supplicant( 2074): wlan0:  * reason 0
D/wpa_supplicant( 2074): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2074): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2074): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2074): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2074): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  967): handleMessage: E msg.what=147460,
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState,
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost,
D/WifiStateMachine(  967): Stopping DHCP and clearing IP,
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb85c7d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2074):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): wlan0: State: COMPLETED -> DISCONNECTED
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized,
,D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state INITIALIZE
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2074): wlan0: BSS: Remove id 4 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c0:ff:d4:d3:aa:48]
,D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): addressRemoved: 192.168.1.155/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
D/QCNEA   (  392): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  392): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  392): |CAC| updateNetCfgInfo
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC|                   Netconfig               
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  392): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  392): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  392): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  392): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  392): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  392): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| Received bssid= 
D/QCNEA   (  392): |CAC| net type = 3
V/QCNEA   (  392): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  392): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  392): |CAC| 	ssid           =NG700
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  392): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  392): |CAC| dispatchNetCfg: updating:0xb7fe08dc
,D/QCNEA   (  392): |CAC| readCallback: read len:0, ret:-1, errno:11
D/wpa_supplicant( 2074): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2074): wlan0: nl80211: scan request
,D/wpa_supplicant( 2074): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiHS20(  967): hidePasspointNotification off =false,
D/wpa_supplicant( 2074): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2074): wlan0: nl80211: Scan trigger
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/QcConnectivityService(  967): Attempting to switch to mobile
,D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '95 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 95 Failed to remove route from default table (No such process)'
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6910 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '96 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 96 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '97 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 97 Failed to remove route from default table (No such process)'
V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,W/NetworkManagementService(  967): route cmd failed: 
W/NetworkManagementService(  967): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '99 route del src v6 2' failed with '400 99 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  967): '
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  967): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  967): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  967): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  967): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x6146d520 clazz=0xfc700001 iface=wlan0 mask=0x3
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
,V/NativeCrypto( 1519): Read error: ssl=0x638f7f30: I/O error during system call, Connection timed out
,V/NativeCrypto( 1519): SSL shutdown failed: ssl=0x638f7f30: I/O error during system call, Broken pipe
,D/DhcpStateMachine(  967): StoppedState
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/dalvikvm(  967): GC_EXPLICIT freed 2079K, 49% free 30705K/59972K, paused 8ms+13ms, total 173ms
,D/HyLog   ( 6910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6910): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PCSuite ( 6910): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6910): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6910): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6955 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  967): Killing 6064:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6955): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6955): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6955): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 6955): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6955): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6955): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6955): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6955): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6955): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6955): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6955): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6955): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 6077:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2074): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2074): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2074): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2074): nl80211: Survey data missing
D/wpa_supplicant( 2074): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 2074): wlan0: BSS: Add new id 8 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Add new id 9 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: BSS: Add new id 10 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2074): wlan0: New scan results available
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2074): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2074): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2074): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2074): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2074): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2074): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-80
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2074): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2074): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2074): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2074): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2074): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2074): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2074): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85c95a8  current_ssid=0x0
D/wpa_supplicant( 2074): scard is not null.,.
D/wpa_supplicant( 2074): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2074): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2074): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2074): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2074): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2074): wlan0: Cancelling scan request
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2074): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 2074): RSN: PMKSA cache search - network_ctx=0xb85c95a8 try_opportunistic=0,
,D/wpa_supplicant( 2074): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
,D/wpa_supplicant( 2074): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2074): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2074): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2,
D/wpa_supplicant( 2074): wlan0: WPA: clearing AP WPA IE
,D/wpa_supplicant( 2074): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2074): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2074): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2074): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2074): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2074): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2074): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2074): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2074): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2074): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2074): nl80211: Unsubscribe mgmt frames handle 0xb85c8590 (mode change),
D/wpa_supplicant( 2074): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590,
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
,D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590,
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09,
,D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 0a 07,
D/wpa_supplicant( 2074): nl80211: Register frame type=0xd0 nl_handle=0xb85c8590
D/wpa_supplicant( 2074): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2074): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2074):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2074):   * freq=2412
D/wpa_supplicant( 2074):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2074):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074):   * Auth Type 0,
D/wpa_supplicant( 2074):   * WPA Versions 0x2
D/wpa_supplicant( 2074): nl80211: Connect request send successfully
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): EAPOL: External notification - EAP fail=0,
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 c0:ff:d4:d3:aa:4a],
D/wpa_supplicant( 2074): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 38:f8:89:11:e9:11]
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState,
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2074): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 2074): nl80211: Event message available
D/wpa_supplicant( 2074): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2074): nl80211: Connect event
D/wpa_supplicant( 2074): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2074): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2074): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2074): wlan0: Association info event
D/wpa_supplicant( 2074): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2074): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2074): wlan0: freq=2412 MHz
D/wpa_supplicant( 2074): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2074): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2074): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2074): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): scard is not null..
D/wpa_supplicant( 2074): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2074): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2074): TDLS: Remove peers on association
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2074): EAPOL: enable timer tick
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2074): wlan0: Cancelling scan request
,D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700],
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e1 06 84 fe d8 4e 52 af be 80 41 b9 66 4a 8c ...
D/wpa_supplicant( 2074): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2074): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2074): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2074): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2074): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2074):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2074):   key_nonce - hexdump(len=32): e1 06 84 fe d8 4e 52 af be 80 41 b9 66 4a 8c 3b 23 29 e3 cf f5 85 a5 e2 f5 03 bc bf 6e b3 9c e0
D/wpa_supplicant( 2074):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e1 06 84 fe d8 4e 52 af be 80 41 b9 66 4a 8c ...
D/wpa_supplicant( 2074): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2074): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2074): Get randomness: len=32 entropy=4
D/wpa_supplicant( 2074): WPA: Renewed SNonce - hexdump(len=32): 61 36 b2 84 9a 68 53 1d db ec a7 cc 11 da f6 96 d0 53 d1 b3 ef a1 a7 57 fb 1f 24 07 74 46 43 df
D/wpa_supplicant( 2074): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): WPA: Nonce1 - hexdump(len=32): 61 36 b2 84 9a 68 53 1d db ec a7 cc 11 da f6 96 d0 53 d1 b3 ef a1 a7 57 fb 1f 24 07 74 46 43 df
D/wpa_supplicant( 2074): WPA: Nonce2 - hexdump(len=32): e1 06 84 fe d8 4e 52 af be 80 41 b9 66 4a 8c 3b 23 29 e3 cf f5 85 a5 e2 f5 03 bc bf 6e b3 9c e0
D/wpa_supplicant( 2074): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2074): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2074): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2074): wlan0: WPA: Sending EAPOL-Key 2/4
,D/wpa_supplicant( 2074): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): WPA: Derived Key MIC - hexdump(len=16): 2a 99 0f e7 e8 23 a8 0b 06 89 f1 33 81 ba 65 9b
,D/wpa_supplicant( 2074): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 61 36 b2 84 9a 68 53 1d db ec a7 cc 11 da f6 ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e1 06 84 fe d8 4e 52 af be 80 41 b9 66 4a 8c ...
D/wpa_supplicant( 2074): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2074): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2074): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2074): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2074):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2074):   key_nonce - hexdump(len=32): e1 06 84 fe d8 4e 52 af be 80 41 b9 66 4a 8c 3b 23 29 e3 cf f5 85 a5 e2 f5 03 bc bf 6e b3 9c e0
D/wpa_supplicant( 2074):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_rsc - hexdump(len=8): 71 42 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2074):   key_mic - hexdump(len=16): c9 bd d9 5d d4 6b f9 13 c5 8c 28 49 86 57 77 e3
D/wpa_supplicant( 2074): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e1 06 84 fe d8 4e 52 af be 80 41 b9 66 4a 8c ...
D/wpa_supplicant( 2074): RSN: encrypted key data - hexdump(len=56): 1e fd e2 4d 7c 2a cc 6e 1c 37 71 bd 15 29 fd a1 99 e8 c2 e0 8f 0a c2 34 97 8c d6 d5 2d 44 cd 3d ...
D/wpa_supplicant( 2074): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2074): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2074): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 73 0b ...
D/wpa_supplicant( 2074): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2074): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2074): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2074): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): WPA: Derived Key MIC - hexdump(len=16): b0 15 da db 33 ce 70 a5 30 9f 2d 3e 09 3a ab 06
,D/wpa_supplicant( 2074): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2074): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb85c8c54 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 2074):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2074): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED],
,D/wpa_supplicant( 2074): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2074): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2074): WPA: RSC - hexdump(len=6): 71 42 00 00 00 00
,D/wpa_supplicant( 2074): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2803a key_idx=1 set_tx=0 seq_len=6 key_len=16,
D/wpa_supplicant( 2074):    broadcast key
I/wpa_supplicant( 2074): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2074): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2074): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2074): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2074): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2074): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2074): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2074): wpa_supplicant_set_state, isWPS : 0
,D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2074): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2074): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 2074): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2074): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2074): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2074): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2074): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2074): EAPOL authentication completed successfully
D/wpa_supplicant( 2074): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2074): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2074): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
,D/WifiNative-wlan0(  967): doString: STATUS
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2074): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2074): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  967):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  967): ssid=NG700
D/WifiNative-wlan0(  967): id=0
D/WifiNative-wlan0(  967): mode=station
D/WifiNative-wlan0(  967): pairwise_cipher=CCMP
D/WifiNative-wlan0(  967): group_cipher=CCMP
D/WifiNative-wlan0(  967): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  967): wpa_state=COMPLETED
D/WifiNative-wlan0(  967): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  967): address=34:fc:ef:de:0a:e2
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :false
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
I/AppUp4:CustModeStarterReceiver( 3728): onReceive
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
D/AppUp4:CustFacade( 3728): isPhone : true
I/LicenseContentProvider( 3032): start selecting data
D/SIMObserver( 3032): simInfo1
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-29ms what=147462 obj=android.net.wifi.StateChangeResult@4326a7e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@431de3d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
I/AppUp4:EulaManager( 3728): getAgreementFo,rKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3728): begin check event
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity
D/WifiStateMachine(  967): ObtainingIpState{ when=-18ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7001 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 7001): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7001): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7001): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
,D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring up wlan0
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432a9890 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432a9890 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  967): handleMessage: X
I/LGEmail ( 7001): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2074): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2074): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2074): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2074): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2074): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2074): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  392): Reading a NULL string not supported here.
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
,D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine(  967): handleMessage: X
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  392): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
,E/Parcel  (  392): Reading a NULL string not supported here.
,D/LGEmail ( 7001): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,V/        (  272): RouteController
,W/BaseRuntimeLoader( 7001): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7001): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7001): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7001): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  272): RouteController
,V/        (  272): RouteController
,D/EAS     ( 7001): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7001): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/        (  272): RouteController
,D/eas_req ( 7001): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4254): networkInfo.isConnected() = false
D/QCNEA   (  392): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  392): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  392): |CAC| updateNetCfgInfo
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC|                   Netconfig               
V/QCNEA   (  392): |CAC| *********************************************
V/QCNEA   (  392): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  392): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  392): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  392): |CAC| 	NetConfig: ip4        =192.168.1.155
V/QCNEA   (  392): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  392): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  392): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  392): |CAC| net type = 1
V/QCNEA   (  392): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  392): |CAC| Received ssid= NG700
V/QCNEA   (  392): |CAC| 	ssid           =NG700
V/QCNEA   (  392): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  392): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  392): |CAC| *********************************************
D/QCNEA   (  392): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  392): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  392): |CAC| dispatchNetCfg: updating:0xb7fe08dc
,D/QCNEA   (  392): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=7035 uid=10052 gids={50052, 3003}
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,W/linker  ( 7001): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 7001): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 7001): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 7001): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/dalvikvm( 7001): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/HtmlEditor( 7001): register_HtmlEditor, Success
,D/HtmlEditor( 7001): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 7001): register_HtmlEditorTimer, Success
,D/HtmlEditor( 7001): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 7001): register_HtmlEditorDownloader, Success
D/HtmlEditor( 7001): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 7001): register_HtmlEditorFont, Success
D/HtmlEditor( 7001): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7001): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 7001): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 7001): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 7001): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7001): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 7001): JNI_OnLoad Success
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/HubEmail( 7001): JNI_OnLoad()
,I/HubEmail( 7001): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7001): registerNatives()
I/HubEmail( 7001): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7001): registerNativeMethods()
,I/HubEmail( 7001): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/dalvikvm(  276): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 3ms+3ms, total 37ms
,D/HyLog   ( 7035): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7035): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7035): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): Killing 6091:com.lge.wireless_storage/u0a101 (adj 15): empty #17
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 27ms
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 7035): [loadRssi] File not exist 
,V/LGRssiData( 7035): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 7035): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 7035): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7035): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7035): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7035): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+4ms, total 27ms
V/TelephonyAutoProfiling( 7035): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/MobileConnectivityChangeReceiver( 7035): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/TelephonyAutoProfiling( 7035): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7035): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 7035): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7058 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 6103:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,E/PhoneMonitor( 7035): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 7035): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1854): Checking schedule, now: 1453397636102 next: 1453397176725
,I/CheckinService( 1854): active receiver: enabled
D/HyLog   ( 7058): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7058): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7058): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1854): Preparing to send checkin request
,I/EventLogService( 1854): Accumulating logs since 1453397142808
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7072 uid=10066 gids={50066, 4002, 3003, 1028}
,E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 7072): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7072): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7072): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  967): Killing 6116:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=7085 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 7085): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7085): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7085): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 7085): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7085): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=7102 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  967): Killing 6164:com.test.thalitest/u0a304 (adj 15): empty #17,
,D/HyLog   ( 7102): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7102): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7102): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 7102): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7102): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 7102): intf.getDisplayName() = lo
I/Wireless_Storage( 7102): intf.getDisplayName() = sit0
I/Wireless_Storage( 7102): intf.getDisplayName() = p2p0
,I/Wireless_Storage( 7102): intf.getDisplayName() = teql0
,I/Wireless_Storage( 7102): intf.getDisplayName() = wlan0
,D/NFS     ( 7102): interface name:wlan0 name:wlan0
D/NFS     ( 7102): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 7102): interface name:wlan0 name:wlan0
,D/NFS     ( 7102): addr:192.168.1.155 broadcast:192.168.1.255
,I/Wireless_Storage( 7102): CONNECT : WIFI_CONNECT
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7115 uid=10104 gids={50104, 3003, 1028, 1015}
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  967): Killing 6304:com.google.android.talk/u0a77 (adj 15): empty #17
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HyLog   ( 7115): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7115): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7115): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x432afad8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GAV2    ( 7115): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7132 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 7132): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7132): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7132): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 7132): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7132): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 7132): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7132): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7132): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 7132): VM with version 1.6.0 does not have multidex support
I/MultiDex( 7132): install
D/wpa_supplicant( 2074): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2074): EAPOL: disable timer tick
,I/MultiDex( 7132): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 7132): loading existing secondary dex files
,I/MultiDex( 7132): load found 3 secondary dex files
,I/MultiDex( 7132): install done
,D/dalvikvm( 7132): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 7132): VFY: unable to resolve instance field 61
,D/dalvikvm( 7132): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 7132): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7132): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7132): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 7132): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7132): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7132): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 7132): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7132): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 7132): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a0668
,D/dalvikvm( 7132): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a0668
,D/dalvikvm( 7132): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a0668, skipping init
,D/dalvikvm( 7132): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a0668
,D/dalvikvm( 7132): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a0668
,V/JNIHelp ( 7132): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 7115): Binding Chromium to the main looper Looper (main, tid 1) {42898f60}
,I/chromium( 7115): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7115): Initializing chromium process, renderers=0
,D/dalvikvm( 7132): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a0668
D/dalvikvm( 7132): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428a0668
D/dalvikvm( 7132): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a0668
,D/dalvikvm( 7132): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428a0668
,W/chromium( 7115): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 7115): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7115): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7115): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7115): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7115): Remote Branch: 
I/Adreno-EGL( 7115): Local Patches: 
I/Adreno-EGL( 7115): Reconstruct Branch: 
,I/NSApplication( 7115): Starting up...
,I/ActivityManager(  967): Killing 6353:com.android.contacts/u0a21 (adj 15): empty #17
,I/ProviderInstaller( 7132): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=7163 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
,D/dalvikvm( 3880): GC_CONCURRENT freed 383K, 2% free 38258K/38924K, paused 2ms+8ms, total 63ms
,D/dalvikvm( 3880): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/HyLog   ( 7163): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/HyLog   ( 7163): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7163): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/dalvikvm( 7132): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 7132): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7132): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7132): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 7132): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7132): VFY: replacing opcode 0x6e at 0x0201
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 7163): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a0b20
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
D/dalvikvm( 7163): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a0b20
,D/jxcore_app_log( 7163): JniHelper::setJavaVM(0x41761838), pthread_self() = 1074590036
,E/JX-Cordova( 7163): JXcore wasn't initialized yet
,D/QRemote ( 6955): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d5e000
I/QRemote ( 6955): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d5e000
,D/QRemote ( 6955): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,I/QRemote ( 6955): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/QRemote ( 6955): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6955): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6910): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6910): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6955): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6955): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 6955): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6955): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/ActivityManager(  967): Killing 6369:com.android.gallery3d/u0a27 (adj 15): empty #17
I/WVCdm   (  278): CdmEngine::OpenSession
D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/GCM     ( 1519): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/AuthorizationBluetoothService( 1519): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1519): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/WearableService( 1737): callingUid 10006, callindPid: 1737
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,E/MDM     ( 1424): [67] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1854): Restart initialization of location
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  278): PrepareKeyRequest: nonce=3105476618
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 7132): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a67778
D/dalvikvm( 7132): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a67778
,D/dalvikvm( 7132): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a67778, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 7132): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 7132): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 7214): DexOpt: load 5ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 7132): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 7132): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 125ms
,I/Adreno-EGL( 7132): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7132): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7132): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7132): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7132): Remote Branch: 
I/Adreno-EGL( 7132): Local Patches: 
I/Adreno-EGL( 7132): Reconstruct Branch: 
,I/Adreno-EGL( 7132): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7132): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7132): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7132): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7132): Remote Branch: 
I/Adreno-EGL( 7132): Local Patches: 
I/Adreno-EGL( 7132): Reconstruct Branch: 
,I/Adreno-EGL( 7132): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7132): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7132): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7132): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7132): Remote Branch: 
I/Adreno-EGL( 7132): Local Patches: 
I/Adreno-EGL( 7132): Reconstruct Branch: 
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  278): PrepareKeyRequest: nonce=124786325
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/NativeCrypto( 1854): SSL shutdown failed: ssl=0x6bed2988: I/O error during system call, Connection timed out
,V/NativeCrypto( 1854): SSL shutdown failed: ssl=0x6bf1f880: I/O error during system call, Connection timed out
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3728): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3728): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3728): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3728): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3728): handleAsyncCustNotification do not startCustService
,D/EAS     ( 7001): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7001): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6423): DownloadService onCreate
,D/eas_req ( 7001): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4254): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 7035): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7035): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7085): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7085): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7102): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7102): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Tethering(  967): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 6423): in removeSpuriousFiles
,V/DownloadManager( 6423): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428edad0 on behalf of 6423
,I/DownloadManager( 6423): in trimDatabase
,V/DownloadManager( 6423): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428eef88 on behalf of 6423
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/CheckinTask( 1854): Sending checkin request (11585 bytes)
,D/dalvikvm(  967): GC_EXPLICIT freed 2038K, 49% free 30745K/59972K, paused 4ms+10ms, total 144ms
,V/DownloadManager( 6423): DownloadService onStartCommand
,V/DownloadManager( 6423): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428f10f8 on behalf of 6423
,V/DownloadManager( 6423): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6423): DownloadService onCreate
,I/DownloadManager( 6423): in removeSpuriousFiles
,V/DownloadManager( 6423): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 7001): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428f52d0 on behalf of 6423
,D/EAS     ( 7001): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6423): DownloadService onStartCommand
,I/DownloadManager( 6423): in trimDatabase
V/DownloadManager( 6423): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6423): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428f76d0 on behalf of 6423
I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4254): networkInfo.isConnected() = true
,D/PhoneState( 4254): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7035): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 7035): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428f89e8 on behalf of 6423
,V/DownloadManager( 6423): DownloadService onDestroy
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 7085): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 7085): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 7102): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 7102): CONNECT : WIFI_CONNECT
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397639845285753; DSPS: 39361891; Offset: 1453396438615702013
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397640045, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397640055, nextTick: 59977, mDrawingTime: 0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3728): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
,I/AppUp4:CustModeStarterReceiver( 3728): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 7001): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6423): DownloadService onCreate
,D/EAS     ( 7001): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4254): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4254): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4254): networkInfo.isConnected() = true
,D/PhoneState( 4254): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 7035): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7035): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2898): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7085): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7085): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7102): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7102): CONNECT : WIFI_CONNECT
,W/Settings( 7001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 6423): in removeSpuriousFiles
,V/DownloadManager( 6423): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428fd028 on behalf of 6423
,D/LGDMClient( 2898): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LGDMClient( 2898): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 6423): in trimDatabase
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 6423): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@428feeb0 on behalf of 6423
V/DownloadManager( 6423): DownloadService onStartCommand
V/DownloadManager( 6423): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6423): created cursor android.database.sqlite.SQLiteCursor@42900be8 on behalf of 6423
E/LGDMClient( 2898): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2898): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2898): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 6423): DownloadService onDestroy
I/LGDMClient( 2898): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1854): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1854): Failed to find provider info for com.google.android.wearable.settings
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x444e0248: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1854): awaiting user notification for token
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1854): Classify the device as Phone.
,D/dalvikvm( 1519): GC_EXPLICIT freed 1344K, 28% free 17966K/24832K, paused 2ms+6ms, total 46ms
,I/CheckinTask( 1854): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1854): Checking schedule, now: 1453397641169 next: 1453975037164
,I/CheckinService( 1854): active receiver: disabled
,I/CheckinService( 1854): Checking schedule, now: 1453397641226 next: 1453975037164
,I/CheckinService( 1854): active receiver: disabled
,D/GCM     ( 1519): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1519): Connected
,I/GAV2    ( 7115): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1519): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ActivityManager(  967): Killing 6910:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): Killing 6385:com.android.vending/u0a50 (adj 15): empty #18
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3994): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3994): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  967): Handling package changes for user 0
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=7318 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 7318): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7318): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7318): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 7318): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 7318): MmsConfig.loadMmsSettings
I/Babel   ( 7318): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 7318): MmsConfig.loadFromDatabase
I/MediaCodecList( 7318): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 7318): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 7318): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 7318): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 7318): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7318): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7318): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7318): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 7318): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7318): MmsConfig.loadFromResources
,E/Babel   ( 7318): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 7318): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 7318): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 7318): [loadRssi] File not exist 
,V/LGRssiData( 7318): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 7318): [loadFeatureFromXml] *** start feature loading from xml
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling( 7318): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7318): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7318): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/AppUp4:Utils( 3728): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3728): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3728): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3728): onReceive
,D/AppUp4:CustFacade( 3728): Context : android.app.ReceiverRestrictedContext@428af208
D/AppUp4:CustFacade( 3728): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3728): isOpenOperator : true
,D/AppUp4:CustFacade( 3728): isPhone : true
,I/LicenseContentProvider( 3032): start selecting data
,D/SIMObserver( 3032): simInfo1
,I/AppUp4:EulaManager( 3728): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3728): begin check event
D/AppUp4:Utils( 3728): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3728): Event For Nothing, skip.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7365 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 7365): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7365): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7365): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,I/SystemConfig( 7365): BUILD Country: EU
,I/SystemConfig( 7365): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 6955:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7381 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/SystemConfig( 7365): systemFeature RCS result false
,D/SystemConfig( 7365): refreshRcsSupport() :false
I/ActivityManager(  967): Killing 6423:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7381): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7381): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7381): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2691): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  967): Killing 7001:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7398 uid=10050 gids={50050, 3003, 1028, 1015}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  276): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+3ms, total 31ms
,D/HyLog   ( 7398): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7398): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7398): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 25ms
,I/dalvikvm( 7398): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 7398): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7398): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm( 1854): GC_CONCURRENT freed 2005K, 22% free 19567K/24832K, paused 4ms+5ms, total 52ms
,D/Finsky  ( 7398): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 7398): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 7398): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7398): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 7398): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7398): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7398): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7398): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 7398): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7398): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7398): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7398): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7398): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7398): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 7398): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7398): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7398): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7398): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7398): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7398): VFY: replacing opcode 0x6e at 0x029a
,I/IcingCorporaProvider( 2691): UpdateCorporaTask done [took 322 ms] updated apps [took 322 ms] 
,I/ActivityManager(  967): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=7433 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 7398): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 7398): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7398): VFY: replacing opcode 0x6e at 0x001a
,D/HyLog   ( 7433): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7433): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7433): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 7398): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 7398): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 7398): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 7398): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7398): [1] 2.run: Finished loading 1 libraries.
,D/dalvikvm(  967): GC_EXPLICIT freed 2199K, 49% free 30817K/59972K, paused 4ms+10ms, total 139ms
,D/PackageBroadcastService( 1854): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1854): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1854): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 7433): DownloadService onCreate
,I/DownloadManager( 7433): in removeSpuriousFiles
,V/DownloadManager( 7433): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7433): created cursor android.database.sqlite.SQLiteCursor@428d5678 on behalf of 7433
,I/DownloadManager( 7433): in trimDatabase
,V/DownloadManager( 7433): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 7433): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7433): created cursor android.database.sqlite.SQLiteCursor@428d9848 on behalf of 7433
,V/DownloadManager( 7433): DownloadService onStartCommand
,V/DownloadManager( 7433): created cursor android.database.sqlite.SQLiteCursor@428dd3a8 on behalf of 7398
,V/DownloadManager( 7433): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7433): created cursor android.database.sqlite.SQLiteCursor@428df980 on behalf of 7433
,D/Finsky  ( 7398): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 7433): DownloadService onDestroy
,D/Finsky  ( 7398): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  967): Killing 7035:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7398): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7398): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7398): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7398): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7398): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7398): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 7398): Total arena pages for JIT: 11
,I/dalvikvm( 7398): Total arena pages for JIT: 12
,I/dalvikvm( 7398): Total arena pages for JIT: 13
,I/dalvikvm( 7398): Total arena pages for JIT: 14
,I/GLSUser ( 1519): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1519): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1519): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1519): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1519): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1519): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7398): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7398): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7398): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/Finsky  ( 7398): [1] DailyHygiene.reschedule: Scheduling new run in 867 minutes (failures=5)
D/libc    (  272): _dns_getaddrinfo: iptype =1
,D/libc    (  272): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
,I/GAV4    ( 7318): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  967): Killing 7058:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42df7c80 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397659846678034; DSPS: 40017296; Offset: 1453396438615721003
,D/Finsky  ( 7398): [555] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7398): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397679847616295; DSPS: 40672687; Offset: 1453396438615713219
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397699848958108; DSPS: 41328091; Offset: 1453396438615712259
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397700039, nextTick: 59966, mDrawingTime: 12
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397700055, nextTick: 59977, mDrawingTime: 0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397719849851828; DSPS: 41983480; Offset: 1453396438615720969
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397739851942749; DSPS: 42638909; Offset: 1453396438615706177
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453397759852839365; DSPS: 43294298; Offset: 1453396438615717783
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397760041, nextTick: 59965, mDrawingTime: 13
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1453397760057, nextTick: 59976, mDrawingTime: 0
,TIME-OUT KILL (timeout was 1200000ms)
```
