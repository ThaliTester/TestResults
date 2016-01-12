#### Test 55742142a5c2fdb_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1966): Using Auth Proxy for data requests.
,W/GAV2    ( 4551): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  961): Killing 4008:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1554): GC_EXPLICIT freed 1200K, 29% free 17831K/24832K, paused 2ms+6ms, total 42ms
D/dalvikvm( 1966): GC_CONCURRENT freed 1587K, 22% free 19455K/24832K, paused 3ms+3ms, total 37ms
I/ConfigFetchService( 1966): fetch service done; releasing wakelock
I/ConfigFetchService( 1966): stopping self
D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1966): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4595): 
D/AndroidRuntime( 4595): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4595): CheckJNI is OFF
D/dalvikvm( 4595): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4595): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4595): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4595): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4595): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4595): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1966): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1966): Loaded CLD2 Version V2.0 - 20141016
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Icing   ( 1966): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4595): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4595): failed to load memtrack module: -2
D/AndroidRuntime( 4595): Calling main entry com.android.commands.am.Am
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4595
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1789 us)
D/ActivityManager(  961): resumeTopActivityLocked: Pausing null
V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  961): startService SlideAside
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  961): setFocusedStack: mFocusedStack=ActivityStack{42baf630 stackId=1, 2 tasks}
D/UsbSettingsControl( 2571): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2571): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4595): Shutting down VM
I/SlideAside( 3744): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4595): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Restarting ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  961): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4613 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3744): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3744): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4613): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4613): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4613): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
V/WebViewChromium( 4613): Binding Chromium to the background looper Looper (main, tid 1) {42834338}
I/chromium( 4613): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4613): Initializing chromium process, renderers=0
W/chromium( 4613): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4613): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4613): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4613): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4613): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4613): Remote Branch: 
I/Adreno-EGL( 4613): Local Patches: 
I/Adreno-EGL( 4613): Reconstruct Branch: 
I/dalvikvm( 4613): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4613): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4613): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4613): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4613): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4613): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4613): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4613): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4613): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4613): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4613): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4613): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4613): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4613): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4613): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4613): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4613): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4613): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4613): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4613): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4613): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4613): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4613): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4613): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OpenGLRenderer( 4613): Enabling debug mode 0
W/AwContents( 4613): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  961): Displayed com.test.thalitest/.MainActivity: +424ms
I/InputMethodManagerService(  961): IME STATUS OFF
W/AwContents( 4613): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 4613): Timeline: Activity_idle id: android.os.BinderProxy@42835a18 time:108138
D/JsMessageQueue( 4613): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4613): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42839af8
D/dalvikvm( 4613): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42839af8
D/jxcore_app_log( 4613): JniHelper::setJavaVM(0x416f9838), pthread_self() = 1638793224
D/JX-Cordova( 4613): jxcore cordova android initializing
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3} time:108467
D/ActivityManager(  961): no-history finish of ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  961): Finishing activity token=Token{42afb568 ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2571): [AUTORUN] onStop()
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/dalvikvm( 4613): GC_CONCURRENT freed 2754K, 12% free 21898K/24832K, paused 2ms+1ms, total 42ms
,D/dalvikvm( 4613): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4613): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 166K, 12% free 21879K/24832K, paused 23ms, total 23ms
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 131K, 12% free 21895K/24832K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 23.647MB for 96598-byte allocation
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 181K, 13% free 21929K/24928K, paused 37ms, total 38ms
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 23.727MB for 144892-byte allocation
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 254K, 13% free 21977K/25072K, paused 38ms, total 38ms
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 23.842MB for 217334-byte allocation
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4613): GC_FOR_ALLOC freed 370K, 13% free 22051K/25288K, paused 24ms, total 24ms
I/dalvikvm-heap( 4613): Grow heap (frag case) to 24.019MB for 325996-byte allocation
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 570K, 14% free 22173K/25608K, paused 23ms, total 23ms
I/dalvikvm-heap( 4613): Grow heap (frag case) to 24.293MB for 488990-byte allocation
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 868K, 15% free 22350K/26088K, paused 23ms, total 23ms
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 1289K, 14% free 22607K/26088K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 25.300MB for 1100216-byte allocation
,D/dalvikvm( 4613): GC_CONCURRENT freed 1757K, 16% free 22992K/27164K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 305K, 16% free 22928K/27164K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 26.137MB for 1650320-byte allocation
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2055): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/dalvikvm( 4613): GC_CONCURRENT freed 1971K, 18% free 23620K/28776K, paused 1ms+7ms, total 60ms
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 1076K, 19% free 23545K/28776K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 27.528MB for 2475476-byte allocation
,D/dalvikvm( 4613): GC_CONCURRENT freed 2171K, 23% free 24327K/31196K, paused 2ms+5ms, total 74ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4613): GC_CONCURRENT freed 2419K, 22% free 24530K/31196K, paused 1ms+4ms, total 37ms
,D/dalvikvm( 4613): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4613): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 100K, 22% free 24515K/31196K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 29.655MB for 3713210-byte allocation
,D/dalvikvm( 4613): GC_CONCURRENT freed 2833K, 27% free 25521K/34824K, paused 1ms+2ms, total 36ms
,D/dalvikvm( 4613): GC_FOR_ALLOC freed 704K, 27% free 25523K/34824K, paused 24ms, total 25ms
,W/jxcore-log( 4613): Initializing JXcore engine
,W/jxcore-log( 4613): JXcore engine is ready
,D/dalvikvm( 4613): GC_CONCURRENT freed 368K, 20% free 28151K/34824K, paused 1ms+1ms, total 26ms
,D/dalvikvm( 4613): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4613): Starting JXcore engine
,W/jxcore-log( 4613): Platform android
W/jxcore-log( 4613): 
,W/jxcore-log( 4613): Process ARCH arm
W/jxcore-log( 4613): 
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/jxcore-log( 4613): JXcore Cordova bridge is ready!
I/jxcore-log( 4613): 
W/jxcore-log( 4613): JXcore engine is started
I/chromium( 4613): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/chromium( 4613): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4613): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV2    ( 4551): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.460800 Y: -0.416412 Z: 9.819809 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460800 .y:-0.416412 .z:9.819809
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.456619 Y: -0.419907 Z: 9.807816 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456619 .y:-0.419907 .z:9.807816
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/ConfigService( 1554): onDestroy
,I/jxcore-log( 4613): Toggling radios to true
I/jxcore-log( 4613): 
,D/BluetoothManagerService(  961): Message: 20
,D/BluetoothManagerService(  961): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44dcc310:true
,D/BluetoothAdapter( 4613): enable(): BT is already enabled..!
D/WifiService(  961): New client listening to asynchronous messages
,D/WifiStateMachine(  961): handleMessage: E msg.what=131145
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doBoolean: DISCONNECT
,I/jxcore-log( 4613): Radios toggled
I/jxcore-log( 4613): 
,D/BluetoothManagerService(  961): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2055): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2055): wlan0: Cancelling scan request
D/wpa_supplicant( 2055): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2055): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2055): TDLS: Tear down peers
D/wpa_supplicant( 2055): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  961): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4613): Received device characteristics:
I/jxcore-log( 4613): Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4613): Bluetooth name: Thali Test's G2
I/jxcore-log( 4613): Device name: LGE-LG-D802
I/jxcore-log( 4613): 
I/jxcore-log( 4613): Perf Test app loaded loaded
I/jxcore-log( 4613): 
D/WifiService(  961): setWifiEnabled: true pid=4613, uid=10304
E/WifiService(  961): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  961): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  961): disconnect pid=4613, uid=10304
D/WifiService(  961): reconnect pid=4613, uid=10304
I/chromium( 4613): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Choreographer( 4613): Skipped 77 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2055): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2055): wlan0: Deauthentication notification
D/wpa_supplicant( 2055): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2055): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2055): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2055): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2055): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2055): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb70cbd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2055):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2055): netlink: Operstate: linkmode=-1, operstate=5
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2055): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2055): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2055): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2055): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2055): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2055): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2055): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2055): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2055): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2055): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2055): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2055): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2055): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2055): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2055): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2055): nl80211: Event message available
D/wpa_supplicant( 2055): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 2055): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  961): invokeExitMethods: ConnectedState
W/Settings(  961): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  961): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  961): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131146
D/WifiStateMachine(  961): processMsg: DisconnectingState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiNative-wlan0(  961): doBoolean: RECONNECT
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2055): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2055): Fast associate: Old scan results
D/wpa_supplicant( 2055): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2055): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2055): wlan0: nl80211: scan request
D/wpa_supplicant( 2055): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147460
D/WifiStateMachine(  961): processMsg: DisconnectingState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): Network connection lost
D/wpa_supplicant( 2055): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2055): nl80211: Event message available
D/wpa_supplicant( 2055): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2055): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  961): Stopping DHCP and clearing IP
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  961): doBoolean: SET ps 1
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2055): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2055): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2055): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2055): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2055): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  961):    returned true
,I/jxcore-log( 4613): check test folder
I/jxcore-log( 4613): 
D/DhcpStateMachine(  961): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4613): found test : ./testFindPeers.js
I/jxcore-log( 4613): 
D/WifiP2pService(  961): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  270): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  961): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  961): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  961): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,I/jxcore-log( 4613): found test : ./testSendData.js
I/jxcore-log( 4613): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
,E/Parcel  (  568): Reading a NULL string not supported here.
D/QCNEA   (  568): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  568): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  568): |CAC| updateNetCfgInfo
V/QCNEA   (  568): |CAC| *********************************************
V/QCNEA   (  568): |CAC|                   Netconfig               
V/QCNEA   (  568): |CAC| *********************************************
V/QCNEA   (  568): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  568): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  568): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  568): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  568): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  568): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  568): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  568): |CAC| *********************************************
D/QCNEA   (  568): |CAC| Received bssid= 
D/QCNEA   (  568): |CAC| net type = 3
V/QCNEA   (  568): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  568): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  568): |CAC| 	ssid           =NG700
V/QCNEA   (  568): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  568): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  568): |CAC| *********************************************
D/QCNEA   (  568): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  568): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  568): |CAC| dispatchNetCfg: updating:0xb77628dc
,D/QCNEA   (  568): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  568): Reading a NULL string not supported here.
,E/Parcel  (  568): Reading a NULL string not supported here.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  961): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  961): invokeExitMethods: DisconnectingState
,D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
D/WifiHS20(  961): hidePasspointNotification off =false
D/QcConnectivityService(  961): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  961): Attempting to switch to mobile
D/QcConnectivityService(  961): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  961): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  961): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131213
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131213
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  270): RouteController
I/ActivityManager(  961): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4663 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,D/HyLog   ( 4663): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4663): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4663): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  270): RouteController
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PCSuite ( 4663): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  270): RouteController
,V/        (  270): RouteController
,D/PCSuite ( 4663): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4663): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  270): RouteController
,W/NetworkManagementService(  961): route cmd failed: 
W/NetworkManagementService(  961): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  961): '
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  961): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  961): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  961): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  961): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  961): android_net_utils_resetConnections in env=0x6284c290 clazz=0x6db00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  961): resetConnections(wlan0, 3)
I/ActivityManager(  961): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4701 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  961): Killing 4084:com.google.android.talk/u0a77 (adj 15): empty #17
,V/NativeCrypto( 1554): Read error: ssl=0x63a9b180: I/O error during system call, Connection timed out
,V/NativeCrypto( 1554): SSL shutdown failed: ssl=0x63a9b180: I/O error during system call, Broken pipe
,D/HyLog   ( 4701): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4701): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4701): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4701): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
D/QRemote ( 4701): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4701): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4701): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4701): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/GpsLocationProvider(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 4701): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QRemote ( 4701): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4701): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4701): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  961): Killing 3074:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  961): StoppedState
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3757): onReceive
,D/wpa_supplicant( 2055): nl80211: Event message available
D/wpa_supplicant( 2055): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2055): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2055): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2055): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 2055): nl80211: Survey data missing
D/wpa_supplicant( 2055): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2055): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Add new id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Add new id 7 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Add new id 8 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Add new id 9 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear'
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Add new id 10 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series'
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 2055): wlan0: New scan results available
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2055): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2055): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2055): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2055): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2055): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2055): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2055): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2055): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2055): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2055): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2055): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2055): WPS: AP[3] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2055): WPS: AP[4] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2055): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2055): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2055): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2055): wlan0:    skip - SSI,D mismatch
D/wpa_supplicant( 2055): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53
D/wpa_supplicant( 2055): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2055): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2055): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2055): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2055): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2055): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2055): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2055): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2055): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2055): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2055): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb70cd5a8  current_ssid=0x0
D/wpa_supplicant( 2055): scard is not null..
D/wpa_supplicant( 2055): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2055): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2055): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2055): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2055): wpa_supplicant_check_mdm_ac_policy policy: 0,
,D/wpa_supplicant( 2055): wlan0: [MDM] lg mdm allow/disallow auto connect is not set ,
D/wpa_supplicant( 2055): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2055): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2055): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2055): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2055): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2055): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2055): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2055): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2055): wlan0: Cancelling scan request
D/wpa_supplicant( 2055): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2055): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 2055): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2055): RSN: PMKSA cache search - network_ctx=0xb70cd5a8 try_opportunistic=0
D/wpa_supplicant( 2055): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2055): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2055): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2055): wlan0: WPA: clearing AP WPA IE,
D/wpa_supplicant( 2055): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2055): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2055): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2055): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2055): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2055): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2055): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2055): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2055): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2055): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2055): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2055): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2055): nl80211: Unsubscribe mgmt frames handle 0xb70cc590 (mode change)
D/wpa_supplicant( 2055): nl80211: Subscribe to mgmt frames with non-AP handle 0xb70cc590
,D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
,D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09,
D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=2): 04 0e
,D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590,
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2055): nl80211: Register frame type=0xd0 nl_handle=0xb70cc590
D/wpa_supplicant( 2055): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2055): nl80211: Connect (ifindex=23),
D/wpa_supplicant( 2055):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055):   * freq=2412,
D/wpa_supplicant( 2055):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2055):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2055):   * Auth Type 0,
D/wpa_supplicant( 2055):   * WPA Versions 0x2,
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48],
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:97]
D/wpa_supplicant( 2055): nl80211: Connect request send successfully
D/wpa_supplicant( 2055): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2055): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2055): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2055): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2055): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2055): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2055): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 a0:c5:62:7a:49:96]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 44:e9:dd:10:c0:ac]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 00:26:f2:18:08:c8]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 dc:4a:3e:0f:c2:f1],
,D/WifiStateMachine(  961): handleMessage: E msg.what=147461,
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  961): processMsg: SupplicantStartedState,
D/WifiNative-wlan0(  961): doString: BSS RANGE=0- MASK=0x21987,
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2055): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2055): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2055): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2055): WPS: Unknown Vendor Extension (Vendor ID 311),
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ],
W/WifiMonitor(  961): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/wpa_supplicant( 2055): nl80211: Event message available
D/wpa_supplicant( 2055): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2055): nl80211: Connect event
D/wpa_supplicant( 2055): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2055): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2055): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2055): wlan0: Association info event
D/wpa_supplicant( 2055): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2055): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2055): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2055): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2055): wlan0: freq=2412 MHz
D/wpa_supplicant( 2055): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2055): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2055): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2055): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2055): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2055): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): scard is not null..
D/wpa_supplicant( 2055): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2055): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2055): TDLS: Remove peers on association
D/wpa_supplicant( 2055): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2055): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2055): EAPOL: enable timer tick
D/wpa_supplicant( 2055): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2055): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2055): wlan0: Cancelling scan request
,D/wpa_supplicant( 2055): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2055): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2055): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2055): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2055): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2055): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2055): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2055): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2055): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
,D/wpa_supplicant( 2055): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700],
D/WifiMonitor(  961): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  961): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/AppUp4:CustFacade( 3757): Context : android.app.ReceiverRestrictedContext@42847fb8
D/wpa_supplicant( 2055): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 03 62 97 c4 7c 47 93 38 39 ab 50 ed 18 59 f9 ...
D/wpa_supplicant( 2055): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2055): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2055): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2055): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2055): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2055):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2055):   key_nonce - hexdump(len=32): 03 62 97 c4 7c 47 93 38 39 ab 50 ed 18 59 f9 0d de ac 6f 38 2e 68 f4 09 60 69 16 2d 05 bb ff 53
D/wpa_supplicant( 2055):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2055):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2055):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2055):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2055): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 03 62 97 c4 7c 47 93 38 39 ab 50 ed 18 59 f9 ...
D/wpa_supplicant( 2055): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2055): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2055): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2055): WPA: Renewed SNonce - hexdump(len=32): 63 f4 f5 35 93 e7 a8 1a ae 51 13 95 7b 1e 1f 5a 18 d4 9f 24 10 7d 80 80 d2 c8 28 09 7e 58 58 aa
D/wpa_supplicant( 2055): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): WPA: Nonce1 - hexdump(len=32): 63 f4 f5 35 93 e7 a8 1a ae 51 13 95 7b 1e 1f 5a 18 d4 9f 24 10 7d 80 80 d2 c8 28 09 7e 58 58 aa
D/wpa_supplicant( 2055): WPA: Nonce2 - hexdump(len=32): 03 62 97 c4 7c 47 93 38 39 ab 50 ed 18 59 f9 0d de ac 6f 38 2e 68 f4 09 60 69 16 2d 05 bb ff 53
D/wpa_supplicant( 2055): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2055): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2055): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2055): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2055): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2055): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2055): WPA: Derived Key MIC - hexdump(len=16): be dc 89 0c 13 3f 5d 1c d1 0a 51 3b 7e 49 93 b0
,D/wpa_supplicant( 2055): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 63 f4 f5 35 93 e7 a8 1a ae 51 13 95 7b 1e 1f ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/AppUp4:CustFacade( 3757): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3757): isOpenOperator : true
,D/AppUp4:CustFacade( 3757): isPhone : true
D/wpa_supplicant( 2055): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 03 62 97 c4 7c 47 93 38 39 ab 50 ed 18 59 f9 ...
D/wpa_supplicant( 2055): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
,D/wpa_supplicant( 2055): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2055): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2055): wlan0:   key_length=16 key_data_length=56
,D/wpa_supplicant( 2055):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2055):   key_nonce - hexdump(len=32): 03 62 97 c4 7c 47 93 38 39 ab 50 ed 18 59 f9 0d de ac 6f 38 2e 68 f4 09 60 69 16 2d 05 bb ff 53
D/wpa_supplicant( 2055):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2055):   key_rsc - hexdump(len=8): 65 04 00 00 00 00 00 00
D/wpa_supplicant( 2055):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2055):   key_mic - hexdump(len=16): db 59 79 84 1a e7 86 19 9d 36 4b 69 45 78 8a f5
,D/wpa_supplicant( 2055): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 03 62 97 c4 7c 47 93 38 39 ab 50 ed 18 59 f9 ...
D/wpa_supplicant( 2055): RSN: encrypted key data - hexdump(len=56): 01 5c e6 0d f0 85 8c 2e bf b3 fd a0 a0 e4 d2 5b 60 fe 9f 04 45 7d 90 a7 e4 ad 2e f4 1e 7d 4c ee ...
D/wpa_supplicant( 2055): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2055): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2055): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2055): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 ae 75 ...
D/wpa_supplicant( 2055): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2055): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2055): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2055): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2055): WPA: Derived Key MIC - hexdump(len=16): b2 26 e2 17 13 06 cf 7e b2 0f ce 8e a6 e2 04 43,
D/wpa_supplicant( 2055): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2055): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb70ccc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2055):    addr=c0:ff:d4:d3:aa:48
I/LicenseContentProvider( 2958): start selecting data
D/SIMObserver( 2958): simInfo1
D/wpa_supplicant( 2055): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2055): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2055): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2055): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2055): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2055): WPA: RSC - hexdump(len=6): 65 04 00 00 00 00
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ec803a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2055):    broadcast key
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2055): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: Cancelling authentication timeout
,D/wpa_supplicant( 2055): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2055): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2055): netlink: Operstate: linkmode=-1, operstate=6
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2055): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2055): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2055): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2055): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2055): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2055): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2055): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2055): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2055): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2055): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2055): EAPOL authentication completed successfully
,D/wpa_supplicant( 2055): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2055): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2055): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  961): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/AppUp4:EulaManager( 3757): getAgreementForKK : Eula agreement is false
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/AppUp4:CustModeStarterReceiver( 3757): begin check event
I/AppUp4:CustModeStarterReceiver( 3757): Event For GoodConnectivity
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
,D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
,D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): Network connection established
,D/WifiNative-wlan0(  961): doString: STATUS
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2055): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  961):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  961): ssid=NG700
D/WifiNative-wlan0(  961): id=0
D/WifiNative-wlan0(  961): mode=station
D/WifiNative-wlan0(  961): pairwise_cipher=CCMP
D/WifiNative-wlan0(  961): group_cipher=CCMP
D/WifiNative-wlan0(  961): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  961): wpa_state=COMPLETED
D/WifiNative-wlan0(  961): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  961): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  961): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  961): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine(  961): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  961): invokeExitMethods: DisconnectedState
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  961): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  961): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  961): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  961): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  961): WaitBeforeStartState
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-21ms what=147462 obj=android.net.wifi.StateChangeResult@443b9868 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
,E/Parcel  (  568): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/ActivityManager(  961): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4745 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-22ms what=147462 obj=android.net.wifi.StateChangeResult@44ee8bf0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-23ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-10ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2055): nl80211: survey data missing!
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=196612
,D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-11ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2055): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/dalvikvm(  274): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/HyLog   ( 4745): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4745): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4745): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 14ms
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  961): battery changed pluggedType: 2
,V/DownloadManager( 4745): DownloadService onCreate
,D/EAS     ( 4532): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4532): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4745): in removeSpuriousFiles
,D/eas_req ( 4532): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4745): DownloadService onStartCommand
,V/DownloadManager( 4745): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4252): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@4287b090 on behalf of 4745
,I/LgeMiscReceiver( 4252): networkInfo.isConnected() = false
,V/DownloadManager( 4745): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4745): in trimDatabase
,V/DownloadManager( 4745): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/wpa_supplicant( 2055): wpa_driver_nl80211_driver_cmd OK len = 0, 2
V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@4287dbd8 on behalf of 4745
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 false
V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@4287e168 on behalf of 4745
,D/WifiNative-wlan0(  961): doBoolean: SET ps 0
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2055): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2055): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2055): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2055): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2055): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  961):    returned null
E/WifiStateMachine(  961): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2055): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2055): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  961):    returned null
E/WifiStateMachine(  961): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  961): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  961): DHCP Start wake lock is acquired.
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431209e0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@431209e0 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring up wlan0
,D/WifiStateMachine(  961): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  961): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  961): handleMessage: X
W/linker  ( 4532): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/WifiStateMachine(  961): handleMessage: E msg.what=131212
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=196613
D/WifiStateMachine(  961): processMsg: ObtainingIpState
,D/HtmlEditor( 4532): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4532): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4532): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
D/WifiStateMachine(  961): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  961): doBoolean: SET ps 1
,I/dalvikvm( 4532): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,I/ActivityManager(  961): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4770 uid=10052 gids={50052, 3003}
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2055): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2055): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2055): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/HtmlEditor( 4532): register_HtmlEditor, Success
D/HtmlEditor( 4532): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/HtmlEditor( 4532): register_HtmlEditorTimer, Success
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2055): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/HtmlEditor( 4532): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
,V/DownloadManager( 4745): DownloadService onDestroy
D/wpa_supplicant( 2055): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/HtmlEditor( 4532): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4532): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4532): register_HtmlEditorFont, Success
D/HtmlEditor( 4532): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): DHCP successful
,D/HtmlEditor( 4532): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4532): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  961): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
,D/HtmlEditor( 4532): register_HtmlEditorDrawImage, Success
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/HtmlEditor( 4532): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  961): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  961): VerifyingLinkState enter
D/WifiStateMachine(  961): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/HtmlEditor( 4532): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4532): JNI_OnLoad Success
D/WifiStateMachine(  961): handleMessage: X
D/HyLog   ( 4770): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4770): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4770): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/HubEmail( 4532): JNI_OnLoad()
I/HubEmail( 4532): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4532): registerNatives()
I/HubEmail( 4532): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4532): registerNativeMethods()
,I/HubEmail( 4532): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  961): send additional Connectivity Action
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
E/Parcel  (  568): Reading a NULL string not supported here.
,E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
D/WifiStateMachine(  961): handleMessage: E msg.what=135190
D/WifiStateMachine(  961): processMsg: VerifyingLinkState
D/WifiStateMachine(  961): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  961): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  961): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  961): CaptivePortalCheckState enter
D/WifiStateMachine(  961): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  961): handleMessage: X
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  961): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  961): 
W/WifiStateTracker(  961):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  961):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  961): handleMessage: E msg.what=131092
D/WifiStateMachine(  961): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  961): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/WifiStateMachine(  961): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  961): transitionTo: destState=ConnectedState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  961): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,W/Settings( 4532): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  961): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  568): Reading a NULL string not supported here.
E/ActivityThread(  961): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  961): handleConnectivityChange: preConnState=2 connState=1
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  270): RouteController
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
V/LGRssiData( 4770): [loadRssi] File not exist 
,V/LGRssiData( 4770): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4770): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4770): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,W/BaseRuntimeLoader( 4770): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4770): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4770): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4770): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4770): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4770): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  270): RouteController
,D/MobileConnectivityChangeReceiver( 4770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4770): onReceive CONNECTIVITY_CHANGE networkType=1
,V/        (  270): RouteController
,I/ActivityManager(  961): Killing 3910:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
V/        (  270): RouteController
,V/        (  270): RouteController
I/ActivityManager(  961): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4790 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  961): Killing 4289:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
E/PhoneMonitor( 4770): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4770): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  270): RouteController
D/HyLog   ( 4790): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4790): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4790): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
I/CheckinService( 1966): Checking schedule, now: 1452601006977 next: 1452600951886
,I/CheckinService( 1966): active receiver: enabled
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1452600918987
D/QCNEA   (  568): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  568): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  568): |CAC| updateNetCfgInfo
V/QCNEA   (  568): |CAC| *********************************************
V/QCNEA   (  568): |CAC|                   Netconfig               
V/QCNEA   (  568): |CAC| *********************************************
V/QCNEA   (  568): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  568): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  568): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  568): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  568): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  568): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  568): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  568): |CAC| *********************************************
D/QCNEA   (  568): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  568): |CAC| net type = 1
V/QCNEA   (  568): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  568): |CAC| Received ssid= NG700
V/QCNEA   (  568): |CAC| 	ssid           =NG700
V/QCNEA   (  568): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  568): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  568): |CAC| *********************************************
D/QCNEA   (  568): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  568): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  568): |CAC| dispatchNetCfg: updating:0xb77628dc
,D/QCNEA   (  568): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
,D/DhcpStateMachine(  961): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  961): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  961): GC_EXPLICIT freed 23488K, 49% free 29779K/57924K, paused 2ms+8ms, total 126ms
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  961): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4822 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  961): Killing 4460:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/HyLog   ( 4822): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4822): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4822): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
,D/LGDMClient( 2835): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2835): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2835): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  961): Killing 4492:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  961): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4836 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
,E/LGDMClient( 2835): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2835): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2835): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2835): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4836): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4836): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4836): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4836): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  961): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4850 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  961): Killing 4519:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4850): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4850): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4850): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 4850): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4850): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4850): intf.getDisplayName() = lo
I/Wireless_Storage( 4850): intf.getDisplayName() = sit0
I/Wireless_Storage( 4850): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4850): intf.getDisplayName() = teql0
I/Wireless_Storage( 4850): intf.getDisplayName() = wlan0
,D/NFS     ( 4850): interface name:wlan0 name:wlan0
D/NFS     ( 4850): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4850): interface name:wlan0 name:wlan0
D/NFS     ( 4850): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4850): CONNECT : WIFI_CONNECT
,I/ActivityManager(  961): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4862 uid=10104 gids={50104, 3003, 1028, 1015}
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  961): Killing 4135:com.android.contacts/u0a21 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4862): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4862): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4862): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x431751f8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GAV2    ( 4862): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  961): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4879 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4879): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4879): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4879): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4879): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4879): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4879): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4879): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4879): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4879): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4879): install
,I/MultiDex( 4879): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4879): loading existing secondary dex files
,I/MultiDex( 4879): load found 3 secondary dex files
,I/MultiDex( 4879): install done
,D/dalvikvm( 4879): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4879): VFY: unable to resolve instance field 61
,D/dalvikvm( 4879): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4879): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4879): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4879): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4879): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4879): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4879): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4879): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4879): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4879): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428392d8
D/dalvikvm( 4879): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428392d8
,D/dalvikvm( 4879): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428392d8, skipping init
,D/dalvikvm( 4879): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428392d8
D/dalvikvm( 4879): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428392d8
,V/JNIHelp ( 4879): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4879): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428392d8
,D/dalvikvm( 4879): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428392d8
D/dalvikvm( 4879): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428392d8
,D/dalvikvm( 4879): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428392d8
,V/WebViewChromium( 4862): Binding Chromium to the main looper Looper (main, tid 1) {42831cf0}
,I/chromium( 4862): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4862): Initializing chromium process, renderers=0
,W/chromium( 4862): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4862): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4862): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4862): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4862): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4862): Remote Branch: 
I/Adreno-EGL( 4862): Local Patches: 
I/Adreno-EGL( 4862): Reconstruct Branch: 
,I/NSApplication( 4862): Starting up...
,I/ActivityManager(  961): Killing 4152:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4701): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4701): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/ProviderInstaller( 4879): Installed default security provider GmsCore_OpenSSL
,D/QRemote ( 4701): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4701): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4701): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4701): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4663): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4663): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4701): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4701): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4701): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4701): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1554): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1554): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/dalvikvm( 4879): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4879): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4879): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4879): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4879): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4879): VFY: replacing opcode 0x6e at 0x0201
,D/WearableService( 1874): callingUid 10006, callindPid: 1874
,D/LocationInitializer( 1966): Restart initialization of location
,E/MDM     ( 1423): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2053000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2053000
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
D/wpa_supplicant( 2055): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2055): EAPOL: disable timer tick
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=418994161
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4879): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a57008
,D/dalvikvm( 4879): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a57008
,D/dalvikvm( 4879): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a57008, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  961): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  276): PrepareKeyRequest: nonce=3831787661
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,W/Settings( 4879): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4879): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/dalvikvm( 4923): DexOpt: load 4ms, verify+opt 3ms, 128132 bytes
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4879): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4879): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 4879): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4879): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4879): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4879): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4879): Remote Branch: 
I/Adreno-EGL( 4879): Local Patches: 
I/Adreno-EGL( 4879): Reconstruct Branch: 
,I/Adreno-EGL( 4879): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4879): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4879): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4879): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4879): Remote Branch: 
I/Adreno-EGL( 4879): Local Patches: 
I/Adreno-EGL( 4879): Reconstruct Branch: 
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/dalvikvm( 4613): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4613): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4613): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4613): Shutting down VM
,W/dalvikvm( 4613): threadid=1: thread exiting with uncaught exception (group=0x417f4e48)
E/AndroidRuntime( 4613): FATAL EXCEPTION: main
E/AndroidRuntime( 4613): Process: com.test.thalitest, PID: 4613
E/AndroidRuntime( 4613): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4613): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4613): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4613): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4613): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4613): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4613): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4613): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4613): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4613): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4613): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4613): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4613): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4613): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4613): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4613): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4613): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4613): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4613): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  961):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3 f}
,D/WifiStateMachine(  961): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  961): handleMessage: E msg.what=131212
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  961): processMsg: SupplicantStartedState
,D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  961): handleMessage: X
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  961): send additional Connectivity Action
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  961): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  961):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  961): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,D/DhcpStateMachine(  961): DHCP succeeded on wlan0
D/LgDhcpStateMachineHelper(  961): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  961): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  961): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  961): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  961): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  961): RunningState
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/GCM     ( 1554): Connected
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/GCM     ( 1554): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Adreno-EGL( 4879): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4879): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4879): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4879): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4879): Remote Branch: 
I/Adreno-EGL( 4879): Local Patches: 
I/Adreno-EGL( 4879): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1966): Sending checkin request (11621 bytes)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  961): Activity pause timeout for ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42baf630 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  961): moveHomeStack:
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
,V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  961): resumeTopActivityLocked: Resumed ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WeatherAncestor( 1838): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:16:49
,D/UpdateThreadPoolManager( 1838): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1838): 2 : quick cover state : opened : 0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1838): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1838): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1838): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1838): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1838): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1838): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:16:49
D/WeatherService( 1838): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1838): 2 : quick cover state : opened : 0
D/Weather.Utils( 1838): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1838): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1838): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1838): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1838): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1838): 2 : This is isUpdating : false
D/WeatherService( 1838): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1838): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1838): 2 : Map key string is -2
D/lim     ( 1838): 2 : time = 13:16
I/WeatherReflect( 1838): Model Name : LG-D802
D/WeatherTheme( 1838): 2 : Different view - status_min_formatted : 15 != 16
D/WeatherTheme( 1838): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1838): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1838): 2 : Fixed theme : optimus
D/WeatherTheme( 1838): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1838): 2 : quick cover state : opened : 0
D/Weather.Utils( 1838): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1838): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1838): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/WifiController(  961): battery changed pluggedType: 2
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1488): GC_CONCURRENT freed 5420K, 9% free 60847K/66464K, paused 1ms+5ms, total 27ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 6104K, 10% free 71529K/78608K, paused 29ms, total 29ms
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
,D/dalvikvm( 1488): GC_FOR_ALLOC freed 5016K, 9% free 61984K/67852K, paused 21ms, total 21ms
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@42832338 time:118516
,D/dalvikvm(  961): GC_CONCURRENT freed 2244K, 47% free 30870K/57924K, paused 3ms+5ms, total 119ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 108ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 65ms
,I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1} time:118554
,I/CheckinService( 1966): Checking schedule, now: 1452601009565 next: 1453178405487
,I/CheckinService( 1966): active receiver: disabled
D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x44eb4b88: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
D/UsbSettings( 2571): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2571): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2571): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2571): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{4307da70 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2055): nl80211: survey data missing!
D/WifiStateMachine(  961): handleMessage: X
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3757): onReceive
,D/AppUp4:CustFacade( 3757): Context : android.app.ReceiverRestrictedContext@42847fb8
D/AppUp4:CustFacade( 3757): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3757): isOpenOperator : true
,D/AppUp4:CustFacade( 3757): isPhone : true
,I/LicenseContentProvider( 2958): start selecting data
,D/SIMObserver( 2958): simInfo1
,I/AppUp4:EulaManager( 3757): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3757): begin check event
,I/AppUp4:CustModeStarterReceiver( 3757): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3757): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3757): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3757): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3757): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3757): handleAsyncCustNotification do not startCustService
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/EAS     ( 4532): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4745): DownloadService onCreate
,D/EAS     ( 4532): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4532): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4252): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4252): networkInfo.isConnected() = false
,I/DownloadManager( 4745): in removeSpuriousFiles
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4745): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@42884520 on behalf of 4745
D/MobileConnectivityChangeReceiver( 4770): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4532): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 4745): in trimDatabase
V/DownloadManager( 4745): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4745): DownloadService onStartCommand
V/DownloadManager( 4745): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2835): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@42887c20 on behalf of 4745
V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@42886798 on behalf of 4745
,D/LGDMSGCM( 4836): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2835): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2835): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4850): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4850): CONNECT : WIFI_CONNECT
,V/DownloadManager( 4745): DownloadService onDestroy
,E/LGDMClient( 2835): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2835): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2835): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 4836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2835): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 3757): onReceive
D/AppUp4:CustFacade( 3757): Context : android.app.ReceiverRestrictedContext@42847fb8
D/AppUp4:CustFacade( 3757): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3757): isOpenOperator : true
D/AppUp4:CustFacade( 3757): isPhone : true
I/LicenseContentProvider( 2958): start selecting data
D/SIMObserver( 2958): simInfo1
I/AppUp4:EulaManager( 3757): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3757): begin check event
,I/AppUp4:CustModeStarterReceiver( 3757): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4745): DownloadService onCreate
,I/DownloadManager( 4745): in removeSpuriousFiles
D/EAS     ( 4532): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4532): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4745): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@4288c7e8 on behalf of 4745
,V/DownloadManager( 4745): DownloadService onStartCommand
I/DownloadManager( 4745): in trimDatabase
V/DownloadManager( 4745): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4745): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@4288e1b0 on behalf of 4745
I/LgeMiscReceiver( 4252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4252): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4252): networkInfo.isConnected() = true
D/PhoneState( 4252): setPdpRejectCasuse : false
,V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@4288fcc0 on behalf of 4745
,D/MobileConnectivityChangeReceiver( 4770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4770): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4532): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2835): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4745): DownloadService onDestroy
,D/LGDMClient( 2835): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4836): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2835): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4850): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4850): CONNECT : WIFI_CONNECT
E/LGDMClient( 2835): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2835): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2835): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2835): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  961): battery changed pluggedType: 2
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1488): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-39ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3757): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3757): onReceive
,D/AppUp4:CustFacade( 3757): Context : android.app.ReceiverRestrictedContext@42847fb8
D/AppUp4:CustFacade( 3757): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3757): isOpenOperator : true
,D/AppUp4:CustFacade( 3757): isPhone : true
,I/LicenseContentProvider( 2958): start selecting data
,D/SIMObserver( 2958): simInfo1
,I/AppUp4:EulaManager( 3757): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3757): begin check event
,I/AppUp4:CustModeStarterReceiver( 3757): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4532): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4745): DownloadService onCreate
,D/EAS     ( 4532): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4252): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4252): networkInfo.isConnected() = true
,D/PhoneState( 4252): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4770): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2835): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4836): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4850): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4850): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2835): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 4745): in removeSpuriousFiles
,V/DownloadManager( 4745): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@428947c0 on behalf of 4745
,I/LGDMClient( 2835): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 4745): in trimDatabase
V/DownloadManager( 4745): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4745): DownloadService onStartCommand
V/DownloadManager( 4745): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@42895e28 on behalf of 4745
V/DownloadManager( 4745): created cursor android.database.sqlite.SQLiteCursor@42897a48 on behalf of 4745
E/LGDMClient( 2835): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
W/Settings( 4532): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2835): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2835): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 4745): DownloadService onDestroy
I/LGDMClient( 2835): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  961): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV2    ( 4862): Thread[GAThread,5,main]: No campaign data found.
,E/ThermalEngine(  290): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  961): Killing 4551:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2055): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/Finsky  ( 4171): [390] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4171): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  961): Killing 4663:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2055): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.460846 Y: -0.396973 Z: 9.810623 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460846 .y:-0.396973 .z:9.810623
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.459991 Y: -0.402878 Z: 9.817780 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459991 .y:-0.402878 .z:9.817780
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/InputReader(  961): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  961): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5116 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  961): Handling package changes for user 0
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3744): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3744): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5116): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/WifiController(  961): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Babel   ( 5116): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5116): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5116): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5116): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5116): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5116): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Babel   ( 5116): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5116): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5116): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5116): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/GmsNetworkLocationProvi( 1423): DISABLE
W/BaseRuntimeLoader( 5116): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5116): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5116): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5116): MmsConfig.loadFromResources
,E/Babel   ( 5116): canonicalizeMccMnc: invalid mccmnc nullnull
I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 5116): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5116): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5116): [loadRssi] File not exist 
V/LGRssiData( 5116): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5116): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5116): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5116): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5116): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3757): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 3757): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3757): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3757): onReceive
D/AppUp4:CustFacade( 3757): Context : android.app.ReceiverRestrictedContext@42847fb8
D/AppUp4:CustFacade( 3757): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3757): isOpenOperator : true
,D/AppUp4:CustFacade( 3757): isPhone : true
I/LicenseContentProvider( 2958): start selecting data
,D/SIMObserver( 2958): simInfo1
,I/AppUp4:EulaManager( 3757): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3757): begin check event
D/AppUp4:Utils( 3757): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3757): Event For Nothing, skip.
,D/LocationProviderProxy(  961): applying state to connected service
,D/LocationProviderProxy(  961): applying state to connected service
I/ActivityManager(  961): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5165 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5165): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5165): BUILD Country: EU
,I/SystemConfig( 5165): BUILD Operator: OPEN
I/ActivityManager(  961): Killing 4701:com.lge.qremote/u0a96 (adj 15): empty #17
,I/SystemConfig( 5165): systemFeature RCS result false
,D/SystemConfig( 5165): refreshRcsSupport() :false
,I/ActivityManager(  961): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5179 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Killing 4613:com.test.thalitest/u0a304 (adj 15): empty #17
,D/HyLog   ( 5179): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5179): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5179): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/WindowState(  961): WIN DEATH: Window{44f63e08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  961): Client connection lost with reason: 4
,I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{44eb7478 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,I/InputMethodManagerService(  961): IME STATUS OFF
,W/Binder  ( 1325): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1325): java.lang.NullPointerException
W/Binder  ( 1325): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1325): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1325): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1325): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  961): Got RemoteException sending setActive(false) notification to pid 4613 uid 10304
,I/ActivityManager(  961): Killing 4745:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2642): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  961): Delaying start of: ServiceRecord{44689fc0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1966): GC_CONCURRENT freed 1902K, 22% free 19550K/24832K, paused 2ms+3ms, total 32ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2642): UpdateCorporaTask done [took 224 ms] updated apps [took 224 ms] 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/WifiController(  961): battery changed pluggedType: 2
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1226): Disconnected process message: 10
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2055): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1157): GC_CONCURRENT freed 2918K, 11% free 25444K/28540K, paused 2ms+1ms, total 61ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/WifiController(  961): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/WifiController(  961): battery changed pluggedType: 2
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CaptivePortalTracker(  961): Checking http://216.58.209.46/generate_204
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2,
D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601020086, nextTick: 59945, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601020088, nextTick: 59932, mDrawingTime: 4
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WeatherService( 1838): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:17:0
,D/WeatherService( 1838): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1838): 2 : SDK version : 19
,D/WeatherQuickCover( 1838): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1838): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1838): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1838): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1838): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1838): 2 : This is isUpdating : false
D/WeatherService( 1838): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1838): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1838): 2 : Map key string is -2
,D/lim     ( 1838): 2 : time = 13:17
,I/WeatherReflect( 1838): Model Name : LG-D802
,D/WeatherTheme( 1838): 2 : Different view - status_min_formatted : 16 != 17
D/WeatherTheme( 1838): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,D/WeatherTheme( 1838): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1838): 2 : Fixed theme : optimus
,D/WeatherTheme( 1838): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1838): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:17:0
,D/CaptivePortalTracker(  961): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  961): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  961): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  961): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2055): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV4    ( 5116): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
,D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/wpa_supplicant( 2055): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2055): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,I/PowerManagerService(  961): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  961): [updateScreenState] screen on = false
,D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  961): _hal_sensors_flush: handle=35
,I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, enabled=1
,I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6094 usec
D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  961): hal_acquire_resources
,I/qcom_sensors_hal(  961): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  961): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  961): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  961): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  961): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  961): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  961): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.464691 Y: -0.393448 Z: 9.821869 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464691 .y:-0.393448 .z:9.821869
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.459869 Y: -0.389236 Z: 9.817108 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459869 .y:-0.389236 .z:9.817108
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Sensors (  326): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  961): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  961): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  961): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  961): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  961): proximitySensorChanged  positive = true
I/KnockOnPowerController(  961): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.460983 Y: -0.388123 Z: 9.810669 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460983 .y:-0.388123 .z:9.810669
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.456299 Y: -0.399353 Z: 9.817154 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456299 .y:-0.399353 .z:9.817154
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.459244 Y: -0.401306 Z: 9.835403 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459244 .y:-0.401306 .z:9.835403
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.456207 Y: -0.393250 Z: 9.825592 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456207 .y:-0.393250 .z:9.825592
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.448868 Y: -0.403275 Z: 9.805786 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448868 .y:-0.403275 .z:9.805786
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  961): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@435180e0)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
,D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  961): **** SHOWN CALLED ****
,D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb8b4d450
D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
I/WindowManager(  961): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  961): handleScreenStateChanged: true
,D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2055): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  961): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2055): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131127
D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=132097
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  961): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2055): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2055): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiOffDelayIfNotUsed(  961): stopMonitoring
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 961
V/SRS_Proc(  276): ParamSet string: screen_state=on
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
,V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4282d3e8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3744): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WeatherAncestor( 1838): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:17:9
,I/SlideAside( 3744): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1838): 2 : This is isUpdating : false
,D/WeatherAncestor( 1838): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:17:9
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1838): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1838): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1838): 2 : TimeTick Receiver Unregister
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherService( 1838): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 231, B = 231
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  961): Excessive delay in blankDisplay() while turning screen off: 401ms
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601029941, nextTick: 50092, mDrawingTime: 0
D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601029964, nextTick: 50067, mDrawingTime: 2
D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
D/WeatherService( 1838): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:17:9
D/WeatherService( 1838): 2 : ACTION screen on
,D/WeatherService( 1838): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1838): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:17:9
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
,E/Parcel  (  568): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_ON
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1143): notifyScreenOffLocked
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1}
,D/qcom_sensors_hal(  961): hal_acquire_resources
D/qcom_sensors_hal(  961): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  961): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  961): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  961): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  961): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
W/ProcessCpuTracker(  961): Skipping unknown process pid 5261
W/ProcessCpuTracker(  961): Skipping unknown process pid 5262
W/ProcessCpuTracker(  961): Skipping unknown process pid 5267
W/ProcessCpuTracker(  961): Skipping unknown process pid 5269
D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  961): Vibrator off
,D/WifiStateMachine(  961): handleScreenStateChanged: false
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  961): doBoolean: DRIVER SETSUSPENDMODE 1
,D/KeyguardViewMediator( 1143): handleNotifyScreenOff
,D/KeyguardViewManager( 1143): onScreenTurnedOff()
W/ProcessCpuTracker(  961): Skipping unknown process pid 5272
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/wpa_supplicant( 2055): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2055): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/WifiController(  961): CMD_SCREEN_OFF 
D/WifiController(  961): shouldWifiStayAwake TRUE
E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 961
V/SRS_Proc(  276): ParamSet string: screen_state=off
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
,D/wpa_supplicant( 2055): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  961):    returned true
,D/WifiStateMachine(  961): handleMessage: X
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{42c20cf8 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1157): clear
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
E/Parcel  (  568): Reading a NULL string not supported here.
,E/Parcel  (  568): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WeatherService( 1838): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:17:10
D/WeatherService( 1838): 2 : ACTION screen off
,D/WeatherService( 1838): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:17:10
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,D/NfcService( 1473): NFC-C OFF
,D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_OFF
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
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
,I/Sensors (  326): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,E/ThermalEngine(  290): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1554): Vacuum at: now=1452601038449 tag=VacuumService
,I/GoogleURLConnFactory( 1554): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1554): No account for auth token provided
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1554): No account for auth token provided
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1554): No account for auth token provided
,W/Uploader( 1554):  no longer exists, so no auth token.
,W/Uploader( 1554): No account for auth token provided
,D/dalvikvm( 1554): GC_CONCURRENT freed 1719K, 28% free 18061K/24832K, paused 25ms+5ms, total 78ms
,D/dalvikvm(  961): GC_EXPLICIT freed 3056K, 47% free 30792K/57324K, paused 5ms+15ms, total 172ms
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601047791316221; DSPS: 5276403; Offset: 1452600886768275450
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601067792224853; DSPS: 5931792; Offset: 1452600886768299072
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601080046, nextTick: 59985, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601080057, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601087793575389; DSPS: 6587197; Offset: 1452600886768276317
,D/wpa_supplicant( 2055): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601107794028842; DSPS: 7242572; Offset: 1452600886768272007
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601127794462381; DSPS: 7897946; Offset: 1452600886768278299
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601140049, nextTick: 59969, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601140059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601147795823954; DSPS: 8553350; Offset: 1452600886768297099
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601167796264655; DSPS: 9208725; Offset: 1452600886768280036
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601187797205543; DSPS: 9864116; Offset: 1452600886768274879
,D/wpa_supplicant( 2055): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Remove id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Remove id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Remove id 7 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Remove id 8 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Remove id 9 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2055): wlan0: BSS: Remove id 10 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2055): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 a0:c5:62:7a:49:97]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 a0:c5:62:7a:49:96]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 44:e9:dd:10:c0:ac]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:26:f2:18:08:c8]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 dc:4a:3e:0f:c2:f1]
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601200048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601200051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601207798565851; DSPS: 10519520; Offset: 1452600886768292414
,I/ActivityManager(  961): Killing 4532:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c3dc70 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x44f7fb28: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1554): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1554): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1554): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1554): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1554): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4171): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4171): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4171): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4171): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4171): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4171): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4171): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4171): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4171): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4171): isDataSchedulerEnabled():false
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601227799466932; DSPS: 11174910; Offset: 1452600886768277968
,I/LocationManagerService(  961): remove 42d920e0
,D/LocationManagerService(  961): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2629): GC_CONCURRENT freed 7742K, 32% free 16910K/24832K, paused 13ms+3ms, total 87ms
,D/dalvikvm( 2629): WAIT_FOR_CONCURRENT_GC blocked 61ms
,D/dalvikvm( 2629): GC_CONCURRENT freed 1821K, 31% free 17136K/24832K, paused 3ms+1ms, total 27ms
,D/dalvikvm( 2629): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2629): GC_FOR_ALLOC freed 1328K, 31% free 17267K/24832K, paused 20ms, total 20ms
,I/Mlt MonitorService( 2629): parseLastkmsg to dump
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601247799901677; DSPS: 11830284; Offset: 1452600886768285467
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601260032, nextTick: 59986, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601260041, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601267800343190; DSPS: 12485659; Offset: 1452600886768269216
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601287801255307; DSPS: 13141049; Offset: 1452600886768265806
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601307802103651; DSPS: 13796436; Offset: 1452600886768290175
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601320037, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601320046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601327802554384; DSPS: 14451811; Offset: 1452600886768283144
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601347803003208; DSPS: 15107186; Offset: 1452600886768274205
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601367803446122; DSPS: 15762560; Offset: 1452600886768289872
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601380036, nextTick: 59982, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601380045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601387803892478; DSPS: 16417935; Offset: 1452600886768278465
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601407804816698; DSPS: 17073325; Offset: 1452600886768287157
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601427805241595; DSPS: 17728699; Offset: 1452600886768284808
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601440036, nextTick: 59982, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601440045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601447805684417; DSPS: 18384074; Offset: 1452600886768269867
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601467813472457; DSPS: 19039689; Offset: 1452600886768275924
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601487814770739; DSPS: 19695091; Offset: 1452600886768292468
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 268 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601500049, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601500050, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601507815631087; DSPS: 20350479; Offset: 1452600886768298324
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601527816085431; DSPS: 21005854; Offset: 1452600886768294904
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601547817540194; DSPS: 21661262; Offset: 1452600886768284823
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601560039, nextTick: 59973, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601560053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601567818392534; DSPS: 22316650; Offset: 1452600886768282671
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601587818845493; DSPS: 22972025; Offset: 1452600886768277867
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601607819286076; DSPS: 23627399; Offset: 1452600886768291203
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601620028, nextTick: 59997, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601620054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601627820678718; DSPS: 24282805; Offset: 1452600886768280037
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601647821140362; DSPS: 24938180; Offset: 1452600886768283917
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601667821582769; DSPS: 25593555; Offset: 1452600886768268561
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601680037, nextTick: 59991, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601680040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601687826831510; DSPS: 26249087; Offset: 1452600886768268278
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601707828212487; DSPS: 26904492; Offset: 1452600886768275964
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  961): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  961): Done.
,D/QcConnectivityService(  961): Setting timer for 720seconds
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601727829149976; DSPS: 27559882; Offset: 1452600886768297926
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601740039, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601740048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601747830543211; DSPS: 28215288; Offset: 1452600886768287352
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601767831437731; DSPS: 28870677; Offset: 1452600886768296862
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601787832339467; DSPS: 29526067; Offset: 1452600886768283071
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601800038, nextTick: 59990, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601800041, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601807833715539; DSPS: 30181472; Offset: 1452600886768285852
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601827834156415; DSPS: 30836847; Offset: 1452600886768268964
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601847834617353; DSPS: 31492222; Offset: 1452600886768272139
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601860050, nextTick: 59979, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601860056, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601867835993335; DSPS: 32147627; Offset: 1452600886768274830
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601887837978479; DSPS: 32803052; Offset: 1452600886768276331
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601907838830797; DSPS: 33458440; Offset: 1452600886768274157
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601920037, nextTick: 59968, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601920056, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601927840255073; DSPS: 34113846; Offset: 1452600886768294624
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601947841607206; DSPS: 34769250; Offset: 1452600886768303984
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601967842454851; DSPS: 35424638; Offset: 1452600886768297137
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601980037, nextTick: 59987, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452601980052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452601987843824519; DSPS: 36080043; Offset: 1452600886768293514
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602007844707185; DSPS: 36735432; Offset: 1452600886768291170
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602027845598173; DSPS: 37390821; Offset: 1452600886768297148
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602040027, nextTick: 60000, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602040051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602047847646387; DSPS: 38046248; Offset: 1452600886768300684
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602067848567231; DSPS: 38701639; Offset: 1452600886768275483
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602087849008672; DSPS: 39357013; Offset: 1452600886768289678
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602100028, nextTick: 59984, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602100061, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602107850391521; DSPS: 40012418; Offset: 1452600886768299236
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602127851276987; DSPS: 40667807; Offset: 1452600886768299693
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602147852145520; DSPS: 41323196; Offset: 1452600886768283216
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602160042, nextTick: 59972, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602160053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602167853531841; DSPS: 41978602; Offset: 1452600886768265728
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602187854423476; DSPS: 42633991; Offset: 1452600886768272353
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602207854885488; DSPS: 43289366; Offset: 1452600886768276602
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602220028, nextTick: 59998, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602220052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602227856277319; DSPS: 43944771; Offset: 1452600886768295142
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602247858226382; DSPS: 44600195; Offset: 1452600886768291080
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602267859094910; DSPS: 45255584; Offset: 1452600886768274598
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602280040, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602280042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602287860475643; DSPS: 45910989; Offset: 1452600886768282040
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602307861807027; DSPS: 46566393; Offset: 1452600886768270651
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602327862254988; DSPS: 47221767; Offset: 1452600886768291365
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602340032, nextTick: 59988, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602340041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602347863677829; DSPS: 47877174; Offset: 1452600886768279880
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602367864554702; DSPS: 48532563; Offset: 1452600886768271744
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602387865431204; DSPS: 49187951; Offset: 1452600886768293753
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602400037, nextTick: 59979, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602400047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602407867560376; DSPS: 49843381; Offset: 1452600886768286695
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602427868013075; DSPS: 50498756; Offset: 1452600886768281630
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  961): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  961): Done.
,D/QcConnectivityService(  961): Setting timer for 720seconds
,I/EventLogService( 1966): Aggregate from 1452601007013 (log), 1452600181484 (data)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1554): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602447868976220; DSPS: 51154147; Offset: 1452600886768298730
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602460039, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602460046, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602467870368646; DSPS: 51809553; Offset: 1452600886768287348
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602487871310608; DSPS: 52464944; Offset: 1452600886768283265
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602507872629226; DSPS: 53120347; Offset: 1452600886768289627
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602520034, nextTick: 59987, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602520042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602527874009213; DSPS: 53775752; Offset: 1452600886768296323
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602547874916902; DSPS: 54431142; Offset: 1452600886768288485
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602567875346447; DSPS: 55086516; Offset: 1452600886768290783
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602580039, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602580042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602587877493009; DSPS: 55741947; Offset: 1452600886768270597
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602607877951797; DSPS: 56397321; Offset: 1452600886768302139
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602627878871578; DSPS: 57052712; Offset: 1452600886768275875
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602640079, nextTick: 59951, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602640081, nextTick: 59952, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602647880243983; DSPS: 57708116; Offset: 1452600886768305507
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602667881144102; DSPS: 58363506; Offset: 1452600886768290099
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602687881590502; DSPS: 59018881; Offset: 1452600886768278735
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602700083, nextTick: 59948, mDrawingTime: 1
I/ProcessStatsService(  961): Prepared write state in 64ms
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602700087, nextTick: 59943, mDrawingTime: 1
,I/ProcessStatsService(  961): Pruning old procstats: /data/system/procstats/state-2016-01-11-15-39-10.bin
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602707883021447; DSPS: 59674288; Offset: 1452600886768275354
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602727884406087; DSPS: 60329693; Offset: 1452600886768286703
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602747885251304; DSPS: 60985081; Offset: 1452600886768277428
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602760062, nextTick: 59969, mDrawingTime: 1
D/Clock   ( 1143): Clock updated, drawingStartTime : 1452602760063, nextTick: 59968, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602767886258941; DSPS: 61640473; Offset: 1452600886768308502
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602787887239392; DSPS: 62295866; Offset: 1452600886768281873
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1452602807888136644; DSPS: 62951255; Offset: 1452600886768294115
,TIME-OUT KILL (timeout was 1800000ms)
```
