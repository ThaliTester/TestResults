#### Test 5065027869d93ea_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1947): Using Auth Proxy for data requests.
W/BaseAppContext( 1947): Using Auth Proxy for data requests.
,W/GAV2    ( 4807): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  967): Killing 4166:com.google.android.configupdater/u0a3 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2}
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1947): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1947): GC_CONCURRENT freed 1564K, 22% free 19529K/24832K, paused 3ms+3ms, total 40ms
I/ConfigFetchService( 1947): fetch service done; releasing wakelock
I/ConfigFetchService( 1947): stopping self
D/AndroidRuntime( 4857): 
D/AndroidRuntime( 4857): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4857): CheckJNI is OFF
D/dalvikvm( 4857): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4857): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4857): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4857): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4857): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4857): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4857): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4857): failed to load memtrack module: -2
I/Icing   ( 1947): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4857): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4857
D/Icing   ( 1947): Loaded CLD2 Version V2.0 - 20141016
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (325 us)
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{439a2658 stackId=1, 2 tasks}
D/UsbSettingsControl( 2616): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2616): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4857): Shutting down VM
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4857): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4871 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3814): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/SlideAside( 3814): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3814): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/dalvikvm(  269): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+1ms, total 20ms
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 16ms
D/HyLog   ( 4871): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4871): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4871): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
I/Icing   ( 1947): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
V/WebViewChromium( 4871): Binding Chromium to the background looper Looper (main, tid 1) {42e45530}
I/chromium( 4871): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4871): Initializing chromium process, renderers=0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1210): Disconnected process message: 10
W/chromium( 4871): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Adreno-EGL( 4871): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4871): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4871): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4871): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4871): Remote Branch: 
I/Adreno-EGL( 4871): Local Patches: 
I/Adreno-EGL( 4871): Reconstruct Branch: 
I/dalvikvm( 4871): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4871): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4871): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4871): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4871): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4871): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4871): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4871): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4871): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4871): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4871): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4871): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4871): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4871): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4871): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4871): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4871): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4871): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4871): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4871): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4871): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4871): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4871): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4871): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4871): Enabling debug mode 0
W/AwContents( 4871): nativeOnDraw failed; clearing to background color.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +412ms
W/AwContents( 4871): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  967): IME STATUS OFF
I/ActivityManager( 4871): Timeline: Activity_idle id: android.os.BinderProxy@42e46d00 time:111220
D/JsMessageQueue( 4871): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4871): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42e4ade0
D/dalvikvm( 4871): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42e4ade0
D/jxcore_app_log( 4871): JniHelper::setJavaVM(0x41df1808), pthread_self() = 1638998408
D/JX-Cordova( 4871): jxcore cordova android initializing
D/ActivityManager(  967): no-history finish of ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{437ae578 ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3} time:111552
D/UsbSettings( 2616): [AUTORUN] onStop()
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2031): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459152 Y: -0.358109 Z: 9.781158 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459152 .y:-0.358109 .z:9.781158
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/dalvikvm( 4871): GC_CONCURRENT freed 2787K, 12% free 21866K/24832K, paused 2ms+2ms, total 46ms
D/dalvikvm( 4871): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4871): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 241K, 13% free 21828K/24832K, paused 22ms, total 22ms
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449310 Y: -0.372330 Z: 9.773300 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449310 .y:-0.372330 .z:9.773300
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 187K, 12% free 21855K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4871): Grow heap (frag case) to 23.655MB for 144892-byte allocation
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 252K, 13% free 21905K/24976K, paused 22ms, total 22ms
I/dalvikvm-heap( 4871): Grow heap (frag case) to 23.772MB for 217334-byte allocation
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 372K, 13% free 21977K/25192K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4871): Grow heap (frag case) to 23.947MB for 325996-byte allocation
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 570K, 14% free 22099K/25512K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4871): Grow heap (frag case) to 24.221MB for 488990-byte allocation
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 869K, 15% free 22276K/25992K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4871): Grow heap (frag case) to 24.626MB for 733480-byte allocation
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 1288K, 16% free 22534K/26712K, paused 22ms, total 22ms
,D/dalvikvm( 4871): GC_CONCURRENT freed 1676K, 15% free 22905K/26712K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 4871): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4871): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 376K, 15% free 22863K/26712K, paused 34ms, total 34ms
,I/dalvikvm-heap( 4871): Grow heap (frag case) to 26.074MB for 1650320-byte allocation
,D/dalvikvm( 4871): GC_CONCURRENT freed 1679K, 18% free 23431K/28324K, paused 1ms+3ms, total 34ms
,D/dalvikvm( 4871): GC_FOR_ALLOC freed 1386K, 17% free 23517K/28324K, paused 25ms, total 27ms
,I/dalvikvm-heap( 4871): Grow heap (frag case) to 27.500MB for 2475476-byte allocation
D/dalvikvm( 4871): GC_CONCURRENT freed 312K, 16% free 25867K/30744K, paused 2ms+3ms, total 36ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4871): GC_FOR_ALLOC freed 4323K, 21% free 24481K/30744K, paused 29ms, total 29ms
I/dalvikvm-heap( 4871): Grow heap (frag case) to 29.622MB for 3713210-byte allocation
D/dalvikvm( 4871): GC_CONCURRENT freed 306K, 19% free 27977K/34372K, paused 4ms+7ms, total 38ms
D/dalvikvm( 4871): GC_FOR_ALLOC freed 3139K, 26% free 25442K/34372K, paused 24ms, total 24ms
W/jxcore-log( 4871): Initializing JXcore engine
W/jxcore-log( 4871): JXcore engine is ready
D/dalvikvm( 4871): GC_CONCURRENT freed 325K, 19% free 28105K/34372K, paused 1ms+2ms, total 31ms
D/dalvikvm( 4871): WAIT_FOR_CONCURRENT_GC blocked 30ms
W/jxcore-log( 4871): Starting JXcore engine
W/jxcore-log( 4871): Platform android
W/jxcore-log( 4871): 
W/jxcore-log( 4871): Process ARCH arm
W/jxcore-log( 4871): 
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4871): JXcore Cordova bridge is ready!
I/jxcore-log( 4871): 
,W/jxcore-log( 4871): JXcore engine is started
,I/chromium( 4871): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4871): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4871): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484640031, nextTick: 60000, mDrawingTime: 1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484640053, nextTick: 59980, mDrawingTime: 0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2031): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/GAV2    ( 4807): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4871): Toggling radios to true
I/jxcore-log( 4871): 
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44f7a630:true
,D/BluetoothAdapter( 4871): enable(): BT is already enabled..!
D/WifiService(  967): New client listening to asynchronous messages
,D/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doBoolean: DISCONNECT
,I/jxcore-log( 4871): Radios toggled
I/jxcore-log( 4871): 
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2031): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2031): wlan0: Cancelling scan request
D/wpa_supplicant( 2031): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2031): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2031): TDLS: Tear down peers
,D/wpa_supplicant( 2031): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4871): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4871): 
,I/jxcore-log( 4871): Perf Test app loaded loaded
I/jxcore-log( 4871): 
D/WifiService(  967): setWifiEnabled: true pid=4871, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  967): disconnect pid=4871, uid=10304
,D/WifiService(  967): reconnect pid=4871, uid=10304
I/Choreographer( 4871): Skipped 73 frames!  The application may be doing too much work on its main thread.
,D/wpa_supplicant( 2031): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2031): wlan0: Deauthentication notification
D/wpa_supplicant( 2031): wlan0:  * reason 3 (locally generated)
,D/wpa_supplicant( 2031): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2031): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2031): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2031): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2031): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb80f7d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2031):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2031): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2031): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2031): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=5
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2031): EAPOL: External notification - portEnabled=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2031): nl80211: Event message available
D/wpa_supplicant( 2031): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2031): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
W/Settings(  967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131146
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiNative-wlan0(  967): doBoolean: RECONNECT
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2031): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2031): Fast associate: Old scan results
D/wpa_supplicant( 2031): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2031): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2031): wlan0: nl80211: scan request
D/wpa_supplicant( 2031): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  967):    returned true
D/wpa_supplicant( 2031): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2031): nl80211: Event message available
D/wpa_supplicant( 2031): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2031): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
I,/jxcore-log( 4871): check test folder
I/jxcore-log( 4871): 
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2031): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2031): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2031): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
I/jxcore-log( 4871): found test : ./testFindPeers.js
I/jxcore-log( 4871): 
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  265): Clearing all IP addresses on wlan0
D/WifiP2pService(  967): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 0
,D/WifiHS20(  967): hidePasspointNotification off =false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
D/QCNEA   (  420): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  420): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  420): |CAC| updateNetCfgInfo
V/QCNEA   (  420): |CAC| *********************************************
V/QCNEA   (  420): |CAC|                   Netconfig               
V/QCNEA   (  420): |CAC| *********************************************
V/QCNEA   (  420): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  420): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  420): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  420): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  420): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  420): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  420): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  420): |CAC| *********************************************
D/QCNEA   (  420): |CAC| Received bssid= 
D/QCNEA   (  420): |CAC| net type = 3
V/QCNEA   (  420): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  420): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  420): |CAC| 	ssid           =NG700
V/QCNEA   (  420): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  420): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  420): |CAC| *********************************************
D/QCNEA   (  420): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  420): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  420): |CAC| dispatchNetCfg: updating:0xb7c3c8dc
D/QCNEA   (  420): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4932 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
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
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,I/jxcore-log( 4871): found test : ./testSendData.js
I/jxcore-log( 4871): 
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  265): RouteController
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
D/HyLog   ( 4932): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4932): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4932): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,W/NetworkManagementService(  967): route cmd failed: 
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
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x62859fe0 clazz=0x6c000001 iface=wlan0 mask=0x3
,D/QcConnectivityService(  967): resetConnections(wlan0, 3)
V/NativeCrypto( 1554): Read error: ssl=0x63ef0640: I/O error during system call, Connection timed out
I/PCSuite ( 4932): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/NativeCrypto( 1554): SSL shutdown failed: ssl=0x63ef0640: I/O error during system call, Broken pipe
D/PCSuite ( 4932): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4932): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4968 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  967): Killing 4301:com.google.android.talk/u0a77 (adj 15): empty #17
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/HyLog   ( 4968): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4968): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4968): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/chromium( 4871): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4968): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4968): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4968): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4968): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4968): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4968): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4968): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,I/ConfigService( 1554): onDestroy
,D/QRemote ( 4968): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4968): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 2132:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  967): StoppedState
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
,D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
,D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3827): isOpenOperator : true
,D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,I/AppUp4:CustModeStarterReceiver( 3827): Event For GoodConnectivity
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4997 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/wpa_supplicant( 2031): nl80211: Event message available
D/wpa_supplicant( 2031): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2031): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2031): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2031): nl80211: Received scan results (12 BSSes)
D/wpa_supplicant( 2031): nl80211: Survey data missing
D/wpa_supplicant( 2031): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 7 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 8 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 9 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 10 BSSID fc:6f:b7:3e:78:0a SSID 'UPC249917252'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 11 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): BSS: last_scan_res_used=12/32 last_scan_full=0
D/wpa_supplicant( 2031): wlan0: New scan results available
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2031): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2031): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2031): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2031): WPS: AP fc:6f:b7:3e:78:0a type 0 added
D/wpa_supplicant( 2031): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2031): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2031): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2031): WPS: AP[2] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2031): WPS: AP[3] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2031): WPS: AP[4] fc:6f:b7:3e:78:0a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2031): WPS: AP[5] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2031): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2031): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2031): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2031): wlan0: 1: c0:,ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2031): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2031): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2031): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb80f95a8  current_ssid=0x0
D/wpa_supplicant( 2031): scard is not null..
D/wpa_supplicant( 2031): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2031): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2031): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2031): wlan0: Cancelling scan request
D/wpa_supplicant( 2031): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2031): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2031): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2031): RSN: PMKSA cache search - network_ctx=0xb80f95a8 try_opportunistic=0
D/wpa_supplicant( 2031): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2031): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2031): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2031): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2031): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2031): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2031): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2031): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2031): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2031): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2031): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2031): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2031): nl80211: Unsubscribe mgmt frames handle 0xb80f8590 (mode change)
D/wpa_supplicant( 2031): nl80211: Subscribe to mgmt frames with non-AP handle 0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2031): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2031):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031):   * freq=2412
D/wpa_supplicant( 2031):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2031):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031):   * Auth Type 0
D/wpa_supplicant( 2031):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 06:7c:34:12:7f:81]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 fc:94:e3:11:35:3a]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 fe:94:e3:11:35:3c]
D/wpa_supplicant( 2031): nl80211: Connect request send successfully
D/wpa_supplicant( 2031): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2031): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 64:7c:34:38:27:cc]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 fc:6f:b7:3e:78:0a]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 64:7c:34:12:7f:81]
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2031): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2031): nl80211: Event message available
D/wpa_supplicant( 2031): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2031): nl80211: Connect event
D/wpa_supplicant( 2031): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2031): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2031): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2031): wlan0: Association info event
D/wpa_supplicant( 2031): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2031): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2031): wlan0: freq=2412 MHz
D/wpa_supplicant( 2031): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2031): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2031): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2031): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): scard is not null..
D/wpa_supplicant( 2031): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2031): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2031): TDLS: Remove peers on association
D/wpa_supplicant( 2031): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2031): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2031): EAPOL: enable timer tick
D/wpa_supplicant( 2031): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2031): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2031): wlan0: Cancelling scan request
D/wpa_supplicant( 2031): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/HyLog   ( 4997): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4997): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4997): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2031): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 78 eb e4 4d d5 66 29 7a e9 42 f5 67 3e ba f0 ...
D/wpa_supplicant( 2031): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2031): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2031): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2031): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2031): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2031):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2031):   key_nonce - hexdump(len=32): 78 eb e4 4d d5 66 29 7a e9 42 f5 67 3e ba f0 69 f6 20 7b e8 6b 40 e7 8d eb 0c 4e 16 78 be e7 d8
D/wpa_supplicant( 2031):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 78 eb e4 4d d5 66 29 7a e9 42 f5 67 3e ba f0 ...
D/wpa_supplicant( 2031): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2031): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2031): Get randomness: len=32 entropy=11
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2031): WPA: Renewed SNonce - hexdump(len=32): f7 c6 b2 7d 5e ab f1 66 d5 7a d9 b2 06 ac 41 c1 11 22 f2 b1 24 37 0e 00 cd 3d a3 d6 d2 c7 b3 e1
D/wpa_supplicant( 2031): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): WPA: Nonce1 - hexdump(len=32): f7 c6 b2 7d 5e ab f1 66 d5 7a d9 b2 06 ac 41 c1 11 22 f2 b1 24 37 0e 00 cd 3d a3 d6 d2 c7 b3 e1
D/wpa_supplicant( 2031): WPA: Nonce2 - hexdump(len=32): 78 eb e4 4d d5 66 29 7a e9 42 f5 67 3e ba f0 69 f6 20 7b e8 6b 40 e7 8d eb 0c 4e 16 78 be e7 d8
D/wpa_supplicant( 2031): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2031): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2031): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2031): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2031): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2031): WPA: Derived Key MIC - hexdump(len=16): 63 39 28 33 4d 17 e8 77 ec 32 ba 00 0d a7 17 2e
D/wpa_supplicant( 2031): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 f7 c6 b2 7d 5e ab f1 66 d5 7a d9 b2 06 ac 41 ...
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2031): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 78 eb e4 4d d5 66 29 7a e9 42 f5 67 3e ba f0 ...
D/wpa_supplicant( 2031): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2031): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2031): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2031): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2031):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2031):   key_nonce - hexdump(len=32): 78 eb e4 4d d5 66 29 7a e9 42 f5 67 3e ba f0 69 f6 20 7b e8 6b 40 e7 8d eb 0c 4e 16 78 be e7 d8
D/wpa_supplicant( 2031):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_rsc - hexdump(len=8): a0 83 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_mic - hexdump(len=16): cd 44 2c 48 4d 19 a0 d1 b7 38 65 e5 5c d9 90 9f
D/wpa_supplicant( 2031): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 78 eb e4 4d d5 66 29 7a e9 42 f5 67 3e ba f0 ...
D/wpa_supplicant( 2031): RSN: encrypted key data - hexdump(len=56): a7 a1 6d 69 02 f8 86 78 03 47 39 f2 10 38 94 d3 ec 40 64 2d 46 d9 1a 94 89 cf 90 6c 2d 6f 6b 14 ...
D/wpa_supplicant( 2031): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2031): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2031): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2031): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2031): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2031): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2031): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2031): WPA: Derived Key MIC - hexdump(len=16): 5f cf 76 fd 0f b1 b0 a8 31 30 f7 15 d9 cc 13 81
D/wpa_supplicant( 2031): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2031): wlan0: WPA: Installing PTK to the driver
E/BatteryObserver( 1160): usb Uevent not necessary.
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb80f8c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2031):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2031): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2031): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2031): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2031): WPA: RSC - hexdump(len=6): a0 83 00 00 00 00
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ed503a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2031):    broadcast key
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
I/wpa_supplicant( 2031): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2031): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2031): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2031): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2031): wpa_supplicant_set_state, isWPS : 0
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 2031): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2031): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2031): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2031): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2031): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2031): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): Network connection established
D/wpa_supplicant( 2031): EAPOL: SUPP_BE entering state IDLE
D/WifiNative-wlan0(  967): doString: STATUS
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2031): EAPOL authentication completed successfully
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2031): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetStateMachine( 1210): Disconnected process message: 10
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
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): handleMessage: X
D/DhcpStateMachine(  967): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-14ms what=147462 obj=android.net.wifi.StateChangeResult@454569f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-12ms what=147462 obj=android.net.wifi.StateChangeResult@4545af18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-12ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-5ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2031): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/DownloadManager( 4997): DownloadService onCreate
,D/EAS     ( 4790): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4790): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4997): in removeSpuriousFiles
,D/eas_req ( 4790): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4997): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e80660 on behalf of 4997
,V/DownloadManager( 4997): DownloadService onStartCommand
I/LgeMiscReceiver( 4480): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4480): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4480): networkInfo.isConnected() = false
,V/DownloadManager( 4997): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4997): in trimDatabase
V/DownloadManager( 4997): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e82cd8 on behalf of 4997
,V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e842b0 on behalf of 4997
,W/linker  ( 4790): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4790): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4790): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4790): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4790): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4790): register_HtmlEditor, Success
D/HtmlEditor( 4790): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4790): register_HtmlEditorTimer, Success
,D/HtmlEditor( 4790): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4790): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4790): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4790): register_HtmlEditorFont, Success
D/HtmlEditor( 4790): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4790): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4790): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4790): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4790): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4790): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4790): JNI_OnLoad Success
V/DownloadManager( 4997): DownloadService onDestroy
,I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5036 uid=10052 gids={50052, 3003}
I/HubEmail( 4790): JNI_OnLoad()
I/HubEmail( 4790): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4790): registerNatives()
I/HubEmail( 4790): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4790): registerNativeMethods()
I/HubEmail( 4790): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4790): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HyLog   ( 5036): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5036): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5036): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 3979:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
V/LGRssiData( 5036): [loadRssi] File not exist 
V/LGRssiData( 5036): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5036): [loadFeatureFromXml] *** start feature loading from xml
D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd OK len = 0, 2
W/BaseRuntimeLoader( 5036): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
W/BaseRuntimeLoader( 5036): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2031): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2031): CTRL_IFACE SET 'ps'='0'
W/BaseRuntimeLoader( 5036): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/wpa_supplicant( 2031): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
W/BaseRuntimeLoader( 5036): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/TelephonyAutoProfiling( 5036): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/WifiNative-wlan0(  967):    returned null
V/TelephonyAutoProfiling( 5036): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5036): [getValue] FEATURE key : vzw_roaming_state, value : null
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
,D/CommandListener(  265): Setting iface cfg
,D/MobileConnectivityChangeReceiver( 5036): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5036): onReceive CONNECTIVITY_CHANGE networkType=1
D/WifiStateMachine(  967): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/CommandListener(  265): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e614b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e614b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-8ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-7ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5052 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4466:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/wpa_supplicant( 2031): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2031): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2031): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
,D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
E/PhoneMonitor( 5036): onOtaspChanged old =0, new =3
V/PhoneMonitor( 5036): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  967): handleMessage: X
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
E/Parcel  (  420): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 1
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/HyLog   ( 5052): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5052): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5052): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
,V/        (  265): RouteController
,V/        (  265): RouteController
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5078 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  967): Killing 4734:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/QCNEA   (  420): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  420): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  420): |CAC| updateNetCfgInfo
V/QCNEA   (  420): |CAC| *********************************************
V/QCNEA   (  420): |CAC|                   Netconfig               
V/QCNEA   (  420): |CAC| *********************************************
V/QCNEA   (  420): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  420): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  420): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  420): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  420): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  420): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  420): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  420): |CAC| *********************************************
D/QCNEA   (  420): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  420): |CAC| net type = 1
V/QCNEA   (  420): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  420): |CAC| Received ssid= NG700
V/QCNEA   (  420): |CAC| 	ssid           =NG700
V/QCNEA   (  420): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  420): |CAC| 	DNS v4        =0.0.0.0
,V/QCNEA   (  420): |CAC| *********************************************
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QCNEA   (  420): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  420): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  420): |CAC| dispatchNetCfg: updating:0xb7c3c8dc
,D/QCNEA   (  420): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 5078): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5078): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5078): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  967): GC_EXPLICIT freed 23396K, 49% free 29780K/57592K, paused 2ms+8ms, total 131ms
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1210): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,I/ActivityManager(  967): Killing 4206:com.google.android.partnersetup/u0a9 (adj 15): empty #17
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1210): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 2888): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/WifiController(  967): battery changed pluggedType: 2
,I/CheckinService( 1947): Checking schedule, now: 1450484644562 next: 1450484587930
,I/CheckinService( 1947): active receiver: enabled
,D/LGDMClient( 2888): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2888): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5107 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinService( 1947): Preparing to send checkin request
,I/EventLogService( 1947): Accumulating logs since 1450484553867
,E/LGDMClient( 2888): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2888): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/HyLog   ( 5107): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5107): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5107): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2888): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2888): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/LGDMSGCM( 5107): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5107): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5120 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  967): Killing 4776:com.lge.bnr/1000 (adj 15): empty #17
D/HyLog   ( 5120): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5120): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5120): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 5120): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/CheckinRequestBuilder( 1947): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1947): Failed to find provider info for com.google.android.wearable.settings
I/Wireless_Storage( 5120): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 5120): intf.getDisplayName() = lo
I/Wireless_Storage( 5120): intf.getDisplayName() = sit0
I/Wireless_Storage( 5120): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5120): intf.getDisplayName() = teql0
I/Wireless_Storage( 5120): intf.getDisplayName() = wlan0
D/NFS     ( 5120): interface name:wlan0 name:wlan0
D/NFS     ( 5120): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5120): interface name:wlan0 name:wlan0
D/NFS     ( 5120): addr:192.168.1.144 broadcast:192.168.1.255
I/Wireless_Storage( 5120): CONNECT : WIFI_CONNECT
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5133 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4364:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5133): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5133): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5133): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 5133): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1947): awaiting user notification for token
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x438773d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5152 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5152): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5152): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5152): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/WebViewChromium( 5133): Binding Chromium to the main looper Looper (main, tid 1) {42e43338}
,I/chromium( 5133): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5133): Initializing chromium process, renderers=0
,W/dalvikvm( 5152): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5152): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5152): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5152): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5152): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5152): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5152): install
,I/MultiDex( 5152): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,W/chromium( 5133): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5133): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5133): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5133): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5133): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5133): Remote Branch: 
I/Adreno-EGL( 5133): Local Patches: 
I/Adreno-EGL( 5133): Reconstruct Branch: 
,I/MultiDex( 5152): loading existing secondary dex files
,I/MultiDex( 5152): load found 3 secondary dex files
,I/MultiDex( 5152): install done
,I/NSApplication( 5133): Starting up...
D/dalvikvm( 5152): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5152): VFY: unable to resolve instance field 61
,D/dalvikvm( 5152): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 5152): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5152): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5152): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5152): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5152): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5152): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5152): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5152): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5152): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e4a6b8
D/dalvikvm( 5152): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e4a6b8
,D/dalvikvm( 5152): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e4a6b8, skipping init
,D/dalvikvm( 5152): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e4a6b8
D/dalvikvm( 5152): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e4a6b8
,V/JNIHelp ( 5152): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  967): Killing 4385:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4968): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4968): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4968): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4968): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4968): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4968): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4932): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4932): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4968): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4968): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4968): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4968): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/dalvikvm( 5152): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e4a6b8
D/dalvikvm( 5152): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42e4a6b8
D/dalvikvm( 5152): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e4a6b8
,D/dalvikvm( 5152): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42e4a6b8
,I/ProviderInstaller( 5152): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1554): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1554): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1947): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 5152): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 5152): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5152): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1947): Restart initialization of location
,D/WearableService( 1838): callingUid 10006, callindPid: 1838
I/dalvikvm( 5152): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5152): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5152): VFY: replacing opcode 0x6e at 0x0201
,E/MDM     ( 1427): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ea1000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ea1000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=1836736607
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5152): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43002060
D/dalvikvm( 5152): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43002060
,D/dalvikvm( 5152): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x43002060, skipping init
,D/wpa_supplicant( 2031): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2031): EAPOL: disable timer tick
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/dalvikvm( 5152): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5185): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/dalvikvm( 5152): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5152): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 60ms
,I/Adreno-EGL( 5152): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5152): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5152): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5152): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5152): Remote Branch: 
I/Adreno-EGL( 5152): Local Patches: 
I/Adreno-EGL( 5152): Reconstruct Branch: 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 5152): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5152): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5152): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5152): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5152): Remote Branch: 
I/Adreno-EGL( 5152): Local Patches: 
I/Adreno-EGL( 5152): Reconstruct Branch: 
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=2392643444
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/dalvikvm( 4871): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4871): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4871): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4871): Shutting down VM
,W/dalvikvm( 4871): threadid=1: thread exiting with uncaught exception (group=0x41e02e48)
,E/AndroidRuntime( 4871): FATAL EXCEPTION: main
E/AndroidRuntime( 4871): Process: com.test.thalitest, PID: 4871,
E/AndroidRuntime( 4871): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4871): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4871): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4871): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4871): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4871): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4871): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4871): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4871): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4871): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4871): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4871): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4871): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4871): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4871): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4871): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4871): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4871): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4871): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  967):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3 f}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 5152): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5152): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5152): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5152): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5152): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5152): Remote Branch: 
I/Adreno-EGL( 5152): Local Patches: 
I/Adreno-EGL( 5152): Reconstruct Branch: 
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinRequestBuilder( 1947): Classify the device as Phone.
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,I/CheckinTask( 1947): Sending checkin request (11620 bytes)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
W/ActivityManager(  967): Activity pause timeout for ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{439a2658 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1869): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:24:6
,D/UpdateThreadPoolManager( 1869): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1869): 2 : quick cover state : opened : 0
,D/WeatherService( 1869): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1869): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1869): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1869): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1869): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1869): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:24:6
,D/WeatherService( 1869): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1869): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1869): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1869): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1869): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1869): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1869): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1869): 2 : This is isUpdating : false
D/WeatherService( 1869): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1869): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1869): 2 : Map key string is -2
,D/lim     ( 1869): 2 : time = 01:24
I/WeatherReflect( 1869): Model Name : LG-D802
D/WeatherTheme( 1869): 2 : Different view - status_min_formatted : 22 != 24
,D/WeatherTheme( 1869): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1869): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1869): 2 : Fixed theme : optimus
,D/WeatherTheme( 1869): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1869): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1869): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1869): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1869): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1210): Disconnected process message: 10
,D/HeadsetStateMachine( 1210): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,D/dalvikvm( 1160): GC_CONCURRENT freed 2885K, 11% free 25444K/28508K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 1144): GC_FOR_ALLOC freed 7414K, 10% free 70970K/78832K, paused 59ms, total 62ms
,D/dalvikvm( 1490): GC_CONCURRENT freed 5519K, 9% free 60855K/66560K, paused 2ms+4ms, total 36ms
,D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 29ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1947): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1947): Failed to find provider info for com.google.android.wearable.settings
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/dalvikvm( 1554): GC_EXPLICIT freed 533K, 29% free 17845K/24832K, paused 1ms+4ms, total 33ms
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,W/CheckinRequestBuilder( 1947): awaiting user notification for token
,I/CheckinRequestBuilder( 1947): Classify the device as Phone.
,I/CheckinTask( 1947): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1947): Checking schedule, now: 1450484646854 next: 1451062042851
,I/CheckinService( 1947): active receiver: disabled
,D/dalvikvm( 1490): GC_FOR_ALLOC freed 4798K, 9% free 61905K/67428K, paused 23ms, total 23ms
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1} time:121405
,D/dalvikvm(  967): GC_CONCURRENT freed 2294K, 47% free 30818K/57592K, paused 3ms+9ms, total 111ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 107ms
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43677f88: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@42e3ff18 time:121452
,D/UsbSettings( 2616): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2616): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2616): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2616): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{437ae410 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2031): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1554): Connected
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1554): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] request level :IDLE....
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
,D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3827): isOpenOperator : true
,D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,I/AppUp4:CustModeStarterReceiver( 3827): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 3827): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3827): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 3827): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3827): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3827): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4997): DownloadService onCreate
,D/EAS     ( 4790): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4997): in removeSpuriousFiles
,D/EAS     ( 4790): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4997): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/eas_req ( 4790): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e8a2a8 on behalf of 4997
,I/DownloadManager( 4997): in trimDatabase
,V/DownloadManager( 4997): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4997): DownloadService onStartCommand
,V/DownloadManager( 4997): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4480): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4480): action = android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/LgeMiscReceiver( 4480): networkInfo.isConnected() = false
,V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e8b910 on behalf of 4997
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e8de30 on behalf of 4997
,D/MobileConnectivityChangeReceiver( 5036): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/Settings( 4790): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/MobileConnectivityChangeReceiver( 5036): onReceive CONNECTIVITY_CHANGE networkType=1
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2888): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4997): DownloadService onDestroy
,D/LGDMSGCM( 5107): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2888): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2888): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 5107): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5120): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5120): CONNECT : WIFI_CONNECT
E/LGDMClient( 2888): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2888): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2888): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2888): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
,D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3827): isOpenOperator : true
,D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,I/AppUp4:CustModeStarterReceiver( 3827): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4997): DownloadService onCreate
,I/DownloadManager( 4997): in removeSpuriousFiles
,V/DownloadManager( 4997): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4790): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4790): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e92118 on behalf of 4997
,I/DownloadManager( 4997): in trimDatabase
,V/DownloadManager( 4997): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4997): DownloadService onStartCommand
,V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e93d60 on behalf of 4997
,V/DownloadManager( 4997): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4480): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4480): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4480): networkInfo.isConnected() = true
D/PhoneState( 4480): setPdpRejectCasuse : false
W/Settings( 4790): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e95cf8 on behalf of 4997
,D/MobileConnectivityChangeReceiver( 5036): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5036): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4997): DownloadService onDestroy
,D/LGDMClient( 2888): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2888): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5107): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2888): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 5120): connectivityManager.getNetworkInfo = TYPE_WIFI
,W/ContextImpl( 5107): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Wireless_Storage( 5120): CONNECT : WIFI_CONNECT
E/LGDMClient( 2888): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2888): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2888): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2888): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1210): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1210): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1490): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
,D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3827): isOpenOperator : true
,D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,I/AppUp4:CustModeStarterReceiver( 3827): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4790): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4997): DownloadService onCreate
,D/EAS     ( 4790): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4480): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4480): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4480): networkInfo.isConnected() = true
,D/PhoneState( 4480): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5036): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5036): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2888): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5107): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5107): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5120): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5120): CONNECT : WIFI_CONNECT
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 4997): in removeSpuriousFiles
D/LGDMClient( 2888): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 4997): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e9a440 on behalf of 4997
I/LGDMClient( 2888): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 4997): in trimDatabase
V/DownloadManager( 4997): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e9b638 on behalf of 4997
W/Settings( 4790): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4997): DownloadService onStartCommand
V/DownloadManager( 4997): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 2888): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2888): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2888): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2888): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4997): created cursor android.database.sqlite.SQLiteCursor@42e9dae8 on behalf of 4997
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
V/DownloadManager( 4997): DownloadService onDestroy
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1210): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1210): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/GAV2    ( 5133): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Killing 4807:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2031): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.463013 Y: -0.383072 Z: 9.749756 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463013 .y:-0.383072 .z:9.749756
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.463760 Y: -0.400696 Z: 9.763733 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463760 .y:-0.400696 .z:9.763733
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4404): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4404): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Killing 4932:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2031): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,E/SlideAside( 3814): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3814): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/administrator(  967): Handling package changes for user 0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5364 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
,D/dalvikvm(  269): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+4ms, total 58ms
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 25ms
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 24ms
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5364): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5364): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5364): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1210): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  967): battery changed pluggedType: 2
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/MediaCodecList( 5364): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/Babel   ( 5364): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5364): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5364): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5364): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5364): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5364): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5364): MmsConfig.loadFromDatabase
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 5364): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5364): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5364): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5364): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5364): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5364): MmsConfig.loadFromResources
,E/Babel   ( 5364): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5364): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1427): DISABLE
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5364): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5364): [loadRssi] File not exist 
V/LGRssiData( 5364): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5364): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5364): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5364): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5364): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3827): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3827): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3827): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3827): isOpenOperator : true
D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3827): begin check event
D/AppUp4:Utils( 3827): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3827): Event For Nothing, skip.
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5415 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5415): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5415): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5415): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5415): BUILD Country: EU
,I/SystemConfig( 5415): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4968:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5431 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
,I/SystemConfig( 5415): systemFeature RCS result false
,D/SystemConfig( 5415): refreshRcsSupport() :false
I/ActivityManager(  967): Killing 4871:com.test.thalitest/u0a304 (adj 15): empty #17
,D/HyLog   ( 5431): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5431): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5431): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/WindowState(  967): WIN DEATH: Window{443b5898 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  967): Client connection lost with reason: 4
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/[LGHome]EVENT( 1490): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{454c0f60 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
I/InputMethodManagerService(  967): IME STATUS OFF
,W/Binder  ( 1316): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1316): java.lang.NullPointerException
W/Binder  ( 1316): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1316): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1316): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1316): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4871 uid 10304
,I/ActivityManager(  967): Killing 4997:android.process.media/u0a23 (adj 15): empty #17
I/IcingCorporaProvider( 2686): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1947): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1947): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  967): Delaying start of: ServiceRecord{43e24ea8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1947): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1947): GC_CONCURRENT freed 1886K, 21% free 19632K/24832K, paused 2ms+3ms, total 43ms
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/IcingCorporaProvider( 2686): UpdateCorporaTask done [took 224 ms] updated apps [took 224 ms] 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2031): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2031): nl80211: survey data missing!
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/GAV4    ( 5364): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2031): nl80211: survey data missing!
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
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8464 usec
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.471375 Y: -0.382019 Z: 9.785889 
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449158 Y: -0.379791 Z: 9.776993 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.471375 .y:-0.382019 .z:9.785889
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.458542 Y: -0.367783 Z: 9.788818 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458542 .y:-0.367783 .z:9.788818
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  398): sns_pwr.c(292):acquiring wakelock
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
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.470535 Y: -0.381638 Z: 9.782990 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470535 .y:-0.381638 .z:9.782990
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.458038 Y: -0.370819 Z: 9.786194 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458038 .y:-0.370819 .z:9.786194
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.458496 Y: -0.374878 Z: 9.785126 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458496 .y:-0.374878 .z:9.785126
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.471832 Y: -0.376343 Z: 9.781052 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471832 .y:-0.376343 .z:9.781052
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44f3c690)
,D/KeyguardViewMediator( 1144): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1144): notifyScreenOnLocked
D/KeyguardViewMediator( 1144): handleNotifyScreenOn
,D/KeyguardViewManager( 1144): onScreenTurnedOn()
V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
I/WindowManager(  967): No lock screen! windowToken=null
,D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb875f450
,D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,E/SlideAside( 3814): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.453766 Y: -0.374313 Z: 9.766129 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453766 .y:-0.374313 .z:9.766129
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2031): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2031): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2031): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2031): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  271): ParamSet string: screen_state=on
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1160): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1160): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{42e34748 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1160): enqueuing start. mLedList.size()=2
,I/EmotionalLed( 1160): updateLightsLocked() start. mLedList.size=3
D/qdlights( 1160): set_light_notifications: 0,0,0,0,3
,D/WeatherAncestor( 1869): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:24:23
,E/CliptrayService( 1160): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1160): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1160): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,I/SlideAside( 3814): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1869): 2 : This is isUpdating : false
,D/WeatherAncestor( 1869): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:24:23
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1869): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1869): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1869): 2 : TimeTick Receiver Unregister
D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
D/WeatherService( 1869): 2 : shouldTimeTickRegistered : false
D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1160): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1160): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1160): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1160): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1160): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1160): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1160): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1160): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1160): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 406ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1160): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1160): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484664111, nextTick: 35922, mDrawingTime: 0
D/qdlights( 1160): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1160): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484664131, nextTick: 35902, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
D/qdlights( 1160): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1160): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 165, B = 165
,D/WeatherService( 1869): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:24:24
D/WeatherService( 1869): 2 : ACTION screen on
,D/WeatherService( 1869): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1869): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:24:24
,D/qdlights( 1160): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 159, B = 159
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
D/qdlights( 1160): set_light_notifications: 2,ff009999,10,0,2
E/Parcel  (  420): Reading a NULL string not supported here.
D/qdlights( 1160): [Current] = 255, R = 0, G = 153, B = 153
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1160): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 147, B = 147
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1144): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1144): notifyScreenOffLocked
,I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
I/LGImmersionVibrator(  967): Vibrator off
,D/KeyguardViewMediator( 1144): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1160): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 141, B = 141
D/KeyguardViewMediator( 1144): handleNotifyScreenOff
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1}
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/KeyguardViewManager( 1144): onScreenTurnedOff()
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
,D/WifiStateMachine(  967): handleScreenStateChanged: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1160): usb Uevent not necessary.
,V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{43229cf8 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/qdlights( 1160): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 135, B = 135
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WifiController(  967): CMD_SCREEN_OFF 
,D/WifiController(  967): shouldWifiStayAwake TRUE
D/qdlights( 1160): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 129, B = 129
,D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd  len = 0, 0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/EmotionalLed( 1160): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1160): clear
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
D/qdlights( 1160): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 123, B = 123
E/CliptrayService( 1160): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
,I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1160): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 117, B = 117
,E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/qdlights( 1160): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 111, B = 111
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WeatherService( 1869): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:24:24
D/WeatherService( 1869): 2 : ACTION screen off
,D/WeatherService( 1869): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:24:24
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1160): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 105, B = 105
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
D/NfcService( 1477): NFC-C OFF
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
D/qdlights( 1160): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1160): [Current] = 255, R = 0, G = 99, B = 99
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1160): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1160): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1160): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1160): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1160): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1160): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1160): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1160): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1160): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1160): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1160): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1160): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1160): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1160): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1160): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1160): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1160): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1160): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1160): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  398): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardViewMediator( 1144): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1144): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/KeyguardViewMediator( 1144): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1144): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484682300835205; DSPS: 5276890; Offset: 1450484521262932373
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  967): GC_EXPLICIT freed 2883K, 47% free 30768K/57064K, paused 3ms+11ms, total 134ms
,I/GoogleURLConnFactory( 1554): Using platform SSLCertificateSocketFactory
,I/VacuumService( 1554): Vacuum at: now=1450484689525 tag=VacuumService
,I/GoogleURLConnFactory( 1554): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1554): No account for auth token provided
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1554): GC_CONCURRENT freed 1799K, 28% free 18083K/24832K, paused 25ms+5ms, total 91ms
,W/Uploader( 1554): No account for auth token provided
,W/Uploader( 1554): No account for auth token provided
,W/Uploader( 1554):  no longer exists, so no auth token.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1210): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1160): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484700044, nextTick: 59988, mDrawingTime: 0
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484700048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484702302284552; DSPS: 5932297; Offset: 1450484521262947394
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484722302723310; DSPS: 6587671; Offset: 1450484521262958906
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484742303197038; DSPS: 7243047; Offset: 1450484521262944353
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484760048, nextTick: 59984, mDrawingTime: 0
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484760050, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484762304170229; DSPS: 7898439; Offset: 1450484521262940981
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484782305509152; DSPS: 8553843; Offset: 1450484521262937131
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484802306831311; DSPS: 9209246; Offset: 1450484521262947034
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484820043, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484820056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484822307715532; DSPS: 9864635; Offset: 1450484521262946245
,D/wpa_supplicant( 2031): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 7 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 8 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 9 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 3 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 10 BSSID fc:6f:b7:3e:78:0a SSID 'UPC249917252' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 11 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 4 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 06:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 fc:94:e3:11:35:3a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 fe:94:e3:11:35:3c]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 64:7c:34:38:27:cc]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 fc:6f:b7:3e:78:0a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 64:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484842309074465; DSPS: 10520039; Offset: 1450484521262962405
,D/dalvikvm( 2673): GC_CONCURRENT freed 7723K, 32% free 16929K/24832K, paused 4ms+2ms, total 40ms
,D/dalvikvm( 2673): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4559e740: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1554): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1554): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1554): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1554): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1554): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4404): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4404): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4404): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4404): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4404): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4404): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4404): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4404): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4404): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4404): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484862310576252; DSPS: 11175449; Offset: 1450484521262938313
,I/LocationManagerService(  967): remove 4398e5d8
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2673): GC_CONCURRENT freed 2006K, 32% free 16971K/24832K, paused 10ms+2ms, total 36ms
,D/dalvikvm( 2673): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2673): GC_CONCURRENT freed 1788K, 31% free 17176K/24832K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2673): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2673): GC_FOR_ALLOC freed 1229K, 31% free 17327K/24832K, paused 19ms, total 19ms
,I/Mlt MonitorService( 2673): parseLastkmsg to dump
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484880043, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484880057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484882312024157; DSPS: 11830856; Offset: 1450484521262951892
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484902314824670; DSPS: 12486308; Offset: 1450484521262944788
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484922316200993; DSPS: 13141713; Offset: 1450484521262947820
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484940064, nextTick: 59967, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450484940067, nextTick: 59966, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484942317613577; DSPS: 13797119; Offset: 1450484521262956595
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1210): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484962318514200; DSPS: 14452509; Offset: 1450484521262941691
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450484982319406269; DSPS: 15107898; Offset: 1450484521262948750
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485000034, nextTick: 59991, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485000040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485002320774867; DSPS: 15763303; Offset: 1450484521262944057
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485022322097237; DSPS: 16418706; Offset: 1450484521262954171
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485042324010323; DSPS: 17074129; Offset: 1450484521262944650
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485060048, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485060051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485062325406459; DSPS: 17729535; Offset: 1450484521262936977
,D/wpa_supplicant( 2031): nl80211: Event message available
D/wpa_supplicant( 2031): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2031): nl80211: Disconnect event
D/wpa_supplicant( 2031): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2031): wlan0: Deauthentication notification
D/wpa_supplicant( 2031): wlan0:  * reason 0
D/wpa_supplicant( 2031): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2031): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2031): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2031): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2031): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2031): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2031): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2031): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2031): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  967): handleMessage: E msg.what=147460,
D/WifiStateMachine(  967): processMsg: ConnectedState,
,D/WifiStateMachine(  967): processMsg: L2ConnectedState,
D/WifiStateMachine(  967): processMsg: ConnectModeState,
D/WifiStateMachine(  967): Network connection lost
,D/WifiStateMachine(  967): Stopping DHCP and clearing IP,
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1,
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb80f7d6c key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2031):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2031): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT),
D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=5
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2031): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31,
D/wpa_supplicant( 2031): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2031): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2031): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
,D/DhcpStateMachine(  967): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  265): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/wpa_supplicant( 2031): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2031): wlan0: nl80211: scan request
,D/wpa_supplicant( 2031): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiHS20(  967): hidePasspointNotification off =false
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2031): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2031): nl80211: Event message available
D/wpa_supplicant( 2031): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2031): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
D/QCNEA   (  420): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  420): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  420): |CAC| updateNetCfgInfo
V/QCNEA   (  420): |CAC| *********************************************
V/QCNEA   (  420): |CAC|                   Netconfig               
V/QCNEA   (  420): |CAC| *********************************************
V/QCNEA   (  420): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  420): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  420): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  420): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  420): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  420): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  420): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  420): |CAC| *********************************************
D/QCNEA   (  420): |CAC| Received bssid= 
D/QCNEA   (  420): |CAC| net type = 3
V/QCNEA   (  420): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  420): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  420): |CAC| 	ssid           =NG700
V/QCNEA   (  420): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  420): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  420): |CAC| *********************************************
D/QCNEA   (  420): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  420): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  420): |CAC| dispatchNetCfg: updating:0xb7c3c8dc
,D/QCNEA   (  420): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5937 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  967): handleMessage: X
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  265): RouteController
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5937): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5937): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5937): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,I/PCSuite ( 5937): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5937): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5937): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  265): RouteController
W/NetworkManagementService(  967): route cmd failed: 
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
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x62859fe0 clazz=0xb3e00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5981 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  967): Killing 4790:com.lge.email/u0a24 (adj 15): empty #17
,V/NativeCrypto( 1554): Read error: ssl=0x63f23578: I/O error during system call, Connection timed out
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,V/NativeCrypto( 1554): SSL shutdown failed: ssl=0x63f23578: I/O error during system call, Broken pipe
,D/HyLog   ( 5981): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5981): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5981): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  967): StoppedState
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/QRemote ( 5981): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
D/QRemote ( 5981): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5981): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 5981): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5981): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 5981): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 5981): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5981): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5981): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 5036:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
,D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3827): isOpenOperator : true
,D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,I/AppUp4:CustModeStarterReceiver( 3827): Event For GoodConnectivity
,D/wpa_supplicant( 2031): nl80211: Event message available
D/wpa_supplicant( 2031): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2031): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2031): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2031): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2031): nl80211: Survey data missing
D/wpa_supplicant( 2031): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 12 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Add new id 13 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2031): wlan0: New scan results available
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2031): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2031): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2031): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2031): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2031): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2031): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2031): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2031): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2031): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2031): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2031): wlan0: 2: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-88 wps
D/wpa_supplicant( 2031): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2031): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2031): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2031): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2031): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2031): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2031): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2031): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2031): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2031): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb80f95a8  current_ssid=0x0
D/wpa_supplicant( 2031): scard is not null..
D/wpa_supplicant( 2031): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:0,0:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2031): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2031): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2031): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2031): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2031): wlan0: Cancelling scan request
D/wpa_supplicant( 2031): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2031): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2031): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2031): RSN: PMKSA cache search - network_ctx=0xb80f95a8 try_opportunistic=0
D/wpa_supplicant( 2031): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2031): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2031): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2031): wlan0: WPA: clearing AP WPA IE,
,D/wpa_supplicant( 2031): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2031): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2031): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2031): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2031): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2031): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2031): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2031): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2031): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2031): nl80211: Unsubscribe mgmt frames handle 0xb80f8590 (mode change)
D/wpa_supplicant( 2031): nl80211: Subscribe to mgmt frames with non-AP handle 0xb80f8590,
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590,
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590,
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09,
,D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
,D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2031): nl80211: Register frame type=0xd0 nl_handle=0xb80f8590
,D/wpa_supplicant( 2031): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/wpa_supplicant( 2031): nl80211: Connect (ifindex=23),
D/wpa_supplicant( 2031):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031):   * freq=2412
D/wpa_supplicant( 2031):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2031):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031):   * Auth Type 0
D/wpa_supplicant( 2031):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 a0:c5:62:7a:49:97]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 2031): nl80211: Connect request send successfully
D/wpa_supplicant( 2031): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2031): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState,
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2031): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987',
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=6012 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 6012): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6012): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6012): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6012): DownloadService onCreate
,I/DownloadManager( 6012): in removeSpuriousFiles
,V/DownloadManager( 6012): DownloadService onStartCommand
I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6041 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/wpa_supplicant( 2031): nl80211: Event message available
D/wpa_supplicant( 2031): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2031): nl80211: Connect event
D/wpa_supplicant( 2031): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2031): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2031): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2031): wlan0: Association info event
D/wpa_supplicant( 2031): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2031): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2031): wlan0: freq=2412 MHz
D/wpa_supplicant( 2031): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2031): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2031): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2031): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): scard is not null..
D/wpa_supplicant( 2031): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2031): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2031): TDLS: Remove peers on association
D/wpa_supplicant( 2031): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2031): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2031): EAPOL: enable timer tick
D/wpa_supplicant( 2031): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2031): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2031): wlan0: Cancelling scan request
D/wpa_supplicant( 2031): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 20,31): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,V/DownloadManager( 6012): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e82de8 on behalf of 6012
,V/DownloadManager( 6012): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 6012): in trimDatabase
,V/DownloadManager( 6012): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e85c78 on behalf of 6012
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e85f40 on behalf of 6012
D/HyLog   ( 6041): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6041): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6041): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 6012): DownloadService onDestroy
I/ActivityManager(  967): Killing 5052:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/wpa_supplicant( 2031): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e8 3d 8b 09 aa ae 91 f8 e5 82 ff 0b 77 02 87 ...
D/wpa_supplicant( 2031): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2031): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2031): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2031): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2031): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2031):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2031):   key_nonce - hexdump(len=32): e8 3d 8b 09 aa ae 91 f8 e5 82 ff 0b 77 02 87 2e 73 db f4 f5 f6 75 79 aa fb 02 8b 08 5b be e9 9b
D/wpa_supplicant( 2031):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e8 3d 8b 09 aa ae 91 f8 e5 82 ff 0b 77 02 87 ...
D/wpa_supplicant( 2031): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/LGEmail ( 6041): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/wpa_supplicant( 2031): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2031): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2031): Get randomness: len=32 entropy=4
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2031): WPA: Renewed SNonce - hexdump(len=32): 3f f3 2c fa 8b bd 73 4a fc 5e 44 b8 0b b7 d0 dc 6a 8f 25 c0 f3 47 7b 04 22 3e cc 49 d1 72 fc d6
D/wpa_supplicant( 2031): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): WPA: Nonce1 - hexdump(len=32): 3f f3 2c fa 8b bd 73 4a fc 5e 44 b8 0b b7 d0 dc 6a 8f 25 c0 f3 47 7b 04 22 3e cc 49 d1 72 fc d6
D/wpa_supplicant( 2031): WPA: Nonce2 - hexdump(len=32): e8 3d 8b 09 aa ae 91 f8 e5 82 ff 0b 77 02 87 2e 73 db f4 f5 f6 75 79 aa fb 02 8b 08 5b be e9 9b
D/wpa_supplicant( 2031): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2031): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2031): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2031): wlan0: WPA: Sending EAPOL-Key 2/4
,D/wpa_supplicant( 2031): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2031): WPA: Derived Key MIC - hexdump(len=16): 8b e8 05 8c 6f 99 58 b5 1b 2c 0b 8e 59 a2 ea 87
D/wpa_supplicant( 2031): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 3f f3 2c fa 8b bd 73 4a fc 5e 44 b8 0b b7 d0 ...
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 2031): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2031): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e8 3d 8b 09 aa ae 91 f8 e5 82 ff 0b 77 02 87 ...
D/wpa_supplicant( 2031): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2031): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2031): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2031): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2031):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2031):   key_nonce - hexdump(len=32): e8 3d 8b 09 aa ae 91 f8 e5 82 ff 0b 77 02 87 2e 73 db f4 f5 f6 75 79 aa fb 02 8b 08 5b be e9 9b
D/wpa_supplicant( 2031):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_rsc - hexdump(len=8): 8b 85 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2031):   key_mic - hexdump(len=16): f3 8e d3 4b d6 62 2d f7 61 fc db 91 ad e0 ca 96
D/wpa_supplicant( 2031): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e8 3d 8b 09 aa ae 91 f8 e5 82 ff 0b 77 02 87 ...
D/wpa_supplicant( 2031): RSN: encrypted key data - hexdump(len=56): 3c 7f fb c1 43 6f c4 d0 95 04 96 db 45 04 ee 5a a4 1e ec cb 1e 69 3a 84 9a 08 b2 1d f2 58 8c 97 ...
D/wpa_supplicant( 2031): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2031): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2031): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2031): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2031): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2031): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2031): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2031): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2031): WPA: Derived Key MIC - hexdump(len=16): 19 03 a1 ce 67 99 43 cc 72 1c 87 27 ef 70 d7 78
D/wpa_supplicant( 2031): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2031): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb80f8c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2031):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2031): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2031): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2031): WPA: Group Key - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 2031): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2031): WPA: RSC - hexdump(len=6): 8b 85 00 00 00 00
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ed503a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2031):    broadcast key
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
I/wpa_supplicant( 2031): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2031): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2031): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2031): netlink: Operstate: linkmode=-1, operstate=6,
D/wpa_supplicant( 2031): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2031): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2031): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2031): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2031): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 2031): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2031): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2031): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2031): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2031): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2031): EAPOL authentication completed successfully
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2031): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2031): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2031): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
,D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
,D/wpa_supplicant( 2031): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
,E/Parcel  (  420): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): ObtainingIpState{ when=-22ms what=147462 obj=android.net.wifi.StateChangeResult@44f9ecd8 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-15ms what=147462 obj=android.net.wifi.StateChangeResult@43881230 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-16ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/LGEmail ( 6041): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/BaseRuntimeLoader( 6041): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6041): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6041): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6041): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/EAS     ( 6041): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6041): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2031): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2031): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2031): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
,D/eas_req ( 6041): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  967):    returned null
,D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e614b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e614b8 target=com.android.internal.util.StateMachine$SmHandler }
,I/LgeMiscReceiver( 4480): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4480): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4480): networkInfo.isConnected() = false
,D/CommandListener(  265): Setting iface cfg
W/linker  ( 6041): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/CommandListener(  265): Trying to bring up wlan0
,D/HtmlEditor( 6041): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6041): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 6041): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 6041): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/WifiStateMachine(  967): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/HtmlEditor( 6041): register_HtmlEditor, Success
,D/HtmlEditor( 6041): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6041): register_HtmlEditorTimer, Success
D/HtmlEditor( 6041): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  967): handleMessage: X
D/HtmlEditor( 6041): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6041): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6041): register_HtmlEditorFont, Success
,D/HtmlEditor( 6041): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6041): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 6041): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6041): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6041): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6041): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 6041): JNI_OnLoad Success
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-10ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
,I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6062 uid=10052 gids={50052, 3003}
D/WifiStateMachine(  967): ObtainingIpState{ when=-10ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
I/HubEmail( 6041): JNI_OnLoad()
I/HubEmail( 6041): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6041): registerNatives()
I/HubEmail( 6041): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6041): registerNativeMethods()
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
I/HubEmail( 6041): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd  len = 0, 0
W/Settings( 6041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2031): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2031): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2031): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2031): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2031): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2031): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  967): handleMessage: X
,D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,E/Parcel  (  420): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
,D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  967): handleMessage: X
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/HyLog   ( 6062): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/HyLog   ( 6062): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6062): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
E/Parcel  (  420): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  967): Killing 5078:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/KeyguardUpdateMonitor( 1144): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1160): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  420): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/Parcel  (  420): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  420): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,V/LGRssiData( 6062): [loadRssi] File not exist 
V/LGRssiData( 6062): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6062): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 6062): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6062): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 6062): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
W/BaseRuntimeLoader( 6062): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 6062): onReceive CONNECTIVITY_CHANGE networkType=1
W/BaseRuntimeLoader( 6062): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 6062): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6062): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6062): [getValue] FEATURE key : vzw_roaming_state, value : null
I/RemoteControlStatusBar( 1144): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  265): RouteController
,V/        (  265): RouteController
I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6084 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 5107:com.lge.lgdmsgcm/1000 (adj 15): empty #17
E/PhoneMonitor( 6062): onOtaspChanged old =0, new =3
V/PhoneMonitor( 6062): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
V/        (  265): RouteController
V/        (  265): RouteController
,D/HyLog   ( 6084): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6084): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6084): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  265): RouteController
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,I/CheckinService( 1947): Checking schedule, now: 1450485073066 next: 1450484676851
,I/CheckinService( 1947): active receiver: enabled
,V/        (  265): RouteController
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,I/CheckinService( 1947): Preparing to send checkin request
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/QCNEA   (  420): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  420): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  420): |CAC| updateNetCfgInfo
V/QCNEA   (  420): |CAC| *********************************************
V/QCNEA   (  420): |CAC|                   Netconfig               
V/QCNEA   (  420): |CAC| *********************************************
V/QCNEA   (  420): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  420): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  420): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  420): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  420): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  420): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  420): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  420): |CAC| *********************************************
D/QCNEA   (  420): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  420): |CAC| net type = 1
V/QCNEA   (  420): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  420): |CAC| Received ssid= NG700
V/QCNEA   (  420): |CAC| 	ssid           =NG700
V/QCNEA   (  420): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  420): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  420): |CAC| *********************************************
D/QCNEA   (  420): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  420): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  420): |CAC| dispatchNetCfg: updating:0xb7c3c8dc
,D/QCNEA   (  420): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/EventLogService( 1947): Accumulating logs since 1450484644609
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinRequestBuilder( 1947): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1947): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6119 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  967): Killing 5120:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/HyLog   ( 6119): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6119): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6119): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/LGDMClient( 2888): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2888): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  967): Killing 5133:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
I/LGDMClient( 2888): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6133 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,E/LGDMClient( 2888): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2888): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2888): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2888): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  967): GC_EXPLICIT freed 2439K, 47% free 30669K/57064K, paused 5ms+9ms, total 126ms
,D/HyLog   ( 6133): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6133): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6133): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 6133): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6147 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  967): Killing 5152:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6147): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6147): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6147): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  269): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 31ms
,I/NFS     ( 6147): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6147): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 6147): intf.getDisplayName() = lo
I/Wireless_Storage( 6147): intf.getDisplayName() = sit0
I/Wireless_Storage( 6147): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6147): intf.getDisplayName() = teql0
I/Wireless_Storage( 6147): intf.getDisplayName() = wlan0
,D/NFS     ( 6147): interface name:wlan0 name:wlan0
D/NFS     ( 6147): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6147): interface name:wlan0 name:wlan0
D/NFS     ( 6147): addr:192.168.1.144 broadcast:192.168.1.255
I/Wireless_Storage( 6147): CONNECT : WIFI_CONNECT
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 26ms
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 26ms
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6162 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 5364:com.google.android.talk/u0a77 (adj 15): empty #17
,D/HyLog   ( 6162): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6162): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6162): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 6162): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x42ead190: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1947): awaiting user notification for token
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6180 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6180): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6180): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6180): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6180): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6180): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 6180): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6180): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6180): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6180): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6180): install
,I/MultiDex( 6180): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/wpa_supplicant( 2031): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2031): EAPOL: disable timer tick
,I/MultiDex( 6180): loading existing secondary dex files
,I/MultiDex( 6180): load found 3 secondary dex files
,I/MultiDex( 6180): install done
,D/dalvikvm( 6180): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6180): VFY: unable to resolve instance field 61
,D/dalvikvm( 6180): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6180): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6180): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6180): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 6180): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6180): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6180): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6180): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6180): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6180): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e422f0
D/dalvikvm( 6180): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e422f0
,D/dalvikvm( 6180): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e422f0, skipping init
,D/dalvikvm( 6180): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e422f0
D/dalvikvm( 6180): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e422f0
,V/JNIHelp ( 6180): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 6162): Binding Chromium to the main looper Looper (main, tid 1) {42e3ad00}
,I/chromium( 6162): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6162): Initializing chromium process, renderers=0
,W/chromium( 6162): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6162): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6162): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6162): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6162): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6162): Remote Branch: 
I/Adreno-EGL( 6162): Local Patches: 
I/Adreno-EGL( 6162): Reconstruct Branch: 
,D/dalvikvm( 6180): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42e422f0
,D/dalvikvm( 6180): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42e422f0
D/dalvikvm( 6180): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42e422f0
,D/dalvikvm( 6180): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42e422f0
,I/NSApplication( 6162): Starting up...
,I/ActivityManager(  967): Killing 5415:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 5981): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5981): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5981): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5981): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/ProviderInstaller( 6180): Installed default security provider GmsCore_OpenSSL
,D/QRemote ( 5981): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5981): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5937): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5937): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5981): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5981): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5981): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5981): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1554): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1554): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1947): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1838): callingUid 10006, callindPid: 1838
,E/MDM     ( 1427): [73] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1947): Restart initialization of location
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/dalvikvm( 6180): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6180): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 6180): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6180): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6180): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 6180): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ea1000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ea1000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=3293189027
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6180): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x430375b8
D/dalvikvm( 6180): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x430375b8
,D/dalvikvm( 6180): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x430375b8, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 6180): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6221): DexOpt: load 5ms, verify+opt 7ms, 128132 bytes
,D/dalvikvm( 6180): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6180): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 112ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 6180): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6180): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6180): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6180): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6180): Remote Branch: 
I/Adreno-EGL( 6180): Local Patches: 
I/Adreno-EGL( 6180): Reconstruct Branch: 
,I/Adreno-EGL( 6180): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6180): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6180): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6180): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6180): Remote Branch: 
I/Adreno-EGL( 6180): Local Patches: 
I/Adreno-EGL( 6180): Reconstruct Branch: 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=2214743350
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/WifiStateMachine(  967): handleMessage: X
,D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1,
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 6180): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 6180): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6180): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6180): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6180): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6180): Remote Branch: 
I/Adreno-EGL( 6180): Local Patches: 
I/Adreno-EGL( 6180): Reconstruct Branch: 
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,I/CheckinRequestBuilder( 1947): Classify the device as Phone.
,V/NativeCrypto( 1947): SSL shutdown failed: ssl=0x6bf78218: I/O error during system call, Connection timed out
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
,D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
,D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3827): isOpenOperator : true
,D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/SIMObserver( 4350): simInfo1
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,I/AppUp4:CustModeStarterReceiver( 3827): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 3827): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3827): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 3827): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3827): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3827): handleAsyncCustNotification do not startCustService
,D/EAS     ( 6041): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6012): DownloadService onCreate
,D/EAS     ( 6041): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6041): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4480): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4480): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4480): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6062): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6062): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2888): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6133): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NFS     ( 6147): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6147): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2888): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 6012): in removeSpuriousFiles
,I/LGDMClient( 2888): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 6012): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e8c778 on behalf of 6012
,I/DownloadManager( 6012): in trimDatabase
V/DownloadManager( 6012): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/Settings( 6041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e8d920 on behalf of 6012
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6012): DownloadService onStartCommand
,V/DownloadManager( 6012): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,E/LGDMClient( 2888): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2888): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2888): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e8fe20 on behalf of 6012
,I/LGDMClient( 2888): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 6012): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
,D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3827): isOpenOperator : true
D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,I/AppUp4:CustModeStarterReceiver( 3827): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6012): DownloadService onCreate
I/DownloadManager( 6012): in removeSpuriousFiles
,D/EAS     ( 6041): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 6012): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 6041): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6012): DownloadService onStartCommand
V/DownloadManager( 6012): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e944a8 on behalf of 6012
I/DownloadManager( 6012): in trimDatabase
V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e969d0 on behalf of 6012
,V/DownloadManager( 6012): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e97aa0 on behalf of 6012
I/LgeMiscReceiver( 4480): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4480): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4480): networkInfo.isConnected() = true
D/PhoneState( 4480): setPdpRejectCasuse : false
,V/DownloadManager( 6012): DownloadService onDestroy
,W/Settings( 6041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 6062): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6062): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2888): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2888): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6133): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2888): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 6147): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6147): CONNECT : WIFI_CONNECT
,W/ContextImpl( 6133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2888): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2888): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2888): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2888): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/NativeCrypto( 1947): SSL shutdown failed: ssl=0x6b944cf8: I/O error during system call, Connection timed out
,I/CheckinTask( 1947): Sending checkin request (11622 bytes)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1554): Connected
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3827): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
,D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
,D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3827): isOpenOperator : true
,D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,I/AppUp4:CustModeStarterReceiver( 3827): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 6041): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6012): DownloadService onCreate
,D/EAS     ( 6041): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4480): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4480): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4480): networkInfo.isConnected() = true
,D/PhoneState( 4480): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6062): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6062): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2888): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6133): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6133): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6147): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6147): CONNECT : WIFI_CONNECT
,I/DownloadManager( 6012): in removeSpuriousFiles
,V/DownloadManager( 6012): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2888): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e9bd98 on behalf of 6012
,I/LGDMClient( 2888): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 6012): in trimDatabase
,V/DownloadManager( 6012): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e9d790 on behalf of 6012
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6012): DownloadService onStartCommand
,W/Settings( 6041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6012): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,E/LGDMClient( 2888): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42e9f940 on behalf of 6012
,D/LGDMClient( 2888): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2888): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 6012): DownloadService onDestroy
I/LGDMClient( 2888): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinRequestBuilder( 1947): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1947): Failed to find provider info for com.google.android.wearable.settings
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1947): awaiting user notification for token
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x431d7b30: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1947): Classify the device as Phone.
,I/CheckinTask( 1947): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1947): Checking schedule, now: 1450485078348 next: 1451062474345
,I/CheckinService( 1947): active receiver: disabled
,I/CheckinService( 1947): Checking schedule, now: 1450485078377 next: 1451062474345
,I/CheckinService( 1947): active receiver: disabled
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 6162): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1554): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/ActivityManager(  967): Killing 5431:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485082326805296; DSPS: 18384941; Offset: 1450484521262932005
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3814): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3814): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  967): Handling package changes for user 0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6369 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  967): GC_EXPLICIT freed 2684K, 47% free 30751K/57064K, paused 6ms+7ms, total 104ms
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6369): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6369): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Babel   ( 6369): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6369): MmsConfig.loadMmsSettings
I/Babel   ( 6369): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6369): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6369): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 6369): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6369): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6369): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 6369): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6369): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6369): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6369): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6369): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6369): MmsConfig.loadFromResources
,E/Babel   ( 6369): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6369): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 6369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6369): [loadRssi] File not exist 
,V/LGRssiData( 6369): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6369): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4:Utils( 3827): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 3827): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3827): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3827): onReceive
,V/TelephonyAutoProfiling( 6369): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/AppUp4:CustFacade( 3827): Context : android.app.ReceiverRestrictedContext@42e56008
,V/TelephonyAutoProfiling( 6369): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6369): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:CustFacade( 3827): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3827): isOpenOperator : true
,D/AppUp4:CustFacade( 3827): isPhone : true
,I/LicenseContentProvider( 4350): start selecting data
,D/SIMObserver( 4350): simInfo1
,I/AppUp4:EulaManager( 3827): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3827): begin check event
,D/AppUp4:Utils( 3827): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3827): Event For Nothing, skip.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6418 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/HyLog   ( 6418): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6418): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6418): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/GmsNetworkLocationProvi( 1427): DISABLE
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 6418): BUILD Country: EU
,I/SystemConfig( 6418): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4404:com.android.vending/u0a50 (adj 15): empty #17
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6434 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,I/SystemConfig( 6418): systemFeature RCS result false
,D/SystemConfig( 6418): refreshRcsSupport() :false
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): Killing 5937:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6434): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6434): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6434): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  967): Killing 5981:com.lge.qremote/u0a96 (adj 15): empty #17
I/IcingCorporaProvider( 2686): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6450 uid=10050 gids={50050, 3003, 1028, 1015}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6450): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6450): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6450): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6450): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6450): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6450): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6450): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 6450): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6450): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6450): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6450): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6450): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6450): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6450): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6450): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6450): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6450): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 6450): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6450): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x0292
,I/dalvikvm( 6450): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6450): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x029a
,I/IcingCorporaProvider( 2686): UpdateCorporaTask done [took 293 ms] updated apps [took 293 ms] 
,V/DownloadManager( 6012): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6012): created cursor android.database.sqlite.SQLiteCursor@42ea4c58 on behalf of 6450
,I/dalvikvm( 6450): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6450): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x001a
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6450): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6450): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6450): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6450): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6450): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6450): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1947): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  967): Killing 6041:com.lge.email/u0a24 (adj 15): empty #17
I/PackageBroadcastService( 1947): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1947): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm( 1947): GC_CONCURRENT freed 2012K, 22% free 19605K/24832K, paused 6ms+6ms, total 63ms
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6450): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6450): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6450): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6450): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm( 1554): GC_EXPLICIT freed 1534K, 28% free 18074K/24832K, paused 3ms+7ms, total 52ms
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6450): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6450): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6450): Total arena pages for JIT: 11
,I/dalvikvm( 6450): Total arena pages for JIT: 12
,I/dalvikvm( 6450): Total arena pages for JIT: 13
,I/dalvikvm( 6450): Total arena pages for JIT: 14
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6450): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6450): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6450): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6450): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6369): Thread[GAThread,5,main]: No campaign data found.
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/Finsky  ( 6450): [507] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6450): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485102327720262; DSPS: 19040331; Offset: 1450484521262931444
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485120034, nextTick: 59995, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485120047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485122328179047; DSPS: 19695706; Offset: 1450484521262932465
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485142329086576; DSPS: 20351095; Offset: 1450484521262954985
,I/ActivityManager(  967): Killing 6062:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ece0 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485162330016780; DSPS: 21006486; Offset: 1450484521262939144
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485180039, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485180055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485182330900438; DSPS: 21661875; Offset: 1450484521262937792
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485202331355449; DSPS: 22317250; Offset: 1450484521262935039
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485222331823476; DSPS: 22972625; Offset: 1450484521262945303
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485240049, nextTick: 59977, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485240052, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485242332281088; DSPS: 23628000; Offset: 1450484521262945151
,D/wpa_supplicant( 2031): wlan0: BSS: Remove id 12 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2031): wlan0: BSS: Remove id 13 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 a0:c5:62:7a:49:97]
,D/wpa_supplicant( 2031): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485262332735875; DSPS: 24283375; Offset: 1450484521262942174
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485282339864194; DSPS: 24938969; Offset: 1450484521262929380
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485300048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485300050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485302340744974; DSPS: 25594357; Offset: 1450484521262955668
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485322341660230; DSPS: 26249747; Offset: 1450484521262955397
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485342342098289; DSPS: 26905122; Offset: 1450484521262935692
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485360035, nextTick: 59977, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485360049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485362343733919; DSPS: 27560535; Offset: 1450484521262953890
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485382344640892; DSPS: 28215925; Offset: 1450484521262945336
,D/dalvikvm(  967): GC_EXPLICIT freed 1358K, 46% free 30848K/57064K, paused 17ms+14ms, total 198ms
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x43961958: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1554): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1554): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1554): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1554): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1554): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 6450): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6450): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6450): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6450): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6450): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6450): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6450): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6450): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 6450): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6450): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485402345080933; DSPS: 28871299; Offset: 1450484521262958131
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485420035, nextTick: 59991, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485420037, nextTick: 59994, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485422345553368; DSPS: 29526675; Offset: 1450484521262942285
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485442346461729; DSPS: 30182064; Offset: 1450484521262965636
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485462346911830; DSPS: 30837439; Offset: 1450484521262957973,
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485480047, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485480056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485482347374491; DSPS: 31492815; Offset: 1450484521262932353
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485502348291835; DSPS: 32148205; Offset: 1450484521262934169
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485522349218572; DSPS: 32803595; Offset: 1450484521262945379
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485540035, nextTick: 59992, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485540038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485542349675795; DSPS: 33458970; Offset: 1450484521262944838
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485562350151981; DSPS: 34114345; Offset: 1450484521262963261
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485582361629402; DSPS: 34770082; Offset: 1450484521262935555
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485600048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485600051, nextTick: 59977, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485602362069030; DSPS: 35425456; Offset: 1450484521262947937
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485622362520150; DSPS: 36080831; Offset: 1450484521262941293
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485642365548106; DSPS: 36736290; Offset: 1450484521262948009
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485660043, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485660055, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485662366424540; DSPS: 37391679; Offset: 1450484521262939433
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485682366881821; DSPS: 38047054; Offset: 1450484521262938950
,D/dalvikvm( 2673): GC_CONCURRENT freed 2508K, 33% free 16741K/24832K, paused 3ms+7ms, total 67ms
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485702367356923; DSPS: 38702429; Offset: 1450484521262956289
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485720044, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485720056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485722371801468; DSPS: 39357935; Offset: 1450484521262945267
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485742373797298; DSPS: 40013360; Offset: 1450484521262957455
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485762375171257; DSPS: 40668766; Offset: 1450484521262927605
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485780037, nextTick: 59982, mDrawingTime: 6
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485780047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485782376441632; DSPS: 41324167; Offset: 1450484521262946759
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485802377776845; DSPS: 41979571; Offset: 1450484521262939199
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485822379129352; DSPS: 42634975; Offset: 1450484521262948933
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485840028, nextTick: 59978, mDrawingTime: 11
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485840057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485842380563700; DSPS: 43290382; Offset: 1450484521262948954
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485862381884772; DSPS: 43945785; Offset: 1450484521262957771
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485882383885270; DSPS: 44601211; Offset: 1450484521262944108
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485900023, nextTick: 59990, mDrawingTime: 10
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485900046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485902385244791; DSPS: 45256615; Offset: 1450484521262960856
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485922386673256; DSPS: 45912022; Offset: 1450484521262954995
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485942388038548; DSPS: 46567427; Offset: 1450484521262946996
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485960028, nextTick: 59978, mDrawingTime: 12
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450485960063, nextTick: 59970, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485962389416282; DSPS: 47222832; Offset: 1450484521262951439
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/Finsky  ( 6450): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,D/GCM     ( 1554): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/EventLogService( 1947): Aggregate from 1450485073112 (log), 1450483529358 (data)
,I/ConfigFetchService( 1947): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigService( 1554): onCreate
,I/ConfigFetchService( 1947): running network task: configservice_periodic
,I/ConfigFetchService( 1947): service connected
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/WakeLock( 1947): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,D/ConfigFetchService( 1947): ConfigApi connection successful.
,I/ConfigFetchService( 1947): launchTask
I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/ConfigFetchTask( 1947): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WUeSd_95ubyvvjFPmYj6-atUX6oV6ArMjgSwgPBse6hv7xusrlVY6Kg4Cc86QLgiAl3wi9bsD-HfuNpF7V8idGmtQ8T0-7u1zZRJYLBM9M1fQtrH4-XbqIv1oLxeNuyT0DDz6kDxakXpt101d3ENUCTwEWAqk1nRsb1JNDb6g0oaXAtIDlO0gu8JczwtfS0vQY-fjaGvO6tPNkPgQ1DHRvAS-uqsoeAjHvNfYi1obEeU8BZ0w
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 6450): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/GoogleURLConnFactory( 1947): Using platform SSLCertificateSocketFactory
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6450): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigFetchTask( 1947): updating config table for com.google.android.gms
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6450): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/ConfigFetchService( 1947): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,D/Finsky  ( 6450): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
I/ConfigFetchService( 1947): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1947): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1947): fetch service done; releasing wakelock
,D/Finsky  ( 6450): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6450): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,I/ConfigFetchService( 1947): self-hosted config:fetch_interval = 43200
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/ConfigFetchService( 1947): stopping self
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450485982390826128; DSPS: 47878238; Offset: 1450484521262957476
,I/ConfigService( 1554): onDestroy
,D/Finsky  ( 6450): [507] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6450): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486002392297081; DSPS: 48533646; Offset: 1450484521262963585
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486020022, nextTick: 59989, mDrawingTime: 11
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486020057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486022394290974; DSPS: 49189072; Offset: 1450484521262943318
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486042395635831; DSPS: 49844476; Offset: 1450484521262945402
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486062397042399; DSPS: 50499882; Offset: 1450484521262948161
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486080022, nextTick: 59989, mDrawingTime: 11
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486080057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486082398453010; DSPS: 51155288; Offset: 1450484521262954964
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486102399781511; DSPS: 51810692; Offset: 1450484521262940691
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486122401202888; DSPS: 52466099; Offset: 1450484521262927742
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486140022, nextTick: 60001, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486140052, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486142402601406; DSPS: 53121504; Offset: 1450484521262952969
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486162404524948; DSPS: 53776927; Offset: 1450484521262953904
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486182405888539; DSPS: 54432332; Offset: 1450484521262944204
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486200026, nextTick: 59993, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486200055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486202407334603; DSPS: 55087739; Offset: 1450484521262955941
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486222408688519; DSPS: 55743143; Offset: 1450484521262967084
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486242410029390; DSPS: 56398547; Offset: 1450484521262965182
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486260036, nextTick: 59980, mDrawingTime: 8
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486260045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486262411476879; DSPS: 57053955; Offset: 1450484521262947827
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486282413468257; DSPS: 57709381; Offset: 1450484521262925045
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486302414835053; DSPS: 58364785; Offset: 1450484521262949067
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486320044, nextTick: 59976, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486320051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486322416226326; DSPS: 59020191; Offset: 1450484521262936532
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486342417631120; DSPS: 59675597; Offset: 1450484521262937517
,I/ProcessStatsService(  967): Prepared write state in 21ms
,I/ProcessStatsService(  967): Prepared write state in 20ms
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2015-12-18-12-57-26.bin
I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486362419020911; DSPS: 60331002; Offset: 1450484521262954017
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486380028, nextTick: 59978, mDrawingTime: 11
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486380056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486382420422267; DSPS: 60986408; Offset: 1450484521262951564
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486402421820357; DSPS: 61641814; Offset: 1450484521262945846
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486422423978061; DSPS: 62297245; Offset: 1450484521262936802
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486440036, nextTick: 59986, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1450486440041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450486442425374848; DSPS: 62952650; Offset: 1450484521262960298
,TIME-OUT KILL (timeout was 1800000ms)
```
