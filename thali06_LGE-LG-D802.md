#### Test 5507315224df3aa_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/system
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
--------- beginning of /dev/log/main
D/BubblePopupHelper( 1134): isShowingBubblePopup : false
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2024): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/AndroidRuntime( 5044): 
D/AndroidRuntime( 5044): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5044): CheckJNI is OFF
D/dalvikvm( 5044): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5044): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5044): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5044): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5044): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Icing   ( 1960): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/dalvikvm( 5044): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Icing   ( 1960): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1960): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 5044): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5044): failed to load memtrack module: -2
D/AndroidRuntime( 5044): Calling main entry com.android.commands.am.Am
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 5044
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (152 us)
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  962): startService SlideAside
W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{43a9b4c0 stackId=1, 2 tasks}
D/UsbSettingsControl( 2612): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2612): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 4259): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/AndroidRuntime( 5044): Shutting down VM
D/dalvikvm( 5044): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 2ms
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 4259): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4259): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5062 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 5062): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5062): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5062): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 5062): Binding Chromium to the background looper Looper (main, tid 1) {43080f08}
I/chromium( 5062): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5062): Initializing chromium process, renderers=0
W/chromium( 5062): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5062): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5062): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5062): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5062): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5062): Remote Branch: 
I/Adreno-EGL( 5062): Local Patches: 
I/Adreno-EGL( 5062): Reconstruct Branch: 
I/dalvikvm( 5062): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5062): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5062): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5062): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5062): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5062): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5062): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5062): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5062): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5062): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5062): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5062): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5062): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5062): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5062): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5062): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5062): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5062): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5062): CordovaWebView is running on device made by: LGE
D/dalvikvm( 5062): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 5062): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5062): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5062): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5062): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/BubblePopupHelper( 1134): isShowingBubblePopup : false
D/OpenGLRenderer( 5062): Enabling debug mode 0
W/AwContents( 5062): nativeOnDraw failed; clearing to background color.
W/AwContents( 5062): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  962): IME STATUS OFF
I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +383ms
I/ActivityManager( 5062): Timeline: Activity_idle id: android.os.BinderProxy@430827c8 time:109319
D/JsMessageQueue( 5062): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 5062): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x43086ce0
D/dalvikvm( 5062): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x43086ce0
D/jxcore_app_log( 5062): JniHelper::setJavaVM(0x42035808), pthread_self() = 1639246944
D/JX-Cordova( 5062): jxcore cordova android initializing
I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3} time:109712
D/UsbSettings( 2612): [AUTORUN] onStop()
D/ActivityManager(  962): no-history finish of ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{438acb28 ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 5062): GC_CONCURRENT freed 2736K, 12% free 21906K/24832K, paused 2ms+1ms, total 41ms
,D/dalvikvm( 5062): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1227): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 178K, 12% free 21913K/24832K, paused 22ms, total 22ms
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 132K, 12% free 21927K/24832K, paused 23ms, total 24ms
,I/dalvikvm-heap( 5062): Grow heap (frag case) to 23.679MB for 96598-byte allocation
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 180K, 12% free 21962K/24928K, paused 25ms, total 25ms
,I/dalvikvm-heap( 5062): Grow heap (frag case) to 23.758MB for 144892-byte allocation
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 254K, 13% free 22010K/25072K, paused 23ms, total 23ms
,I/dalvikvm-heap( 5062): Grow heap (frag case) to 23.875MB for 217334-byte allocation
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 370K, 13% free 22084K/25288K, paused 39ms, total 39ms
,I/dalvikvm-heap( 5062): Grow heap (frag case) to 24.051MB for 325996-byte allocation
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 570K, 14% free 22206K/25608K, paused 22ms, total 22ms
,I/dalvikvm-heap( 5062): Grow heap (frag case) to 24.325MB for 488990-byte allocation
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 870K, 15% free 22383K/26088K, paused 41ms, total 41ms
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 1290K, 14% free 22640K/26088K, paused 24ms, total 24ms
,I/dalvikvm-heap( 5062): Grow heap (frag case) to 25.332MB for 1100216-byte allocation
,D/dalvikvm( 5062): GC_CONCURRENT freed 1921K, 16% free 23061K/27164K, paused 1ms+5ms, total 53ms
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 159K, 16% free 22940K/27164K, paused 22ms, total 22ms
,I/dalvikvm-heap( 5062): Grow heap (frag case) to 26.150MB for 1650320-byte allocation
,D/dalvikvm( 5062): GC_CONCURRENT freed 1715K, 19% free 23541K/28776K, paused 1ms+2ms, total 33ms
,D/dalvikvm( 5062): GC_FOR_ALLOC freed 1289K, 18% free 23602K/28776K, paused 25ms, total 25ms
,I/dalvikvm-heap( 5062): Grow heap (frag case) to 27.583MB for 2475476-byte allocation
,D/dalvikvm( 5062): GC_CONCURRENT freed 398K, 17% free 25953K/31196K, paused 6ms+3ms, total 44ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 5062): GC_FOR_ALLOC freed 4253K, 22% free 24588K/31196K, paused 30ms, total 30ms
I/dalvikvm-heap( 5062): Grow heap (frag case) to 29.726MB for 3713210-byte allocation
D/dalvikvm( 5062): GC_CONCURRENT freed 324K, 20% free 28117K/34824K, paused 2ms+4ms, total 44ms
D/BubblePopupHelper( 1134): isShowingBubblePopup : false
D/dalvikvm( 5062): GC_FOR_ALLOC freed 3341K, 27% free 25561K/34824K, paused 25ms, total 25ms
W/jxcore-log( 5062): Initializing JXcore engine
W/jxcore-log( 5062): JXcore engine is ready
D/dalvikvm( 5062): GC_CONCURRENT freed 376K, 19% free 28208K/34824K, paused 2ms+1ms, total 41ms
D/dalvikvm( 5062): WAIT_FOR_CONCURRENT_GC blocked 33ms
W/jxcore-log( 5062): Starting JXcore engine
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2024): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
W/jxcore-log( 5062): Platform android
W/jxcore-log( 5062): 
W/jxcore-log( 5062): Process ARCH arm
W/jxcore-log( 5062): 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 5062): JXcore Cordova bridge is ready!
I/jxcore-log( 5062): 
,W/jxcore-log( 5062): JXcore engine is started
,I/chromium( 5062): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 5062): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 5062): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.457169 Y: -0.421326 Z: 9.808334 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457169 .y:-0.421326 .z:9.808334
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/ConfigService( 1529): onDestroy
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.447983 Y: -0.408569 Z: 9.813934 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447983 .y:-0.408569 .z:9.813934
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1227): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
D/WifiController(  962): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
,I/jxcore-log( 5062): Toggling radios to true
I/jxcore-log( 5062): 
,D/BluetoothManagerService(  962): Message: 20
,D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a81330:true
,D/BluetoothAdapter( 5062): enable(): BT is already enabled..!
,D/WifiStateMachine(  962): handleMessage: E msg.what=131145
D/WifiService(  962): New client listening to asynchronous messages
D/WifiService(  962): setWifiEnabled: true pid=5062, uid=10304
E/WifiService(  962): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  962): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  962): disconnect pid=5062, uid=10304
,D/WifiService(  962): reconnect pid=5062, uid=10304
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DISCONNECT
I/jxcore-log( 5062): Radios toggled
I/jxcore-log( 5062): 
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2024): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2024): wlan0: Cancelling scan request
D/wpa_supplicant( 2024): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2024): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2024): TDLS: Tear down peers
D/wpa_supplicant( 2024): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5062): Received device characteristics:
I/jxcore-log( 5062): Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 5062): Bluetooth name: Thali Test's G2
I/jxcore-log( 5062): Device name: LGE-LG-D802
I/jxcore-log( 5062): 
I/jxcore-log( 5062): Perf Test app loaded loaded
I/jxcore-log( 5062): 
,I/Choreographer( 5062): Skipped 59 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2024): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2024): wlan0: Deauthentication notification
D/wpa_supplicant( 2024): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2024): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2024): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2024): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2024): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2024): wlan0: Disconnect event - remove keys
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7a57d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2024):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2024): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2024): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2024): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): RTM_NEWL,INK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2024): nl80211: Event message available
D/wpa_supplicant( 2024): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2024): nl80211: Ignore disconnect event triggered during reassociation
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
W/Settings(  962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131146
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiNative-wlan0(  962): doBoolean: RECONNECT
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2024): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2024): Fast associate: Old scan results
D/wpa_supplicant( 2024): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2024): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2024): wlan0: nl80211: scan request
,D/wpa_supplicant( 2024): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147460
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/wpa_supplicant( 2024): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2024): nl80211: Event message available
D/wpa_supplicant( 2024): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2024): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  962): Network connection lost
,D/WifiStateMachine(  962): Stopping DHCP and clearing IP
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2024): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2024): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2024): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  962):    returned true
,D/DhcpStateMachine(  962): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5062): check test folder
I/jxcore-log( 5062): 
I/jxcore-log( 5062): found test : ./testFindPeers.js
I/jxcore-log( 5062): 
D/CommandListener(  265): Clearing all IP addresses on wlan0
D/WifiStateMachine(  962): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/QCNEA   (  401): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  401): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  401): |CAC| updateNetCfgInfo
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC|                   Netconfig               
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  401): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  401): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  401): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  401): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  401): |CAC| 	NetConfig: mtu        =0
,V/QCNEA   (  401): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| Received bssid= 
D/QCNEA   (  401): |CAC| net type = 3
V/QCNEA   (  401): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  401): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  401): |CAC| 	ssid           =NG700
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  401): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  401): |CAC| dispatchNetCfg: updating:0xb885f8dc
D/QCNEA   (  401): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
D/WifiHS20(  962): hidePasspointNotification off =false
,D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1134): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
I/jxcore-log( 5062): found test : ./testSendData.js
I/jxcore-log( 5062): 
D/WifiStateMachine(  962): handleMessage: X
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  265): RouteController
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1134): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  265): RouteController
,V/        (  265): RouteController
I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5109 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  265): RouteController
,D/HyLog   ( 5109): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5109): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5109): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,I/PCSuite ( 5109): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  265): RouteController
,W/NetworkManagementService(  962): route cmd failed: 
W/NetworkManagementService(  962): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  962): '
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  962): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  962): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x5bc0d870 clazz=0x6ce00001 iface=wlan0 mask=0x3
,D/QcConnectivityService(  962): resetConnections(wlan0, 3)
D/PCSuite ( 5109): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5109): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/NativeCrypto( 1529): Read error: ssl=0x625e2578: I/O error during system call, Connection timed out
,V/NativeCrypto( 1529): SSL shutdown failed: ssl=0x625e2578: I/O error during system call, Broken pipe
I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5146 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  962): Killing 4273:com.google.android.music:main/u0a107 (adj 15): empty #17
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
D/HyLog   ( 5146): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/HyLog   ( 5146): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5146): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,F/ActivityManager(  962): Service ServiceRecord{43a18210 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43a9e0a8 4273:com.google.android.music:main/u0a107} not same as in map: null
I/chromium( 5062): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,F/ActivityManager(  962): Service ServiceRecord{439f9490 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43a9e0a8 4273:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
,D/QRemote ( 5146): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
D/QRemote ( 5146): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5146): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 5146): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5146): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 5146): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 5146): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 5146): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5146): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 4097:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  962): StoppedState
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
D/HeadsetStateMachine( 1227): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
D/HeadsetStateMachine( 1227): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4231): onReceive
,D/AppUp4:CustFacade( 4231): Context : android.app.ReceiverRestrictedContext@4309a1a0
D/AppUp4:CustFacade( 4231): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4231): isOpenOperator : true
,D/AppUp4:CustFacade( 4231): isPhone : true
,I/LicenseContentProvider( 4498): start selecting data
,D/SIMObserver( 4498): simInfo1
,I/AppUp4:EulaManager( 4231): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4231): begin check event
,I/AppUp4:CustModeStarterReceiver( 4231): Event For GoodConnectivity
,D/EAS     ( 4998): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4998): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4998): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4668): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4668): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4668): networkInfo.isConnected() = false
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5176 uid=10052 gids={50052, 3003}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/linker  ( 4998): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4998): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4998): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4998): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4998): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HyLog   ( 5176): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5176): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5176): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HtmlEditor( 4998): register_HtmlEditor, Success
D/HtmlEditor( 4998): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4998): register_HtmlEditorTimer, Success
D/HtmlEditor( 4998): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4998): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4998): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4998): register_HtmlEditorFont, Success
D/HtmlEditor( 4998): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4998): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4998): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4998): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4998): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4998): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4998): JNI_OnLoad Success
I/HubEmail( 4998): JNI_OnLoad()
I/HubEmail( 4998): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4998): registerNatives()
I/HubEmail( 4998): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4998): registerNativeMethods()
I/HubEmail( 4998): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2024): nl80211: Event message available
D/wpa_supplicant( 2024): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2024): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2024): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2024): nl80211: Received scan results (16 BSSes)
D/wpa_supplicant( 2024): nl80211: Survey data missing
D/wpa_supplicant( 2024): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 9 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 10 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 11 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 12 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 13 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 14 BSSID 00:37:b7:9d:3e:72 SSID 'FunBox2-3E72',
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 15 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 16 BSSID 94:eb:cd:be:6a:81 SSID 'B'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Add new id 17 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): BSS: last_scan_res_used=16/32 last_scan_full=0
D/wpa_supplicant( 2024): wlan0: New scan results available
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2024): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2024): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2024): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2024): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2024): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2024): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2024): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2024): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2024): WPS: AP 00:37:b7:9d:3e:72 type 0 added
D/wpa_supplicant( 2024): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2024): WPS: AP 94:eb:cd:be:6a:81 type 0 added
D/wpa_supplicant( 2024): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[5] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[6] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[7] 00:37:b7:9d:3e:72 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[8] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): WPS: AP[9] 94:eb:cd:be:6a:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2024): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2024): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2024): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2024): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2024): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2024): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2024): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2024): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7a595a8  current_ssid=0x0
D/wpa_supplicant( 2024): scard is not null..
D/wpa_supplicant( 2024): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2024): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2024): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2024): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2024): wlan0: Cancelling scan request
D/wpa_supplicant( 2024): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2024): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2024): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2024): RSN: PMKSA cache search - network_ctx=0xb7a595a8 try_opportunistic=0
D/wpa_supplicant( 2024): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2024): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2024): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2024): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2024): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2024): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2024): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2024): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2024): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2024): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2024): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2024): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2024): nl80211: Unsubscribe mgmt frames handle 0xb7a58590 (mode change)
D/wpa_supplicant( 2024): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2024): nl80211: Register frame type=0xd0 nl_handle=0xb7a58590
D/wpa_supplicant( 2024): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2024): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2024):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024):   * freq=2412
D/wpa_supplicant( 2024):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2024):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024):   * Auth Type 0
D/wpa_supplicant( 2024):   * WPA Versions 0x2
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 a0:c5:62:7a:49:97]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 9e:93:4e:3e:ba:c5]
D/wpa_supplicant( 2024): nl80211: Connect request send successfully
D/wpa_supplicant( 2024): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2024): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 44:e9:dd:10:c0:ac]
V/LGRssiData( 5176): [loadRssi] File not exist 
V/LGRssiData( 5176): [loadRssi] File not exist 
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 44:e9:dd:10:c0:ab]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 14 00:37:b7:9d:3e:72]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 15 10:9a:dd:8e:22:d9]
V/TelephonyAutoProfiling( 5176): [loadFeatureFromXml] *** start feature loading from xml
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 16 94:eb:cd:be:6a:81]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 17 06:7c:34:38:27:cc]
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
W/BaseRuntimeLoader( 5176): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/WifiStateMachine(  962): handleMessage: E msg.what=147461
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2024): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2024): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2024): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2024): WPS: Unknown Vendor Extension (Vendor ID 311)
W/BaseRuntimeLoader( 5176): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/Settings( 4998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/BaseRuntimeLoader( 5176): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5176): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 5176): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5176): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5176): [getValue] FEATURE key : vzw_roaming_state, value : null
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/MobileConnectivityChangeReceiver( 5176): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5176): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5176): onOtaspChanged old =0, new =3
V/PhoneMonitor( 5176): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5200 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  962): Killing 4650:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/HyLog   ( 5200): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5200): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5200): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 2024): nl80211: Event message available
D/wpa_supplicant( 2024): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2024): nl80211: Connect event
D/wpa_supplicant( 2024): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2024): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2024): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2024): wlan0: Association info event
D/wpa_supplicant( 2024): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2024): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2024): wlan0: freq=2412 MHz
D/wpa_supplicant( 2024): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2024): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2024): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2024): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): scard is not null..
D/wpa_supplicant( 2024): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2024): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2024): TDLS: Remove peers on association
D/wpa_supplicant( 2024): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2024): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2024): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2024): EAPOL: enable timer tick
D/wpa_supplicant( 2024): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2024): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2024): wlan0: Cancelling scan request
D/wpa_supplicant( 2024): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5215 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  962): Killing 4923:com.android.defcontainer/u0a4 (adj 15): empty #17
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
D/HyLog   ( 5215): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5215): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5215): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2024): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 23 07 a4 96 3f 68 29 28 7d 24 20 7b 74 a7 f7 ...
D/wpa_supplicant( 2024): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2024): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2024): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2024): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2024): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2024):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2024):   key_nonce - hexdump(len=32): 23 07 a4 96 3f 68 29 28 7d 24 20 7b 74 a7 f7 2f 88 7b c0 ce 16 9f b9 ff 7a 03 80 68 f5 f3 fc 1c
D/wpa_supplicant( 2024):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 23 07 a4 96 3f 68 29 28 7d 24 20 7b 74 a7 f7 ...
D/wpa_supplicant( 2024): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2024): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2024): Get randomness: len=32 entropy=11
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/wpa_supplicant( 2024): WPA: Renewed SNonce - hexdump(len=32): 43 d2 df 6d 7d 1c 80 ff 1e a9 e6 2a 18 32 29 63 45 1c 4c d2 97 34 5c ad 2b 13 e8 3b 41 ed 2f 4f
D/wpa_supplicant( 2024): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): WPA: Nonce1 - hexdump(len=32): 43 d2 df 6d 7d 1c 80 ff 1e a9 e6 2a 18 32 29 63 45 1c 4c d2 97 34 5c ad 2b 13 e8 3b 41 ed 2f 4f
D/wpa_supplicant( 2024): WPA: Nonce2 - hexdump(len=32): 23 07 a4 96 3f 68 29 28 7d 24 20 7b 74 a7 f7 2f 88 7b c0 ce 16 9f b9 ff 7a 03 80 68 f5 f3 fc 1c
D/wpa_supplicant( 2024): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2024): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2024): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2024): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2024): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2024): WPA: Derived Key MIC - hexdump(len=16): 10 24 4b 53 f4 3b 85 21 2c 98 06 58 23 ae fb 6c
D/wpa_supplicant( 2024): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 43 d2 df 6d 7d 1c 80 ff 1e a9 e6 2a 18 32 29 ...
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
D/wpa_supplicant( 2024): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 23 07 a4 96 3f 68 29 28 7d 24 20 7b 74 a7 f7 ...
D/wpa_supplicant( 2024): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2024): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2024): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2024): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2024):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2024):   key_nonce - hexdump(len=32): 23 07 a4 96 3f 68 29 28 7d 24 20 7b 74 a7 f7 2f 88 7b c0 ce 16 9f b9 ff 7a 03 80 68 f5 f3 fc 1c
D/wpa_supplicant( 2024):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_rsc - hexdump(len=8): b3 22 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2024):   key_mic - hexdump(len=16): 16 d1 a8 b8 e8 0b e2 3c dd 63 dc 2a 88 c8 3e 3c
D/wpa_supplicant( 2024): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 23 07 a4 96 3f 68 29 28 7d 24 20 7b 74 a7 f7 ...
D/wpa_supplicant( 2024): RSN: encrypted key data - hexdump(len=56): fc 02 b1 c7 b3 c3 00 f0 13 79 0c 42 dd 42 30 38 23 d9 0b a6 18 f7 22 eb c1 dc 8b 95 aa 4b 88 64 ...
D/wpa_supplicant( 2024): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2024): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2024): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2024): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 28 ef ...
D/wpa_supplicant( 2024): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2024): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2024): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2024): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2024): WPA: Derived Key MIC - hexdump(len=16): 6a 04 83 aa 8b 20 4d 6b 6c 7b 17 f4 7b 0e e3 2b
D/wpa_supplicant( 2024): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2024): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7a58c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2024):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2024): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2024): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2024): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2024): WPA: RSC - hexdump(len=6): b3 22 00 00 00 00
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ec903a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2024):    broadcast key
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/LGDMClient( 2869): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/wpa_supplicant( 2024): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2024): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2024): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 2024): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2024): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2024): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2024): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/wpa_supplicant( 2024): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2024): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2024): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2024): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2024): EAP: EAP entering state DISABLED
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2024): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2024): EAPOL: Supplicant port status: Authorized
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection established
D/WifiNative-wlan0(  962): doString: STATUS
D/wpa_supplicant( 2024): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2024): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2024): EAPOL authentication completed successfully
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2024): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2024): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2024): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2024): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  962):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  962): ssid=NG700
D/WifiNative-wlan0(  962): id=0
D/WifiNative-wlan0(  962): mode=station
D/WifiNative-wlan0(  962): pairwise_cipher=CCMP
D/WifiNative-wlan0(  962): group_cipher=CCMP
D/WifiNative-wlan0(  962): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  962): wpa_state=COMPLETED
D/WifiNative-wlan0(  962): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  962): address=34:fc:ef:de:0a:e2
D/LGDMClient( 2869): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
I/ActivityManager(  962): Killing 4957:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/DhcpStateMachine(  962): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-11ms what=147462 obj=android.net.wifi.StateChangeResult@44452f68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@44454880 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-9ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/KeyguardUpdateMonitor( 1134): received broadcast android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 2024): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5234 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/BubblePopupHelper( 1134): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1134): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5234): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5234): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5234): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LGDMSGCM( 5234): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5234): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5250 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  962): Killing 4986:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 5250): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5250): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5250): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/NFS     ( 5250): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2024): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2024): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2024): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4397e790 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  265): Setting iface cfg
,D/WifiStateMachine(  962): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/CommandListener(  265): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
,D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 5250): intf.getDisplayName() = lo
,D/WifiStateMachine(  962): handleMessage: X
I/Wireless_Storage( 5250): intf.getDisplayName() = sit0
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
I/Wireless_Storage( 5250): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5250): intf.getDisplayName() = teql0
D/WifiStateMachine(  962): processMsg: ObtainingIpState
I/Wireless_Storage( 5250): intf.getDisplayName() = wlan0
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet8
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet2
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet3
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet4
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet5
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet6
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet7
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet0
I/Wireless_Storage( 5250): intf.getDisplayName() = rev_rmnet1
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet0
D/WifiStateMachine(  962): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet1
D/WifiStateMachine(  962): processMsg: L2ConnectedState
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet2
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet3
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet4
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet5
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet6
I/Wireless_Storage( 5250): intf.getDisplayName() = rmnet7
,I/Wireless_Storage( 5250): CONNECT : WIFI_DISCONNECT
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4397e790 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2024): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2024): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2024): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): DHCP successful
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
,D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState enter
,D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardUpdateMonitor( 1134): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5264 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  962): Killing 4510:com.android.contacts/u0a21 (adj 15): empty #17
,W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
I/RemoteControlStatusBar( 1134): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  962): handleMessage: X
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/KeyguardUpdateMonitor( 1134): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1134): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1134): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/dalvikvm(  269): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+2ms, total 28ms
D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/KeyguardUpdateMonitor( 1134): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1134): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1134): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/HyLog   ( 5264): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5264): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5264): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  401): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
,V/        (  265): RouteController
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
,V/        (  265): RouteController
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,W/GAV2    ( 5264): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  401): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  401): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  401): |CAC| updateNetCfgInfo
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC|                   Netconfig               
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  401): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  401): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  401): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  401): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  401): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  401): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  401): |CAC| net type = 1
V/QCNEA   (  401): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  401): |CAC| Received ssid= NG700
V/QCNEA   (  401): |CAC| 	ssid           =NG700
V/QCNEA   (  401): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  401): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  401): |CAC| *********************************************
D/QCNEA   (  401): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  401): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  401): |CAC| dispatchNetCfg: updating:0xb885f8dc
D/QCNEA   (  401): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinService( 1960): Checking schedule, now: 1452008742768 next: 1452008687974
,I/CheckinService( 1960): active receiver: enabled
,I/CheckinService( 1960): Preparing to send checkin request
,I/EventLogService( 1960): Accumulating logs since 1452008654977
,V/WebViewChromium( 5264): Binding Chromium to the main looper Looper (main, tid 1) {430895b8}
,I/chromium( 5264): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5264): Initializing chromium process, renderers=0
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinRequestBuilder( 1960): Checkin reason type: 8 attempt count: 1
,W/chromium( 5264): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5264): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5264): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5264): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5264): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5264): Remote Branch: 
I/Adreno-EGL( 5264): Local Patches: 
I/Adreno-EGL( 5264): Reconstruct Branch: 
E/ActivityThread( 1960): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  962): GC_EXPLICIT freed 23759K, 49% free 29782K/58084K, paused 3ms+8ms, total 151ms
,I/NSApplication( 5264): Starting up...
,I/ActivityManager(  962): Killing 4524:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 5146): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5146): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5146): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5146): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5146): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5146): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5109): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5109): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5146): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5146): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5146): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5146): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/dalvikvm( 1529): GC_EXPLICIT freed 774K, 28% free 17893K/24832K, paused 3ms+6ms, total 40ms
,I/GLSUser ( 1529): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1529): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1529): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1529): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1529): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1529): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1960): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x43971238: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5323 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5323): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5323): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5323): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5323): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5323): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5323): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5323): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5323): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5323): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5323): install
,I/MultiDex( 5323): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5323): loading existing secondary dex files
,I/MultiDex( 5323): load found 3 secondary dex files
,I/MultiDex( 5323): install done
,D/dalvikvm( 5323): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5323): VFY: unable to resolve instance field 61
,D/dalvikvm( 5323): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5323): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5323): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5323): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5323): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5323): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5323): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5323): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5323): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5323): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x43084de8
D/dalvikvm( 5323): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x43084de8
,D/dalvikvm( 5323): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x43084de8, skipping init
,D/dalvikvm( 5323): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x43084de8
D/dalvikvm( 5323): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x43084de8
,V/JNIHelp ( 5323): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 5323): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x43084de8
,D/dalvikvm( 5323): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x43084de8
D/dalvikvm( 5323): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x43084de8
,D/dalvikvm( 5323): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x43084de8
,I/ProviderInstaller( 5323): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1529): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1529): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1529): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1960): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WearableService( 1876): callingUid 10006, callindPid: 1876
,E/MDM     ( 1422): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1960): Restart initialization of location
,I/dalvikvm( 5323): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 5323): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5323): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5323): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5323): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5323): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f58000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f58000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
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
,D/WVCdm   (  271): PrepareKeyRequest: nonce=2195003422
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2024): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2024): EAPOL: disable timer tick
,D/dalvikvm( 5323): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4321fcd0
D/dalvikvm( 5323): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4321fcd0
,D/dalvikvm( 5323): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4321fcd0, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings( 5323): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 5323): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/dalvikvm( 5062): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5062): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5062): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 5062): Shutting down VM
,W/dalvikvm( 5062): threadid=1: thread exiting with uncaught exception (group=0x42046e48)
E/AndroidRuntime( 5062): FATAL EXCEPTION: main
E/AndroidRuntime( 5062): Process: com.test.thalitest, PID: 5062
E/AndroidRuntime( 5062): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5062): 	,at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 5062): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 5062): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 5062): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 5062): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 5062): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 5062): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5062): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5062): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5062): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5062): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5062): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5062): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 5062): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5062): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5062): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 5062): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 5062): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  962):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm( 5348): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 5323): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5323): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 91ms
,I/Adreno-EGL( 5323): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5323): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5323): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5323): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5323): Remote Branch: 
I/Adreno-EGL( 5323): Local Patches: 
I/Adreno-EGL( 5323): Reconstruct Branch: 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
D/WVCdm   (  271): PrepareKeyRequest: nonce=3147014517
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  962): RunningState
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,I/Adreno-EGL( 5323): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5323): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5323): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5323): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5323): Remote Branch: 
I/Adreno-EGL( 5323): Local Patches: 
I/Adreno-EGL( 5323): Reconstruct Branch: 
,I/Adreno-EGL( 5323): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5323): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5323): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5323): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5323): Remote Branch: 
I/Adreno-EGL( 5323): Local Patches: 
I/Adreno-EGL( 5323): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1960): Classify the device as Phone.
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  962): Activity pause timeout for ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43a9b4c0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  962): moveHomeStack:
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
,V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  962): resumeTopActivityLocked: Resumed ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1447): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1835): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:45:44
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1835): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1835): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1835): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1835): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:45:44
,D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1835): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1835): 2 : Map key string is -2
,D/lim     ( 1835): 2 : time = 16:45
I/WeatherReflect( 1835): Model Name : LG-D802
D/WeatherTheme( 1835): 2 : Different view - status_min_formatted : 44 != 45
,D/WeatherTheme( 1835): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1835): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1835): 2 : Fixed theme : optimus
,D/WeatherTheme( 1835): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/CheckinTask( 1960): Sending checkin request (11458 bytes)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1487): GC_CONCURRENT freed 5560K, 9% free 60849K/66648K, paused 1ms+2ms, total 26ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1134): GC_FOR_ALLOC freed 2975K, 10% free 71588K/78964K, paused 25ms, total 25ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 4876K, 9% free 61983K/67744K, paused 19ms, total 19ms
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@43084038 time:119186
,V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2612): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2612): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2612): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2612): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{438ac9c0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1} time:119240
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/CheckinRequestBuilder( 1960): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1960): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1529): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1529): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1529): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1529): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1529): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1529): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1960): awaiting user notification for token
,I/CheckinRequestBuilder( 1960): Classify the device as Phone.
,I/CheckinTask( 1960): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1960): Checking schedule, now: 1452008745411 next: 1452586141407
,I/CheckinService( 1960): active receiver: disabled
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  962): GC_CONCURRENT freed 2116K, 47% free 30989K/58084K, paused 2ms+9ms, total 92ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 91ms
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x43160070: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/GCM     ( 1529): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4231): onReceive
,D/GCM     ( 1529): Connected
,D/AppUp4:CustFacade( 4231): Context : android.app.ReceiverRestrictedContext@4309a1a0
D/AppUp4:CustFacade( 4231): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4231): isOpenOperator : true
,D/AppUp4:CustFacade( 4231): isPhone : true
,I/LicenseContentProvider( 4498): start selecting data
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/SIMObserver( 4498): simInfo1
,I/AppUp4:EulaManager( 4231): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4231): begin check event
,I/AppUp4:CustModeStarterReceiver( 4231): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4231): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4231): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4231): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4231): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4231): handleAsyncCustNotification do not startCustService
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1529): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 4576): DownloadService onCreate
,I/DownloadManager( 4576): in removeSpuriousFiles
,V/DownloadManager( 4576): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4998): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EAS     ( 4998): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/eas_req ( 4998): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430d88b0 on behalf of 4576
D/Tethering(  962): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/DownloadManager( 4576): in trimDatabase
V/DownloadManager( 4576): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4576): DownloadService onStartCommand
V/DownloadManager( 4576): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430dbfe8 on behalf of 4576
V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430da758 on behalf of 4576
I/LgeMiscReceiver( 4668): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4668): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4668): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 5176): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5176): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2869): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4576): DownloadService onDestroy
D/LGDMSGCM( 5234): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/LGDMClient( 2869): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 5234): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5250): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5250): CONNECT : WIFI_CONNECT
I/LGDMClient( 2869): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/LGDMClient( 2869): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2869): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2869): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2869): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GoogleURLConnFactory( 1529): Using platform SSLCertificateSocketFactory
I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4231): onReceive
D/AppUp4:CustFacade( 4231): Context : android.app.ReceiverRestrictedContext@4309a1a0
D/AppUp4:CustFacade( 4231): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4231): isOpenOperator : true
,D/AppUp4:CustFacade( 4231): isPhone : true
I/LicenseContentProvider( 4498): start selecting data
,D/SIMObserver( 4498): simInfo1
,I/AppUp4:EulaManager( 4231): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4231): begin check event
I/AppUp4:CustModeStarterReceiver( 4231): Event For GoodConnectivity, noConnectivity : false, but skip! 
,W/BaseRuntimeLoader( 1529): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1529): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1529): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1529): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1529): No account for auth token provided
,V/DownloadManager( 4576): DownloadService onCreate
,D/EAS     ( 4998): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4998): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4576): in removeSpuriousFiles
,V/DownloadManager( 4576): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430e0b28 on behalf of 4576
,V/DownloadManager( 4576): DownloadService onStartCommand
V/DownloadManager( 4576): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4576): in trimDatabase
V/DownloadManager( 4576): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430e3d40 on behalf of 4576
,V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430e3260 on behalf of 4576
I/LgeMiscReceiver( 4668): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4668): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4668): networkInfo.isConnected() = true
D/PhoneState( 4668): setPdpRejectCasuse : false
,W/Settings( 4998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 5176): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5176): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4576): DownloadService onDestroy
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/LGDMClient( 2869): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2869): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/LGDMSGCM( 5234): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2869): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5250): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5250): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2869): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2869): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2869): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2869): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ContextImpl( 5234): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,W/Uploader( 1529): No account for auth token provided
,W/Uploader( 1529):  no longer exists, so no auth token.
,W/Uploader( 1529): No account for auth token provided
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-10ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4231): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4231): onReceive
,D/AppUp4:CustFacade( 4231): Context : android.app.ReceiverRestrictedContext@4309a1a0
,D/AppUp4:CustFacade( 4231): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4231): isOpenOperator : true
,D/AppUp4:CustFacade( 4231): isPhone : true
,I/LicenseContentProvider( 4498): start selecting data
,D/SIMObserver( 4498): simInfo1
,I/AppUp4:EulaManager( 4231): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4231): begin check event
,I/AppUp4:CustModeStarterReceiver( 4231): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4998): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4576): DownloadService onCreate
,D/EAS     ( 4998): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4668): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4668): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4668): networkInfo.isConnected() = true
,D/PhoneState( 4668): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5176): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5176): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2869): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5234): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5234): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5250): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5250): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,W/Settings( 4998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4576): in removeSpuriousFiles
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4576): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430e8380 on behalf of 4576
,I/DownloadManager( 4576): in trimDatabase
,D/LGDMClient( 2869): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 4576): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4576): DownloadService onStartCommand
V/DownloadManager( 4576): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430ea208 on behalf of 4576
,I/LGDMClient( 2869): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4576): created cursor android.database.sqlite.SQLiteCursor@430ebf40 on behalf of 4576
E/LGDMClient( 2869): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2869): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2869): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2869): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4576): DownloadService onDestroy
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1227): Disconnected process message: 10
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1227): Disconnected process message: 10
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,I/GAV2    ( 5264): Thread[GAThread,5,main]: No campaign data found.
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  962): Killing 4864:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/Finsky  ( 4542): [438] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4542): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  962): Killing 5109:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.444443 Y: -0.424606 Z: 9.795334 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444443 .y:-0.424606 .z:9.795334
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.438248 Y: -0.431473 Z: 9.792664 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438248 .y:-0.431473 .z:9.792664
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 4259): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4259): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  962): Handling package changes for user 0
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5507 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
,D/HyLog   ( 5507): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5507): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5507): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1134): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1134): changeTargets() succeeded. size: 20
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1227): Disconnected process message: 10
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1227): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,I/MediaCodecList( 5507): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/Babel   ( 5507): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5507): MmsConfig.loadMmsSettings
I/MediaCodecList( 5507): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5507): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5507): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5507): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5507): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5507): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5507): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5507): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5507): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5507): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5507): MmsConfig.loadFromResources
E/Babel   ( 5507): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5507): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5507): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4231): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4231): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4231): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/LGRssiData( 5507): [loadRssi] File not exist 
V/LGRssiData( 5507): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5507): [loadFeatureFromXml] *** start feature loading from xml
,I/AppUp4:CustModeStarterReceiver( 4231): onReceive
D/AppUp4:CustFacade( 4231): Context : android.app.ReceiverRestrictedContext@4309a1a0
D/AppUp4:CustFacade( 4231): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4231): isOpenOperator : true
,D/AppUp4:CustFacade( 4231): isPhone : true
,I/LicenseContentProvider( 4498): start selecting data
,D/SIMObserver( 4498): simInfo1
,V/TelephonyAutoProfiling( 5507): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5507): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5507): [getValue] FEATURE key : vzw_roaming_state, value : null
I/AppUp4:EulaManager( 4231): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4231): begin check event
D/AppUp4:Utils( 4231): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4231): Event For Nothing, skip.
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5553 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/GmsNetworkLocationProvi( 1422): DISABLE
,D/HyLog   ( 5553): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5553): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5553): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5553): BUILD Country: EU
,I/SystemConfig( 5553): BUILD Operator: OPEN
,D/LocationProviderProxy(  962): applying state to connected service
I/ActivityManager(  962): Killing 5146:com.lge.qremote/u0a96 (adj 15): empty #17
,I/SystemConfig( 5553): systemFeature RCS result false
D/SystemConfig( 5553): refreshRcsSupport() :false
,D/LocationProviderProxy(  962): applying state to connected service
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5573 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Killing 5062:com.test.thalitest/u0a304 (adj 15): empty #17
,D/HyLog   ( 5573): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5573): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5573): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/WindowState(  962): WIN DEATH: Window{4508b6c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  962): Client connection lost with reason: 4
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/InputMethodManagerService(  962): IME STATUS OFF
,W/Binder  ( 1305): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1305): java.lang.NullPointerException
W/Binder  ( 1305): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1305): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1305): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1305): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  962): Got RemoteException sending setActive(false) notification to pid 5062 uid 10304
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{44209f98 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Killing 4576:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2679): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1960): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1960): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  962): Delaying start of: ServiceRecord{44fb0c98 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1960): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1529): GC_CONCURRENT freed 1746K, 28% free 18078K/24832K, paused 3ms+3ms, total 29ms
,D/dalvikvm( 1960): GC_CONCURRENT freed 1892K, 21% free 19655K/24832K, paused 2ms+3ms, total 36ms
,I/IcingCorporaProvider( 2679): UpdateCorporaTask done [took 215 ms] updated apps [took 215 ms] 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  962): battery changed pluggedType: 2
D/HeadsetStateMachine( 1227): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  962): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/GAV4    ( 5507): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008760041, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008760045, nextTick: 59986, mDrawingTime: 1
,D/WeatherService( 1835): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:46:0
,D/WeatherService( 1835): 2 : TimeTick Intent And Screen On
D/WeatherService( 1835): 2 : SDK version : 19
D/WeatherQuickCover( 1835): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1835): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
,D/WeatherService( 1835): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1835): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1835): 2 : Map key string is -2
,D/lim     ( 1835): 2 : time = 16:46
I/WeatherReflect( 1835): Model Name : LG-D802
,D/WeatherTheme( 1835): 2 : Different view - status_min_formatted : 45 != 46
D/WeatherTheme( 1835): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1835): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1835): 2 : Fixed theme : optimus
,D/WeatherTheme( 1835): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1835): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:46:0
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,I/PowerManagerService(  962): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  962): [updateScreenState] screen on = false
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  962): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8520 usec
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  962): hal_acquire_resources
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
I/qcom_sensors_hal(  962): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
D/qcom_sensors_hal(  962): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
I/qcom_sensors_hal(  962): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.453262 Y: -0.405411 Z: 9.814957 
V/qcom_sensors_hal(  962): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  962): hal_sam_algo_activate: Update freq 0 -> 20
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453262 .y:-0.405411 .z:9.814957
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/qcom_sensors_hal(  962): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  962): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  962): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.447357 Y: -0.407501 Z: 9.815109 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447357 .y:-0.407501 .z:9.815109
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2024): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Sensors (  359): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  962): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  962): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  962): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  962): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  962): proximitySensorChanged  positive = true
I/KnockOnPowerController(  962): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.446884 Y: -0.407608 Z: 9.801270 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446884 .y:-0.407608 .z:9.801270
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.447540 Y: -0.411942 Z: 9.803772 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447540 .y:-0.411942 .z:9.803772
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.452393 Y: -0.413757 Z: 9.798264 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452393 .y:-0.413757 .z:9.798264
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.448654 Y: -0.415680 Z: 9.792404 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448654 .y:-0.415680 .z:9.792404
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
V/KeyguardServiceDelegate(  962): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43c3e810)
D/KeyguardViewMediator( 1134): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1134): notifyScreenOnLocked
D/LockPatternUtilsEx( 1134): OMADM Lock is OFF
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.447784 Y: -0.415466 Z: 9.810165 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447784 .y:-0.415466 .z:9.810165
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/HeadsetStateMachine( 1227): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb8e98450
,D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
D/KeyguardViewMediator( 1134): handleNotifyScreenOn
,D/KeyguardViewManager( 1134): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  962): **** SHOWN CALLED ****
I/WindowManager(  962): No lock screen! windowToken=null
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/WifiStateMachine(  962): handleScreenStateChanged: true
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2024): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  962): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  962): stopMonitoring
,D/wpa_supplicant( 2024): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131127
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=132097
D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  962): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2024): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2024): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  962): handleMessage: X
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43baf890 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/WeatherAncestor( 1835): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:46:4
,E/SlideAside( 4259): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,I/SlideAside( 4259): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
D/UpdateThreadPoolManager( 1835): 2 : This is isUpdating : false
,D/WeatherAncestor( 1835): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:46:4
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
D/WeatherService( 1835): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1835): 2 : TimeTick Receiver Unregister
D/LockPatternUtilsEx( 1134): OMADM Lock is OFF
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
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
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  962): Excessive delay in blankDisplay() while turning screen off: 382ms
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/dalvikvm( 1134): GC_FOR_ALLOC freed 6438K, 15% free 68702K/79928K, paused 39ms, total 39ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/GlobalAccess( 1134): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1134): changeTargets() succeeded. size: 20
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008764490, nextTick: 55541, mDrawingTime: 1
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008764525, nextTick: 55508, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
D/WeatherService( 1835): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:46:4
,D/WeatherService( 1835): 2 : ACTION screen on
,D/WeatherService( 1835): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1835): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:46:4
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, enabled=0
,D/KeyguardViewMediator( 1134): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1134): notifyScreenOffLocked
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
,V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  962): hal_acquire_resources
D/qcom_sensors_hal(  962): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  962): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  962): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,I/LGImmersionVibrator(  962): Vibrator off
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/KeyguardViewMediator( 1134): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  962): handleScreenStateChanged: false
D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{435e9060 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
,V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
D/wpa_supplicant( 2024): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2024): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/VolumeVibrator( 1157): clear
,D/KeyguardViewMediator( 1134): handleNotifyScreenOff
,D/KeyguardViewManager( 1134): onScreenTurnedOff()
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
,D/wpa_supplicant( 2024): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
D/WeatherService( 1835): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:46:4
,D/WeatherService( 1835): 2 : ACTION screen off
,D/WeatherService( 1835): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:46:4
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,D/NfcService( 1472): NFC-C OFF
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1134): OMADM Lock is OFF
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  359): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardViewMediator( 1134): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1134): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1134): OMADM Lock is OFF
,D/KeyguardViewMediator( 1134): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1134): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008772542494741; DSPS: 4945519; Offset: 1452008621617232290
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008792543809680; DSPS: 5600922; Offset: 1452008621617234973
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008812545757979; DSPS: 6256346; Offset: 1452008621617230147
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1227): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008820035, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008820043, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008832546636824; DSPS: 6911735; Offset: 1452008621617223983
,D/wpa_supplicant( 2024): wlan0: BSS: Remove id 4 BSSID ea:6f:1d:5b:14:2a SSID 'iPhone (Natalia)' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 7 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 ea:6f:1d:5b:14:2a]
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008852547521001; DSPS: 7567123; Offset: 1452008621617253668
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008872548402870; DSPS: 8222512; Offset: 1452008621617250527
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008880034, nextTick: 59982, mDrawingTime: 7
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008880045, nextTick: 59968, mDrawingTime: 7
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008892549723215; DSPS: 8877916; Offset: 1452008621617228098
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008912550566323; DSPS: 9533303; Offset: 1452008621617247232
,D/wpa_supplicant( 2024): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 9 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 10 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 11 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 12 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 13 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 14 BSSID 00:37:b7:9d:3e:72 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 15 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 6 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 16 BSSID 94:eb:cd:be:6a:81 SSID 'B' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS: Remove id 17 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2024): wlan0: BSS:, Remove id 8 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2024): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a],
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81],
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 a0:c5:62:7a:49:97]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 44:e9:dd:10:c0:ac]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:37:b7:9d:3e:72]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 10:9a:dd:8e:22:d9]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 64:7c:34:38:27:cc]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 16 94:eb:cd:be:6a:81]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 17 06:7c:34:38:27:cc]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008932551446127; DSPS: 10188692; Offset: 1452008621617242026
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008940028, nextTick: 60000, mDrawingTime: 4
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452008940039, nextTick: 59952, mDrawingTime: 16
,D/dalvikvm( 2667): GC_CONCURRENT freed 7764K, 32% free 16888K/24832K, paused 3ms+2ms, total 47ms
,D/dalvikvm( 2667): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm(  962): GC_EXPLICIT freed 3015K, 47% free 30794K/57484K, paused 4ms+9ms, total 121ms
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008952552910176; DSPS: 10844100; Offset: 1452008621617241231
,I/GLSUser ( 1529): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1529): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1529): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1529): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1529): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1529): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x4364c288: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1529): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1529): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1529): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1529): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1529): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1529): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1529): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1529): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4542): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4542): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4542): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4542): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4542): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4542): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4542): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4542): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4542): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4542): isDataSchedulerEnabled():false
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/LocationManagerService(  962): remove 43c21f88
D/LocationManagerService(  962): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
,D/dalvikvm( 2667): GC_CONCURRENT freed 1885K, 32% free 17051K/24832K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 2667): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2667): GC_CONCURRENT freed 1843K, 31% free 17255K/24832K, paused 3ms+1ms, total 27ms
,D/dalvikvm( 2667): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Mlt MonitorService( 2667): parseLastkmsg to dump
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008972554363740; DSPS: 11499508; Offset: 1452008621617229951
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452008992556741235; DSPS: 12154945; Offset: 1452008621617257593
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009000020, nextTick: 59995, mDrawingTime: 11
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009000047, nextTick: 59983, mDrawingTime: 2
,D/dalvikvm( 2667): GC_CONCURRENT freed 1936K, 31% free 17239K/24832K, paused 10ms+2ms, total 57ms
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009012557705944; DSPS: 12810337; Offset: 1452008621617245739
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009032559018979; DSPS: 13465740; Offset: 1452008621617246519
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009052559437711; DSPS: 14121114; Offset: 1452008621617238004
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009060023, nextTick: 60000, mDrawingTime: 7
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009060056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009072559887269; DSPS: 14776489; Offset: 1452008621617229799
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009092561204989; DSPS: 15431892; Offset: 1452008621617235263
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009112562063823; DSPS: 16087280; Offset: 1452008621617239605
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009120034, nextTick: 59993, mDrawingTime: 4
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009120037, nextTick: 59994, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009132562949178; DSPS: 16742669; Offset: 1452008621617239950
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009152563379307; DSPS: 17398043; Offset: 1452008621617242833
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1134): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 268 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1134): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1227): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009172564279777; DSPS: 18053433; Offset: 1452008621617227776
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009180038, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009180043, nextTick: 59970, mDrawingTime: 7
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009192566308452; DSPS: 18708859; Offset: 1452008621617242290
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009212567162000; DSPS: 19364247; Offset: 1452008621617241346
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009232568080721; DSPS: 20019637; Offset: 1452008621617244540
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009240047, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009240056, nextTick: 59974, mDrawingTime: 2
,I/ActivityManager(  962): Killing 4998:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43409f88 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009252569014512; DSPS: 20675028; Offset: 1452008621617232286
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009272569893575; DSPS: 21330416; Offset: 1452008621617256857
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009292570330395; DSPS: 21985791; Offset: 1452008621617235913
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009300029, nextTick: 60001, mDrawingTime: 2
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009300032, nextTick: 60000, mDrawingTime: 1
,W/ProcessCpuTracker(  962): Skipping unknown process pid 6174
,W/ProcessCpuTracker(  962): Skipping unknown process pid 6175
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009312571806941; DSPS: 22641200; Offset: 1452008621617217098
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009332573107772; DSPS: 23296602; Offset: 1452008621617236190
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009352573980257; DSPS: 23951991; Offset: 1452008621617223666
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009360047, nextTick: 59984, mDrawingTime: 1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009360056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009372575702410; DSPS: 24607407; Offset: 1452008621617236834
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009392577013285; DSPS: 25262810; Offset: 1452008621617235453
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009412577877848; DSPS: 25918198; Offset: 1452008621617245524
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009420051, nextTick: 59979, mDrawingTime: 1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009420056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009432578317469; DSPS: 26573573; Offset: 1452008621617227382
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009452578773513; DSPS: 27228948; Offset: 1452008621617225662
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009472579672196; DSPS: 27884337; Offset: 1452008621617239335
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009480033, nextTick: 59997, mDrawingTime: 1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009480047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009492580104997; DSPS: 28539711; Offset: 1452008621617244890
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009512580571985; DSPS: 29195087; Offset: 1452008621617223597
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009532581453311; DSPS: 29850475; Offset: 1452008621617250431
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009540045, nextTick: 59985, mDrawingTime: 1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009540047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009552581895583; DSPS: 30505850; Offset: 1452008621617234939
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009572582335247; DSPS: 31161224; Offset: 1452008621617247357
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009592583202337; DSPS: 31816613; Offset: 1452008621617229437
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009600033, nextTick: 59997, mDrawingTime: 1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009600036, nextTick: 59996, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009612583632674; DSPS: 32471987; Offset: 1452008621617232528
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009632585504370; DSPS: 33127408; Offset: 1452008621617242652
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009652585929573; DSPS: 33782782; Offset: 1452008621617240609
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009660033, nextTick: 59965, mDrawingTime: 12
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009660057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009672586384800; DSPS: 34438157; Offset: 1452008621617238072
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009692586828109; DSPS: 35093531; Offset: 1452008621617254135
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009712587709284; DSPS: 35748921; Offset: 1452008621617219783
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009720038, nextTick: 59980, mDrawingTime: 9
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009720044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009732588157183; DSPS: 36404295; Offset: 1452008621617240435
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009752589029374; DSPS: 37059684; Offset: 1452008621617227617
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009772589888320; DSPS: 37715072; Offset: 1452008621617232070
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009780035, nextTick: 59988, mDrawingTime: 6
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009780050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009792590346641; DSPS: 38370447; Offset: 1452008621617232628
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009812590791420; DSPS: 39025821; Offset: 1452008621617250161
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009832591229761; DSPS: 39681196; Offset: 1452008621617230738
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009840041, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009840050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009852595322524; DSPS: 40336690; Offset: 1452008621617234146
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009872596685788; DSPS: 40992094; Offset: 1452008621617254636
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009892597103738; DSPS: 41647468; Offset: 1452008621617245340
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009900035, nextTick: 59975, mDrawingTime: 9
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009900049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009912597570289; DSPS: 42302844; Offset: 1452008621617223610
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009932605554448; DSPS: 42958465; Offset: 1452008621617242681
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009952605984791; DSPS: 43613839; Offset: 1452008621617245778
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009960039, nextTick: 59975, mDrawingTime: 9
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452009960050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009972606450473; DSPS: 44269214; Offset: 1452008621617253696
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452009992606894878; DSPS: 44924589; Offset: 1452008621617240337
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010012607805801; DSPS: 45579979; Offset: 1452008621617235733
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010020035, nextTick: 59976, mDrawingTime: 10
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010020048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010032608244851; DSPS: 46235353; Offset: 1452008621617247537
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010052608686274; DSPS: 46890728; Offset: 1452008621617231196
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010072609619205; DSPS: 47546118; Offset: 1452008621617248600
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010080046, nextTick: 59972, mDrawingTime: 8
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010080054, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010092610537554; DSPS: 48201509; Offset: 1452008621617220904
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010112610978402; DSPS: 48856883; Offset: 1452008621617234506
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010132611420685; DSPS: 49512257; Offset: 1452008621617249543
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010140028, nextTick: 60000, mDrawingTime: 4
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010140053, nextTick: 59975, mDrawingTime: 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010152616178969; DSPS: 50167773; Offset: 1452008621617247085
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010172617026117; DSPS: 50823161; Offset: 1452008621617239741
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,D/GCM     ( 1529): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/BubblePopupHelper( 1134): isShowingBubblePopup : false
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010192617498661; DSPS: 51478537; Offset: 1452008621617224003
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010200037, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010200042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010212621105507; DSPS: 52134015; Offset: 1452008621617229775
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010232622414922; DSPS: 52789418; Offset: 1452008621617226934
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010252623699997; DSPS: 53444820; Offset: 1452008621617230271
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010260043, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010260045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010272624143333; DSPS: 54100194; Offset: 1452008621617246361
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010292625048194; DSPS: 54755584; Offset: 1452008621617235694
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010312625915950; DSPS: 55410973; Offset: 1452008621617218441
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010320040, nextTick: 59988, mDrawingTime: 2
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010320043, nextTick: 59988, mDrawingTime: 1
,I/GLSUser ( 1529): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1529): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1529): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1529): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1529): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1529): [DefaultAuthDelegateService] Use browser flow? false
,E/Ads     ( 1960): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010332626358192; DSPS: 56066347; Offset: 1452008621617233437
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010352626821398; DSPS: 56721722; Offset: 1452008621617238879
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010372630212999; DSPS: 57377193; Offset: 1452008621617243029
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010380038, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010380044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010392630651366; DSPS: 58032568; Offset: 1452008621617223632
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010412631080082; DSPS: 58687941; Offset: 1452008621617255620
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010432641573621; DSPS: 59343645; Offset: 1452008621617251112
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,I/ProcessStatsService(  962): Prepared write state in 45ms
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010440082, nextTick: 59948, mDrawingTime: 2
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010440084, nextTick: 59947, mDrawingTime: 1
,I/ProcessStatsService(  962): Prepared write state in 35ms
,I/ProcessStatsService(  962): Pruning old procstats: /data/system/procstats/state-2016-01-04-23-41-00.bin
,D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1529): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1529): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1529): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1529): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1529): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1529): [DefaultAuthDelegateService] Use browser flow? false
,I/EventLogService( 1960): Aggregate from 1452008742803 (log), 1452008650157 (data)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010452642955042; DSPS: 59999051; Offset: 1452008621617228724
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010472643828628; DSPS: 60654439; Offset: 1452008621617247818
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010492644285287; DSPS: 61309814; Offset: 1452008621617246713
,D/KeyguardUpdateMonitor( 1134): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1134): handleTimeUpdate
,D/KeyguardModel( 1134): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010500031, nextTick: 59995, mDrawingTime: 3
,D/Clock   ( 1134): Clock updated, drawingStartTime : 1452010500035, nextTick: 59996, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010512645418162; DSPS: 61965212; Offset: 1452008621617219920
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452010532646298274; DSPS: 62620600; Offset: 1452008621617245540
,TIME-OUT KILL (timeout was 1800000ms)
```
