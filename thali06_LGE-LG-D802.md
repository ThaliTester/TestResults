#### Test 539786639813e59_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 1970): GC_CONCURRENT freed 1575K, 22% free 19461K/24832K, paused 2ms+4ms, total 40ms
D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1970): fetch service done; releasing wakelock
I/ConfigFetchService( 1970): stopping self
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Icing   ( 1970): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1970): Loaded CLD2 Version V2.0 - 20141016
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1970): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2027): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/AndroidRuntime( 4681): 
D/AndroidRuntime( 4681): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4681): CheckJNI is OFF
D/dalvikvm( 4681): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4681): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4681): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4681): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4681): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4681): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4681): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4681): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4681): Calling main entry com.android.commands.am.Am
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4681
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (110 us)
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  965): startService SlideAside
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{43157eb0 stackId=1, 2 tasks}
D/UsbSettingsControl( 2588): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2588): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4681): Shutting down VM
D/dalvikvm( 4681): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3742): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  965): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4697 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3742): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3742): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4697): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4697): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4697): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4697): Binding Chromium to the background looper Looper (main, tid 1) {428af8b8}
I/chromium( 4697): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4697): Initializing chromium process, renderers=0
W/chromium( 4697): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4697): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4697): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4697): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4697): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4697): Remote Branch: 
I/Adreno-EGL( 4697): Local Patches: 
I/Adreno-EGL( 4697): Reconstruct Branch: 
I/dalvikvm( 4697): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4697): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4697): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4697): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4697): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4697): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4697): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4697): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4697): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4697): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4697): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4697): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4697): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4697): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4697): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4697): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4697): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4697): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4697): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4697): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4697): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4697): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4697): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4697): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/OpenGLRenderer( 4697): Enabling debug mode 0
,W/AwContents( 4697): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  965): Displayed com.test.thalitest/.MainActivity: +335ms
W/AwContents( 4697): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  965): IME STATUS OFF
I/ActivityManager( 4697): Timeline: Activity_idle id: android.os.BinderProxy@428b0f98 time:112817
D/JsMessageQueue( 4697): Set native->JS mode to OnlineEventsBridgeMode
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.458771 Y: -0.402481 Z: 9.750046 
D/WifiController(  965): battery changed pluggedType: 2
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458771 .y:-0.402481 .z:9.750046
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/dalvikvm( 4697): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428b5078
D/dalvikvm( 4697): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428b5078
D/jxcore_app_log( 4697): JniHelper::setJavaVM(0x4177c838), pthread_self() = 1639492144
D/JX-Cordova( 4697): jxcore cordova android initializing
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.450394 Y: -0.400421 Z: 9.744522 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450394 .y:-0.400421 .z:9.744522
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3} time:113234
D/UsbSettings( 2588): [AUTORUN] onStop()
D/ActivityManager(  965): no-history finish of ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{43300148 ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/dalvikvm( 4697): GC_CONCURRENT freed 2821K, 13% free 21831K/24832K, paused 2ms+1ms, total 36ms
D/dalvikvm( 4697): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 4697): GC_FOR_ALLOC freed 122K, 12% free 21860K/24832K, paused 28ms, total 28ms
I/dalvikvm-heap( 4697): Grow heap (frag case) to 23.615MB for 98002-byte allocation
D/dalvikvm( 4697): GC_FOR_ALLOC freed 215K, 13% free 21861K/24928K, paused 22ms, total 22ms
I/dalvikvm-heap( 4697): Grow heap (frag case) to 23.662MB for 146998-byte allocation
D/dalvikvm( 4697): GC_FOR_ALLOC freed 256K, 13% free 21909K/25072K, paused 21ms, total 21ms
I/dalvikvm-heap( 4697): Grow heap (frag case) to 23.780MB for 220492-byte allocation
D/dalvikvm( 4697): GC_FOR_ALLOC freed 374K, 14% free 21985K/25288K, paused 22ms, total 22ms
I/dalvikvm-heap( 4697): Grow heap (frag case) to 23.958MB for 330734-byte allocation
,D/dalvikvm( 4697): GC_FOR_ALLOC freed 578K, 14% free 22109K/25612K, paused 37ms, total 38ms
,I/dalvikvm-heap( 4697): Grow heap (frag case) to 24.238MB for 496096-byte allocation
,D/dalvikvm( 4697): GC_FOR_ALLOC freed 879K, 15% free 22288K/26100K, paused 22ms, total 23ms
,D/dalvikvm( 4697): GC_FOR_ALLOC freed 1301K, 14% free 22548K/26100K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4697): Grow heap (frag case) to 25.257MB for 1116206-byte allocation
,D/dalvikvm( 4697): GC_CONCURRENT freed 1723K, 16% free 22931K/27192K, paused 0ms+2ms, total 28ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/dalvikvm( 4697): GC_FOR_ALLOC freed 358K, 16% free 22881K/27192K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4697): Grow heap (frag case) to 26.115MB for 1674304-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4697): GC_CONCURRENT freed 1684K, 19% free 23457K/28828K, paused 2ms+2ms, total 26ms
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/dalvikvm( 4697): GC_FOR_ALLOC freed 1407K, 19% free 23550K/28828K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4697): Grow heap (frag case) to 27.566MB for 2511452-byte allocation
,D/dalvikvm( 4697): GC_CONCURRENT freed 417K, 18% free 25877K/31284K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 4697): GC_FOR_ALLOC freed 4266K, 22% free 24516K/31284K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4697): Grow heap (frag case) to 29.708MB for 3767174-byte allocation
,D/dalvikvm( 4697): GC_CONCURRENT freed 2869K, 27% free 25730K/34964K, paused 2ms+6ms, total 56ms
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,W/jxcore-log( 4697): Initializing JXcore engine
,W/jxcore-log( 4697): JXcore engine is ready
,D/dalvikvm( 4697): GC_CONCURRENT freed 673K, 20% free 28145K/34964K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 4697): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/jxcore-log( 4697): Starting JXcore engine
,W/jxcore-log( 4697): Platform android
W/jxcore-log( 4697): 
,W/jxcore-log( 4697): Process ARCH arm
W/jxcore-log( 4697): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4697): JXcore Cordova bridge is ready!
I/jxcore-log( 4697): 
,W/jxcore-log( 4697): JXcore engine is started
,I/chromium( 4697): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/GAV2    ( 4624): Thread[GAThread,5,main]: No campaign data found.
,I/chromium( 4697): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4697): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4697): Toggling radios to true
I/jxcore-log( 4697): 
,D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43f0cb00:true
,D/BluetoothAdapter( 4697): enable(): BT is already enabled..!
D/WifiStateMachine(  965): handleMessage: E msg.what=131145
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doBoolean: DISCONNECT,
,I/jxcore-log( 4697): Radios toggled
I/jxcore-log( 4697): 
D/WifiService(  965): New client listening to asynchronous messages
D/WifiService(  965): setWifiEnabled: true pid=4697, uid=10304
E/WifiService(  965): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  965): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  965): disconnect pid=4697, uid=10304
,D/WifiService(  965): reconnect pid=4697, uid=10304
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2027): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2027): wlan0: Cancelling scan request
D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2027): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2027): TDLS: Tear down peers
D/wpa_supplicant( 2027): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 2027): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2027): wlan0: Deauthentication notification
D/wpa_supplicant( 2027): wlan0:  * reason 3 (locally generated)
,D/wpa_supplicant( 2027): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2027): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2027): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2027): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2027): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb722cd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2027): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2027): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2027): nl80211: Event message available
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2027): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2027): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: ConnectedState
W/Settings(  965): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131146
D/WifiStateMachine(  965): processMsg: DisconnectingState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiNative-wlan0(  965): doBoolean: RECONNECT
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2027): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2027): Fast associate: Old scan results
D/wpa_supplicant( 2027): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2027): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2027): wlan0: nl80211: scan request
D/wpa_supplicant( 2027): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/wpa_supplicant( 2027): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2027): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147460
D/WifiStateMachine(  965): processMsg: DisconnectingState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection lost
D/WifiStateMachine(  965): Stopping DHCP and clearing IP
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
,D/DhcpStateMachine(  965): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  965): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  965): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/QCNEA   (  600): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  600): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  600): |CAC| updateNetCfgInfo
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC|                   Netconfig               
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  600): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  600): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  600): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  600): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  600): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  600): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| Received bssid= 
D/QCNEA   (  600): |CAC| net type = 3
V/QCNEA   (  600): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  600): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  600): |CAC| 	ssid           =NG700
V/QCNEA   (  600): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  600): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  600): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  600): |CAC| dispatchNetCfg: updating:0xb83768dc
,D/QCNEA   (  600): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/WifiHS20(  965): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
,D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): handleMessage: X
D/QcConnectivityService(  965): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  965): Attempting to switch to mobile
D/QcConnectivityService(  965): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=1 connState=2
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4755 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 4755): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4755): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4755): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
W/NetworkManagementService(  965): route cmd failed: 
W/NetworkManagementService(  965): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  965): '
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  965): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  965): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  965): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  965): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  965): android_net_utils_resetConnections in env=0x628d5100 clazz=0x68f00001 iface=wlan0 mask=0x3
,D/QcConnectivityService(  965): resetConnections(wlan0, 3)
I/PCSuite ( 4755): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4755): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4755): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/NativeCrypto( 1544): Read error: ssl=0x63fdeb80: I/O error during system call, Connection timed out
I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4789 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,V/NativeCrypto( 1544): SSL shutdown failed: ssl=0x63fdeb80: I/O error during system call, Broken pipe
I/ActivityManager(  965): Killing 4143:com.google.android.talk/u0a77 (adj 15): empty #17
,D/HyLog   ( 4789): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4789): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4789): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=false
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
D/LocSvc_java(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 4789): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4789): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4789): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4789): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4789): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4789): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4789): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4789): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4789): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  965): Killing 3108:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  965): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1544): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4697): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4697): 
,I/jxcore-log( 4697): my name is : LGE-LG-D802_PT2533
I/jxcore-log( 4697): 
,I/jxcore-log( 4697): attempting to connect to test coordinator
I/jxcore-log( 4697): 
,I/jxcore-log( 4697): check test folder
I/jxcore-log( 4697): 
,I/jxcore-log( 4697): found test : ./testFindPeers.js
I/jxcore-log( 4697): 
,I/jxcore-log( 4697): found test : ./testReConnect.js
I/jxcore-log( 4697): 
,I/jxcore-log( 4697): found test : ./testSendData.js
I/jxcore-log( 4697): 
,I/jxcore-log( 4697): Test app app.js loaded
I/jxcore-log( 4697): 
,I/Choreographer( 4697): Skipped 125 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4697): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4697): 
,I/chromium( 4697): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
,D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4030): begin check event
,I/AppUp4:CustModeStarterReceiver( 4030): Event For GoodConnectivity
,I/ActivityManager(  965): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4821 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4821): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2027): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2027): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2027): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 2027): nl80211: Survey data missing
D/wpa_supplicant( 2027): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2027): wlan0: BSS: Add new id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 2027): wlan0: New scan results available
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2027): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2027): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2027): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2027): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2027): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2027): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-47 wps
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2027): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2027): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2027): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb722e5a8  current_ssid=0x0
D/wpa_supplicant( 2027): scard is not null..
D/wpa_supplicant( 2027): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdu,mp(len=3): 2a 01 00
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2027): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2027): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2027): wlan0: Cancelling scan request
D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2027): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2027): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2027): RSN: PMKSA cache search - network_ctx=0xb722e5a8 try_opportunistic=0
D/wpa_supplicant( 2027): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2027): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2027): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2027): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2027): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2027): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2027): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2027): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2027): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2027): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2027): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2027): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2027): nl80211: Unsubscribe mgmt frames handle 0xb722d590 (mode change)
D/wpa_supplicant( 2027): nl80211: Subscribe to mgmt frames with non-AP handle 0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2027): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2027):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027):   * freq=2412
D/wpa_supplicant( 2027):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2027):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027):   * Auth Type 0
D/wpa_supplicant( 2027):   * WPA Versions 0x2
I/jxcore-log( 4697): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4697): 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 a0:c5:62:7a:49:97]
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2027): nl80211: Connect request send successfully
D/wpa_supplicant( 2027): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/WifiStateMachine(  965): handleMessage: E msg.what=147461
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2027): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,V/DownloadManager( 4821): DownloadService onCreate
I/DownloadManager( 4821): in removeSpuriousFiles
D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2027): nl80211: Connect event
D/wpa_supplicant( 2027): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2027): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2027): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2027): wlan0: Association info event
D/wpa_supplicant( 2027): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2027): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2027): wlan0: freq=2412 MHz
D/wpa_supplicant( 2027): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2027): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2027): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2027): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): scard is not null..
D/wpa_supplicant( 2027): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2027): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2027): TDLS: Remove peers on association
D/wpa_supplicant( 2027): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2027): EAPOL: enable timer tick
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2027): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2027): wlan0: Cancelling scan request
D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4821): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/eas_req ( 4606): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@428f5778 on behalf of 4821
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 4821): in trimDatabase
V/DownloadManager( 4821): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4821): DownloadService onStartCommand
D/wpa_supplicant( 2027): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 04 0d c6 03 cf 32 8b 58 7c 69 d6 83 fd 4c 50 ...
D/wpa_supplicant( 2027): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2027): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2027): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2027): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2027): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2027):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2027):   key_nonce - hexdump(len=32): 04 0d c6 03 cf 32 8b 58 7c 69 d6 83 fd 4c 50 27 a0 c8 da ef 38 f3 ac ff 5b b5 58 5c 76 f7 ca da
D/wpa_supplicant( 2027):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 04 0d c6 03 cf 32 8b 58 7c 69 d6 83 fd 4c 50 ...
D/wpa_supplicant( 2027): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2027): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2027): Get randomness: len=32 entropy=8
D/wpa_supplicant( 2027): WPA: Renewed SNonce - hexdump(len=32): 3e 3f ac 22 a0 37 e1 19 33 db 7a 03 1b dd 10 ec d7 93 b1 11 e1 64 4b 74 f3 4c 43 73 d9 55 00 16
D/wpa_supplicant( 2027): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): WPA: Nonce1 - hexdump(len=32): 3e 3f ac 22 a0 37 e1 19 33 db 7a 03 1b dd 10 ec d7 93 b1 11 e1 64 4b 74 f3 4c 43 73 d9 55 00 16
D/wpa_supplicant( 2027): WPA: Nonce2 - hexdump(len=32): 04 0d c6 03 cf 32 8b 58 7c 69 d6 83 fd 4c 50 27 a0 c8 da ef 38 f3 ac ff 5b b5 58 5c 76 f7 ca da
D/wpa_supplicant( 2027): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2027): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2027): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2027): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2027): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): WPA: Derived Key MIC - hexdump(len=16): 59 e8 47 49 93 78 9d 18 a1 a3 41 40 57 92 00 9f
D/wpa_supplicant( 2027): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 3e 3f ac 22 a0 37 e1 19 33 db 7a 03 1b dd 10 ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
V/DownloadManager( 4821): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@428f9f00 on behalf of 4821
V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@428f8db8 on behalf of 4821
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed st,ate, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
V/DownloadManager( 4821): DownloadService onDestroy
D/wpa_supplicant( 2027): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 04 0d c6 03 cf 32 8b 58 7c 69 d6 83 fd 4c 50 ...
D/wpa_supplicant( 2027): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2027): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2027): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2027): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2027):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2027):   key_nonce - hexdump(len=32): 04 0d c6 03 cf 32 8b 58 7c 69 d6 83 fd 4c 50 27 a0 c8 da ef 38 f3 ac ff 5b b5 58 5c 76 f7 ca da
D/wpa_supplicant( 2027):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_rsc - hexdump(len=8): 14 15 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_mic - hexdump(len=16): bf 50 8a e6 33 04 18 2b 7b b0 f7 4f 59 57 07 4b
D/wpa_supplicant( 2027): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 04 0d c6 03 cf 32 8b 58 7c 69 d6 83 fd 4c 50 ...
D/wpa_supplicant( 2027): RSN: encrypted key data - hexdump(len=56): 32 f3 38 e9 29 7c b4 ff f4 1b 41 af 3a 26 74 ee 1d 5f e4 1e 2e 1d 52 f7 b9 50 a8 ea f1 89 c5 4b ...
D/wpa_supplicant( 2027): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2027): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2027): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2027): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 81 cb ...
D/wpa_supplicant( 2027): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2027): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2027): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): WPA: Derived Key MIC - hexdump(len=16): e2 cf 05 e8 35 43 ce 05 a2 e5 f2 bf 7b 6e 47 91
D/wpa_supplicant( 2027): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2027): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb722dc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2027):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2027): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2027): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2027): WPA: RSC - hexdump(len=6): 14 15 00 00 00 00
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fa603a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2027):    broadcast key
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new st,ate=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
D/WifiStateMachine(  965): handleMessage: X
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = false
I/wpa_supplicant( 2027): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2027): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2027): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2027): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2027): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2027): EAPOL authentication completed successfully
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection established
D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2027): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  965):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  965): ssid=NG700
D/WifiNative-wlan0(  965): id=0
D/WifiNative-wlan0(  965): mode=station
D/WifiNative-wlan0(  965): pairwise_cipher=CCMP
D/WifiNative-wlan0(  965): group_cipher=CCMP
D/WifiNative-wlan0(  965): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  965): wpa_state=COMPLETED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  965): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4852 uid=10052 gids={50052, 3003}
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-27ms what=147462 obj=android.net.wifi.StateChangeResult@4478f980 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/DhcpStateMachine(  965): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): WaitBeforeStartState
W/linker  ( 4606): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/HtmlEditor( 4606): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4606): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4606): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-23ms what=147462 obj=android.net.wifi.StateChangeResult@44771520 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-23ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
I/dalvikvm( 4606): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
D/HtmlEditor( 4606): register_HtmlEditor, Success
D/HtmlEditor( 4606): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4606): register_HtmlEditorTimer, Success
D/HtmlEditor( 4606): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4606): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4606): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4606): register_HtmlEditorFont, Success
D/HtmlEditor( 4606): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4606): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4606): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/wpa_supplicant( 2027): nl80211: survey data missing!
D/HtmlEditor( 4606): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4606): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4606): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4606): JNI_OnLoad Success
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/HubEmail( 4606): JNI_OnLoad()
I/HubEmail( 4606): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4606): registerNatives()
I/HubEmail( 4606): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4606): registerNativeMethods()
I/HubEmail( 4606): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 4852): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4852): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4852): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): Killing 3887:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4852): [loadRssi] File not exist 
V/LGRssiData( 4852): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4852): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4852): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4852): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4852): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4852): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4852): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4852): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4852): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4852): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4852): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4852): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4852): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  965): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4872 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  965): Killing 4313:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4872): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4872): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4872): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  965):    returned null
D/DhcpStateMachine(  965): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  965): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  965): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  965): handleMessage: X
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4326e958 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4326e958 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-8ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-7ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4889 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  965): Killing 4528:com.android.defcontainer/u0a4 (adj 15): empty #17
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): DHCP successful
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,E/Parcel  (  600): Reading a NULL string not supported here.
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
,W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WifiStateMachine(  965): handleMessage: E msg.what=135190
D/WifiStateMachine(  965): processMsg: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): CaptivePortalCheckState enter
,D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/WifiStateMachine(  965): handleMessage: X
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4889): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  600): Reading a NULL string not supported here.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
E/Parcel  (  600): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
I/ActivityManager(  965): Killing 4564:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4903 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/        (  264): RouteController
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
V/        (  264): RouteController
D/HyLog   ( 4903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4903): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
V/        (  264): RouteController
,D/LGDMSGCM( 4903): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/        (  264): RouteController
W/ContextImpl( 4903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4926 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  965): Killing 4593:com.lge.bnr/1000 (adj 15): empty #17
,V/        (  264): RouteController
D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4926): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  600): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  600): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  600): |CAC| updateNetCfgInfo
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC|                   Netconfig               
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  600): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  600): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  600): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  600): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  600): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  600): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  600): |CAC| net type = 1
V/QCNEA   (  600): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  600): |CAC| Received ssid= NG700
V/QCNEA   (  600): |CAC| 	ssid           =NG700
V/QCNEA   (  600): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  600): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  600): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  600): |CAC| dispatchNetCfg: updating:0xb83768dc
,D/QCNEA   (  600): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
I/NFS     ( 4926): connectivityManager.getNetworkInfo = TYPE_WIFI
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinService( 1970): Checking schedule, now: 1450361505159 next: 1450361446984
,I/CheckinService( 1970): active receiver: enabled
,I/Wireless_Storage( 4926): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4926): intf.getDisplayName() = lo
I/Wireless_Storage( 4926): intf.getDisplayName() = sit0
I/Wireless_Storage( 4926): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4926): intf.getDisplayName() = teql0
I/Wireless_Storage( 4926): intf.getDisplayName() = wlan0
,D/NFS     ( 4926): interface name:wlan0 name:wlan0
D/NFS     ( 4926): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4926): interface name:wlan0 name:wlan0
D/NFS     ( 4926): addr:192.168.1.140 broadcast:192.168.1.255
,I/Wireless_Storage( 4926): CONNECT : WIFI_CONNECT
,I/CheckinService( 1970): Preparing to send checkin request
,I/EventLogService( 1970): Accumulating logs since 1450361414322
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4945 uid=10104 gids={50104, 3003, 1028, 1015}
I/ActivityManager(  965): Killing 4191:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinRequestBuilder( 1970): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1970): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1544): GC_EXPLICIT freed 1051K, 29% free 17827K/24832K, paused 1ms+4ms, total 33ms
,D/dalvikvm(  965): GC_EXPLICIT freed 1819K, 12% free 51144K/57604K, paused 3ms+93ms, total 187ms
D/HyLog   ( 4945): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4945): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4945): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4945): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x42cee0d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1970): awaiting user notification for token
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4974 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4974): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4974): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4974): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 14ms
,W/dalvikvm( 4974): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4974): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4974): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4974): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4974): VFY: replacing opcode 0x62 at 0x005e
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 13ms
,I/MultiDex( 4974): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4974): install
,I/MultiDex( 4974): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,V/WebViewChromium( 4945): Binding Chromium to the main looper Looper (main, tid 1) {428b9578}
,I/chromium( 4945): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4945): Initializing chromium process, renderers=0
,I/MultiDex( 4974): loading existing secondary dex files
,I/MultiDex( 4974): load found 3 secondary dex files
,I/MultiDex( 4974): install done
,W/chromium( 4945): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4945): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4945): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4945): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4945): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4945): Remote Branch: 
I/Adreno-EGL( 4945): Local Patches: 
I/Adreno-EGL( 4945): Reconstruct Branch: 
,D/dalvikvm( 4974): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4974): VFY: unable to resolve instance field 61
,D/dalvikvm( 4974): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4974): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4974): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4974): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4974): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4974): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4974): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4974): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4974): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4974): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428c0728
,D/dalvikvm( 4974): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428c0728
,D/dalvikvm( 4974): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428c0728, skipping init
,D/dalvikvm( 4974): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428c0728
,D/dalvikvm( 4974): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428c0728
,V/JNIHelp ( 4974): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 4945): Starting up...
,I/ActivityManager(  965): Killing 4209:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/dalvikvm( 4974): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428c0728
,D/dalvikvm( 4974): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428c0728
D/dalvikvm( 4974): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428c0728
,D/dalvikvm( 4974): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428c0728
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4789): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4789): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4789): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4789): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4789): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4789): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4755): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4755): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4789): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4789): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4789): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4789): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 4974): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1544): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1544): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1544): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1970): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 4974): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4974): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4974): VFY: replacing opcode 0x6e at 0x000d
,D/WearableService( 1876): callingUid 10006, callindPid: 1876
,I/dalvikvm( 4974): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4974): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4974): VFY: replacing opcode 0x6e at 0x0201
,E/MDM     ( 1425): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1970): Restart initialization of location
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1db7000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1db7000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=3744860328
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2027): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2027): EAPOL: disable timer tick
,D/dalvikvm( 4974): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a744a0
D/dalvikvm( 4974): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a744a0
,D/dalvikvm( 4974): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a744a0, skipping init
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  965): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4974): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5026): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/WifiStateMachine(  965): handleMessage: X
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/dalvikvm( 4974): DexOpt: --- END 'f.apk' (success) ---
D/dalvikvm( 4974): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 86ms
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
I/Adreno-EGL( 4974): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4974): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4974): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4974): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4974): Remote Branch: 
I/Adreno-EGL( 4974): Local Patches: 
I/Adreno-EGL( 4974): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
V/LgDhcpStateMachineHelper(  965): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
,I/Adreno-EGL( 4974): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4974): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4974): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4974): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4974): Remote Branch: 
I/Adreno-EGL( 4974): Local Patches: 
I/Adreno-EGL( 4974): Reconstruct Branch: 
,I/Adreno-EGL( 4974): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4974): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4974): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4974): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4974): Remote Branch: 
I/Adreno-EGL( 4974): Local Patches: 
I/Adreno-EGL( 4974): Reconstruct Branch: 
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=1263366583
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 4974): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1970): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/jxcore-log( 4697): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4697): 
,I/CheckinTask( 1970): Sending checkin request (11459 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/CheckinRequestBuilder( 1970): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1970): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x444e8dc8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1970): awaiting user notification for token
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1970): Classify the device as Phone.
,I/CheckinTask( 1970): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1970): Checking schedule, now: 1450361507596 next: 1450938903590
,I/CheckinService( 1970): active receiver: disabled
,D/GCM     ( 1544): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/GCM     ( 1544): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1544): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
,D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4030): begin check event
,I/AppUp4:CustModeStarterReceiver( 4030): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4030): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4030): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4030): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4030): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4030): handleAsyncCustNotification do not startCustService
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4821): DownloadService onCreate
I/DownloadManager( 4821): in removeSpuriousFiles
,V/DownloadManager( 4821): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@429006b8 on behalf of 4821
D/eas_req ( 4606): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4821): DownloadService onStartCommand
I/DownloadManager( 4821): in trimDatabase
,V/DownloadManager( 4821): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4821): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@42902f08 on behalf of 4821
V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@429038b8 on behalf of 4821
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering(  965): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MobileConnectivityChangeReceiver( 4852): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4852): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4821): DownloadService onDestroy
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4903): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4926): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4926): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 4903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
,D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4030): begin check event
,I/AppUp4:CustModeStarterReceiver( 4030): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/dalvikvm( 1970): GC_CONCURRENT freed 1894K, 22% free 19524K/24832K, paused 2ms+7ms, total 53ms
D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4821): DownloadService onCreate
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4821): in removeSpuriousFiles
,V/DownloadManager( 4821): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@42907ee8 on behalf of 4821
,I/DownloadManager( 4821): in trimDatabase
,V/DownloadManager( 4821): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@42909590 on behalf of 4821
,I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4821): DownloadService onStartCommand
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = true
D/PhoneState( 4327): setPdpRejectCasuse : false
,V/DownloadManager( 4821): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@4290ba90 on behalf of 4821
,D/MobileConnectivityChangeReceiver( 4852): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4852): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4821): DownloadService onDestroy
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4903): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4926): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4926): CONNECT : WIFI_CONNECT
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/dalvikvm( 4697): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4697): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4697): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4697): Shutting down VM
,W/dalvikvm( 4697): threadid=1: thread exiting with uncaught exception (group=0x41877e48)
E/AndroidRuntime( 4697): FATAL EXCEPTION: main
E/AndroidRuntime( 4697): Process: com.test.thalitest, PID: 4697
E/AndroidRuntime( 4697): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4697): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4697): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4697): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4697): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4697): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:153)
E/AndroidRuntime( 4697): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4697): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4697): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4697): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4697): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4697): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4697): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4697): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4697): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4697): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4697): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4697): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4697): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  965):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3 f}
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  965): Activity pause timeout for ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43157eb0 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  965): moveHomeStack:
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  965): resumeTopActivityLocked: Resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1862): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:11:48
,D/UpdateThreadPoolManager( 1862): 2 : This is isUpdating : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WeatherQuickCover( 1862): 2 : quick cover state : opened : 0
D/WeatherService( 1862): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1862): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1862): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1862): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1862): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1862): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:11:49
,D/WeatherService( 1862): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1862): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1862): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1862): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1862): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1862): 2 : requestRefreshAppWidget, isUpdateStart : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/UpdateThreadPoolManager( 1862): 2 : This is isUpdating : false
D/WeatherService( 1862): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1862): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1862): 2 : Map key string is -2
D/lim     ( 1862): 2 : time = 15:11
I/WeatherReflect( 1862): Model Name : LG-D802
D/WeatherTheme( 1862): 2 : Different view - status_min_formatted : 10 != 11
D/WeatherTheme( 1862): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1862): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1862): 2 : Fixed theme : optimus
D/WeatherTheme( 1862): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1862): 2 : quick cover state : opened : 0
D/Weather.Utils( 1862): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1862): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1862): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 7495K, 11% free 70718K/78648K, paused 29ms, total 29ms
,D/dalvikvm( 1490): GC_CONCURRENT freed 5530K, 9% free 60930K/66644K, paused 2ms+5ms, total 27ms
,D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4030): begin check event
,I/AppUp4:CustModeStarterReceiver( 4030): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,V/DownloadManager( 4821): DownloadService onCreate
,I/DownloadManager( 4821): in removeSpuriousFiles
,V/DownloadManager( 4821): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@4290fe40 on behalf of 4821
,I/DownloadManager( 4821): in trimDatabase
,V/DownloadManager( 4821): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4821): DownloadService onStartCommand
V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@42911b48 on behalf of 4821
,V/DownloadManager( 4821): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,V/DownloadManager( 4821): created cursor android.database.sqlite.SQLiteCursor@42913790 on behalf of 4821
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = true
,D/PhoneState( 4327): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4852): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/DownloadManager( 4821): DownloadService onDestroy
,D/MobileConnectivityChangeReceiver( 4852): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMSGCM( 4903): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4926): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4926): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 1490): GC_FOR_ALLOC freed 4872K, 9% free 61907K/67572K, paused 21ms, total 21ms
,I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@428b4f10 time:123601
,D/UsbSettings( 2588): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2588): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2588): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2588): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{430cd0f0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1} time:123617
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1211): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/GAV2    ( 4945): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  965): Killing 4624:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1490): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4228): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4228): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/ActivityManager(  965): Killing 4755:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1211): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.448578 Y: -0.401306 Z: 9.765686 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448578 .y:-0.401306 .z:9.765686
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.451187 Y: -0.396133 Z: 9.751099 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451187 .y:-0.396133 .z:9.751099
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3742): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3742): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  965): Handling package changes for user 0
,I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5198 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5198): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5198): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5198): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  965):   Scheme: "smsto"
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
D/WifiController(  965): battery changed pluggedType: 2
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/PackageManager(  965):   Scheme: "mmsto"
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5198): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5198): MmsConfig.loadMmsSettings
I/Babel   ( 5198): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5198): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5198): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5198): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5198): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5198): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5198): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5198): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5198): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5198): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/Settings( 5198): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 5198): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5198): MmsConfig.loadFromResources
,E/Babel   ( 5198): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5198): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5198): [loadRssi] File not exist 
V/LGRssiData( 5198): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5198): [loadFeatureFromXml] *** start feature loading from xml
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/TelephonyAutoProfiling( 5198): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5198): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5198): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  965): GC_EXPLICIT freed 25525K, 49% free 30729K/59284K, paused 5ms+12ms, total 194ms
,V/GmsNetworkLocationProvi( 1425): DISABLE
,D/AppUp4:Utils( 4030): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 4030): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4030): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
,D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4030): begin check event
D/AppUp4:Utils( 4030): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4030): Event For Nothing, skip.
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5251 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5251): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5251): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5251): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
,I/SystemConfig( 5251): BUILD Country: EU
,I/SystemConfig( 5251): BUILD Operator: OPEN
I/ActivityManager(  965): Killing 4789:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5265 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
I/SystemConfig( 5251): systemFeature RCS result false
,D/SystemConfig( 5251): refreshRcsSupport() :false
I/ActivityManager(  965): Killing 4821:android.process.media/u0a23 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 5265): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5265): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5265): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Killing 4852:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/IcingCorporaProvider( 2657): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1970): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1970): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1970): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/IcingCorporaProvider( 2657): UpdateCorporaTask done [took 208 ms] updated apps [took 208 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  965): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,W/ActivityManager(  965): Activity destroy timeout for ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{43e5a9e0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/WeatherService( 1862): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:12:0
,D/wpa_supplicant( 2027): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/WeatherService( 1862): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1862): 2 : SDK version : 19
,D/WeatherQuickCover( 1862): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1862): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1862): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1862): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361520034, nextTick: 59983, mDrawingTime: 5
,D/UpdateThreadPoolManager( 1862): 2 : This is isUpdating : false
D/WeatherService( 1862): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1862): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1862): 2 : Map key string is -2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361520048, nextTick: 59975, mDrawingTime: 3
,D/lim     ( 1862): 2 : time = 15:12
,I/WeatherReflect( 1862): Model Name : LG-D802
D/WeatherTheme( 1862): 2 : Different view - status_min_formatted : 11 != 12
D/WeatherTheme( 1862): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1862): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1862): 2 : Fixed theme : optimus
,D/WeatherTheme( 1862): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1862): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:12:0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV4    ( 5198): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,I/PowerManagerService(  965): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  965): [updateScreenState] screen on = false
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  965): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8458 usec
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  965): hal_acquire_resources
,I/qcom_sensors_hal(  965): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  965): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  965): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  965): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  965): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  965): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  965): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  965): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.465714 Y: -0.408585 Z: 9.781342 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465714 .y:-0.408585 .z:9.781342
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.453354 Y: -0.404541 Z: 9.796158 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453354 .y:-0.404541 .z:9.796158
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Sensors (  321): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  965): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  965): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  965): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  965): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  965): proximitySensorChanged  positive = true
I/KnockOnPowerController(  965): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.457199 Y: -0.410950 Z: 9.776901 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457199 .y:-0.410950 .z:9.776901
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.453735 Y: -0.400055 Z: 9.783691 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453735 .y:-0.400055 .z:9.783691
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.447449 Y: -0.391891 Z: 9.781128 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447449 .y:-0.391891 .z:9.781128
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.448425 Y: -0.394455 Z: 9.769760 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448425 .y:-0.394455 .z:9.769760
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7de5450
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.444351 Y: -0.405640 Z: 9.776764 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444351 .y:-0.405640 .z:9.776764
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/KeyguardServiceDelegate(  965): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@432437b8)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  965): **** SHOWN CALLED ****
I/WindowManager(  965): No lock screen! windowToken=null
,E/SlideAside( 3742): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  965): handleScreenStateChanged: true
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiServiceExtension(  965): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  965): handleMessage: E msg.what=132097
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2027): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2027): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  965): stopMonitoring
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 965
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43416770 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1862): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:12:4
,I/SlideAside( 3742): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1862): 2 : This is isUpdating : false
D/WeatherAncestor( 1862): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:12:4
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/WeatherService( 1862): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1862): 2 : TimeTick Receiver Unregister
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2,
D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  965): Excessive delay in blankDisplay() while turning screen off: 431ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361524558, nextTick: 55474, mDrawingTime: 1
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361524596, nextTick: 55435, mDrawingTime: 2
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/WeatherService( 1862): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:12:4
,D/WeatherService( 1862): 2 : ACTION screen on
D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/WeatherService( 1862): 2 : shouldTimeTickRegistered : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WeatherService( 1862): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:12:4
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/GsmSST  ( 1450): Emergency Service
D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_ON
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1} (pause complete)
D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_acquire_resources
D/qcom_sensors_hal(  965): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
D/qcom_sensors_hal(  965): hal_smgr_report_delete: handle=0
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.461411 Y: -0.407700 Z: 9.781235 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461411 .y:-0.407700 .z:9.781235
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1} (stop requested)
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  965): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  965): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  965): hal_smgr_report_delete: Rcvd success response from request
,I/LGImmersionVibrator(  965): Vibrator off
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/WifiStateMachine(  965): handleScreenStateChanged: false
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 965
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  965): CMD_SCREEN_OFF 
,D/WifiController(  965): shouldWifiStayAwake TRUE
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
D/KeyguardViewManager( 1143): onScreenTurnedOff()
,I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{42cf2f90 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,D/VolumeVibrator( 1157): clear
D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): handleMessage: X
I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,D/WeatherService( 1862): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:12:4
D/WeatherService( 1862): 2 : ACTION screen off
,D/WeatherService( 1862): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:12:4
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_OFF
D/NfcService( 1474): NFC-C OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
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
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  321): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361532643141657; DSPS: 4949474; Offset: 1450361381597182185
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,E/Ads     ( 1970): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Diskstats( 1970): User is not opted-in to Usage & Diagnostics.
,D/Procstats( 1970): User is not opted-in to Usage & Diagnostics.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361552644183977; DSPS: 5604868; Offset: 1450361381597186907
,D/dalvikvm( 1544): GC_EXPLICIT freed 1509K, 29% free 17851K/24832K, paused 4ms+5ms, total 49ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Netstats( 1970): User is not opted-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1970): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1970): removeStateFiles() called
,D/PerfProfileCollectorService( 1970): User is not opt-in to Usage & Diagnostics.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1211): Disconnected process message: 10
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/dalvikvm( 1157): GC_CONCURRENT freed 2914K, 11% free 25448K/28540K, paused 11ms+1ms, total 33ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361572645728294; DSPS: 6260279; Offset: 1450361381597174828
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361580039, nextTick: 59992, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361580042, nextTick: 59973, mDrawingTime: 6
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361592647260378; DSPS: 6915689; Offset: 1450361381597181033
,D/wpa_supplicant( 2027): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 7 BSSID 8c:04:ff:b9:af:25 SSID 'SALVADOR' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 8c:04:ff:b9:af:25]
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361612648240391; DSPS: 7571081; Offset: 1450361381597184483
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361632649284215; DSPS: 8226475; Offset: 1450361381597190710
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361640035, nextTick: 59992, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361640046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361652650785589; DSPS: 8881885; Offset: 1450361381597166205
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361672652930109; DSPS: 9537315; Offset: 1450361381597174494
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361692653966343; DSPS: 10192709; Offset: 1450361381597173131
,D/wpa_supplicant( 2027): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 a0:c5:62:7a:49:97]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361700029, nextTick: 59998, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361700056, nextTick: 59975, mDrawingTime: 1
,D/dalvikvm( 2644): GC_CONCURRENT freed 7763K, 32% free 16889K/24832K, paused 4ms+2ms, total 47ms
,D/dalvikvm( 2644): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361712655473557; DSPS: 10848118; Offset: 1450361381597184983
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  965): GC_EXPLICIT freed 1513K, 49% free 30687K/59284K, paused 5ms+11ms, total 167ms
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4339eb68: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 4228): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4228): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4228): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4228): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4228): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4228): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4228): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4228): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4228): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4228): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/LocationManagerService(  965): remove 43387170
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  965): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  965): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  965): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2644): GC_CONCURRENT freed 1853K, 32% free 17084K/24832K, paused 3ms+1ms, total 28ms
,D/dalvikvm( 2644): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2644): GC_CONCURRENT freed 1576K, 30% free 17555K/24832K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 2644): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2644): GC_CONCURRENT freed 2046K, 30% free 17487K/24832K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 2644): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/Mlt MonitorService( 2644): parseLastkmsg to dump
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361732657012599; DSPS: 11503529; Offset: 1450361381597167629
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361752658492139; DSPS: 12158937; Offset: 1450361381597182325
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361760042, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361760048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361772658991260; DSPS: 12814313; Offset: 1450361381597193165
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361792659498916; DSPS: 13469690; Offset: 1450361381597182022
,I/Process ( 4697): Sending signal. PID: 4697 SIG: 9
,I/[LGHome]EVENT( 1490): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/InputMethodManagerService(  965): IME STATUS OFF
,I/ActivityManager(  965): Process com.test.thalitest (pid 4697) has died.
,I/WindowState(  965): WIN DEATH: Window{43d4f500 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  965): Client connection lost with reason: 4
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361812660008339; DSPS: 14125067; Offset: 1450361381597172646
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361820039, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361820045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361832661564204; DSPS: 14780478; Offset: 1450361381597172115
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361852663954435; DSPS: 15435916; Offset: 1450361381597181975
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361872664447854; DSPS: 16091292; Offset: 1450361381597187112
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361880042, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361880047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361892672105405; DSPS: 16746903; Offset: 1450361381597184751
,D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2027): nl80211: Disconnect event
D/wpa_supplicant( 2027): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2027): wlan0: Deauthentication notification
D/wpa_supplicant( 2027): wlan0:  * reason 0
D/wpa_supplicant( 2027): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2027): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2027): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2027): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2027): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2027): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2027): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2027): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
D/WifiStateMachine(  965): handleMessage: E msg.what=147460
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection lost
D/WifiStateMachine(  965): Stopping DHCP and clearing IP
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 1,
,D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb722cd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5,
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
,D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2027): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state INITIALIZE,
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2027): EAPOL: External notification - portValid=0,
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 1'
,D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='1',
D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
,D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/DhcpStateMachine(  965): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  965): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiHS20(  965): hidePasspointNotification off =false
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/QCNEA   (  600): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  600): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  600): |CAC| updateNetCfgInfo
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC|                   Netconfig               
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  600): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  600): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  600): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  600): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  600): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  600): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| Received bssid= 
D/QCNEA   (  600): |CAC| net type = 3
V/QCNEA   (  600): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  600): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  600): |CAC| 	ssid           =NG700
V/QCNEA   (  600): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  600): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  600): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  600): |CAC| dispatchNetCfg: updating:0xb83768dc
D/QCNEA   (  600): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
D/wpa_supplicant( 2027): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2027): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2027): wlan0: nl80211: scan request
D/wpa_supplicant( 2027): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/QcConnectivityService(  965): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/wpa_supplicant( 2027): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2027): wlan0: nl80211: Scan trigger
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  965): Attempting to switch to mobile
D/QcConnectivityService(  965): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  965): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  965): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  965): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  965): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5781 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,D/HyLog   ( 5781): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5781): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5781): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 5781): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/        (  264): RouteController
,D/PCSuite ( 5781): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5781): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,W/NetworkManagementService(  965): route cmd failed: 
W/NetworkManagementService(  965): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  965): '
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  965): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  965): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  965): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  965): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  965): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  965): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  965): android_net_utils_resetConnections in env=0x628d5100 clazz=0xb1400001 iface=wlan0 mask=0x3
D/QcConnectivityService(  965): resetConnections(wlan0, 3)
,I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5824 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,V/NativeCrypto( 1544): Read error: ssl=0x63f8eb00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1544): SSL shutdown failed: ssl=0x63f8eb00: I/O error during system call, Broken pipe
,D/HyLog   ( 5824): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5824): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5824): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  965): StoppedState
,D/QRemote ( 5824): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/LocSvc_java(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QRemote ( 5824): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5824): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 5824): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 5824): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 5824): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
D/QRemote ( 5824): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5824): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/VacuumService( 1544): Vacuum at: now=1450361909027 tag=VacuumService
,I/QRemote ( 5824): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  965): Killing 4872:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2027): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2027): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2027): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2027): nl80211: Survey data missing
D/wpa_supplicant( 2027): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2027): wlan0: BSS: Add new id 9 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2027): wlan0: BSS: Add new id 10 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600',
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Add new id 11 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2027): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2027): wlan0: New scan results available
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): WPS: AP c0:ff:d4:d3:aa:4a type 0 added,
D/wpa_supplicant( 2027): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2027): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2027): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2027): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1,
D/wpa_supplicant( 2027): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): WPS: AP[3] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2027): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps,
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2027): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2027): wlan0: 2: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-89 wps
,D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 caps=0x411 level=-86 wps
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2027): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
,D/wpa_supplicant( 2027): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2027): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2027): wlan0:    selected based on RSN IE
,D/wpa_supplicant( 2027): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2027): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb722e5a8  current_ssid=0x0
D/wpa_supplicant( 2027): scard is not null..
D/wpa_supplicant( 2027): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2027): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2027): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 2027): wlan0: Cancelling scan request,
,D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2027): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2027): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2027): RSN: PMKSA cache search - network_ctx=0xb722e5a8 try_opportunistic=0
D/wpa_supplicant( 2027): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2027): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2027): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2027): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2027): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2027): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2027): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2027): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2027): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2027): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2027): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2027): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2027): nl80211: Unsubscribe mgmt frames handle 0xb722d590 (mode change)
D/wpa_supplicant( 2027): nl80211: Subscribe to mgmt frames with non-AP handle 0xb722d590
,D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0b
,D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590,
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb722d590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2027): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2027):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027):   * freq=2412
D/wpa_supplicant( 2027):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2027):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027):   * Auth Type 0
D/wpa_supplicant( 2027):   * WPA Versions 0x2
D/Tethering(  965): MasterInitialState.processMessage what=3
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 a0:c5:62:7a:49:97],
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
,D/WifiStateMachine(  965): handleMessage: E msg.what=147461
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2027): nl80211: Connect request send successfully
,D/wpa_supplicant( 2027): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37,
,D/wpa_supplicant( 2027): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
,D/CaptivePortalTracker(  965): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false,
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2027): nl80211: Connect event
D/wpa_supplicant( 2027): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2027): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2027): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2027): wlan0: Association info event
D/wpa_supplicant( 2027): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2027): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2027): wlan0: freq=2412 MHz
D/wpa_supplicant( 2027): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2027): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2027): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2027): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): scard is not null..
D/wpa_supplicant( 2027): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2027): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2027): TDLS: Remove peers on association
D/wpa_supplicant( 2027): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2027): EAPOL: enable timer tick
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2027): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2027): wlan0: Cancelling scan request
,D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/wpa_supplicant( 2027): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 56 f5 45 33 ad ce 8e d3 7f a2 e1 0f ef 04 bf ...
D/wpa_supplicant( 2027): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2027): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2027): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2027): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2027): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2027):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2027):   key_nonce - hexdump(len=32): 56 f5 45 33 ad ce 8e d3 7f a2 e1 0f ef 04 bf 34 79 db 72 94 4f 83 8d b0 4e 3f 09 ad d4 9f 11 a4
D/wpa_supplicant( 2027):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 56 f5 45 33 ad ce 8e d3 7f a2 e1 0f ef 04 bf ...
D/wpa_supplicant( 2027): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2027): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2027): Get randomness: len=32 entropy=5
,D/wpa_supplicant( 2027): WPA: Renewed SNonce - hexdump(len=32): 73 f9 1e da a6 38 86 42 79 fa 52 39 7b 14 58 e7 10 d4 15 1a 37 fa 32 e1 67 a3 55 03 96 81 22 3d
D/wpa_supplicant( 2027): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): WPA: Nonce1 - hexdump(len=32): 73 f9 1e da a6 38 86 42 79 fa 52 39 7b 14 58 e7 10 d4 15 1a 37 fa 32 e1 67 a3 55 03 96 81 22 3d
D/wpa_supplicant( 2027): WPA: Nonce2 - hexdump(len=32): 56 f5 45 33 ad ce 8e d3 7f a2 e1 0f ef 04 bf 34 79 db 72 94 4f 83 8d b0 4e 3f 09 ad d4 9f 11 a4
D/wpa_supplicant( 2027): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2027): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2027): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2027): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2027): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): WPA: Derived Key MIC - hexdump(len=16): be 7c 63 15 5b dd 63 40 fd 29 12 aa d0 07 bd 95
,D/wpa_supplicant( 2027): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 73 f9 1e da a6 38 86 42 79 fa 52 39 7b 14 58 ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 2027): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 56 f5 45 33 ad ce 8e d3 7f a2 e1 0f ef 04 bf ...
D/wpa_supplicant( 2027): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2027): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2027): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2027): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2027):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2027):   key_nonce - hexdump(len=32): 56 f5 45 33 ad ce 8e d3 7f a2 e1 0f ef 04 bf 34 79 db 72 94 4f 83 8d b0 4e 3f 09 ad d4 9f 11 a4
D/wpa_supplicant( 2027):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_rsc - hexdump(len=8): 05 17 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_mic - hexdump(len=16): 4d 60 47 b6 b7 0f fe fd 67 b5 6a ca 12 38 d3 73
D/wpa_supplicant( 2027): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 56 f5 45 33 ad ce 8e d3 7f a2 e1 0f ef 04 bf ...
D/wpa_supplicant( 2027): RSN: encrypted key data - hexdump(len=56): 89 e5 56 b6 07 90 a1 5d a7 c3 73 94 41 d9 f7 6e 96 df 9a 68 a7 d3 85 0c e3 06 30 40 ed 80 c5 5d ...
D/wpa_supplicant( 2027): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2027): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2027): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2027): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 81 cb ...
D/wpa_supplicant( 2027): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2027): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2027): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): WPA: Derived Key MIC - hexdump(len=16): df 94 c6 67 b9 e8 8c 46 ed 46 28 2a 4e b1 75 2a
,D/wpa_supplicant( 2027): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2027): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb722dc54 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 2027):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=1,
D/wpa_supplicant( 2027): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2027): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2027): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16),
D/wpa_supplicant( 2027): WPA: RSC - hexdump(len=6): 05 17 00 00 00 00
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fa603a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2027):    broadcast key
I/wpa_supplicant( 2027): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2027): wlan0: Cancelling authentication timeout
,D/wpa_supplicant( 2027): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2027): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2027): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=1,
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2027): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state AUTHENTICATED,
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 2027): EAPOL authentication completed successfully
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection established
,D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2027): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  965):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  965): ssid=NG700
D/WifiNative-wlan0(  965): id=0
D/WifiNative-wlan0(  965): mode=station
D/WifiNative-wlan0(  965): pairwise_cipher=CCMP
D/WifiNative-wlan0(  965): group_cipher=CCMP
D/WifiNative-wlan0(  965): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  965): wpa_state=COMPLETED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  965): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
,D/DhcpStateMachine(  965): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): WaitBeforeStartState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
,D/WifiStateMachine(  965): ObtainingIpState{ when=-32ms what=147462 obj=android.net.wifi.StateChangeResult@4315d1c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@42c9f980 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-27ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
,D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] connect :false
I/AppUp4:CustModeStarterReceiver( 4030): onReceive
D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
D/AppUp4:CustFacade( 4030): isPhone : true
I/LicenseContentProvider( 2984): start selecting data
D/SIMObserver( 2984): simInfo1
I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4030): begin check event
I/AppUp4:CustModeStarterReceiver( 4030): Event For GoodConnectivity
,I/ActivityManager(  965): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5864 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5864): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5864): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5864): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  965):    returned null
D/DhcpStateMachine(  965): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring up wlan0
,D/WifiStateMachine(  965): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  965): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  965): handleMessage: X
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4326e958 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4326e958 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): DHCP successful
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
,D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/WifiStateMachine(  965): handleMessage: E msg.what=135190
D/WifiStateMachine(  965): processMsg: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): CaptivePortalCheckState enter
,D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  600): Reading a NULL string not supported here.
,E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/Parcel  (  600): Reading a NULL string not supported here.
E/Parcel  (  600): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  600): Reading a NULL string not supported here.
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  965): handleMessage: X
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/DownloadManager( 5864): DownloadService onCreate
,V/        (  264): RouteController
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/DownloadManager( 5864): in removeSpuriousFiles
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4606): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 5864): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@428f5798 on behalf of 5864
,V/        (  264): RouteController
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4327): networkInfo.isConnected() = false
,I/DownloadManager( 5864): in trimDatabase
,V/DownloadManager( 5864): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@428f86c0 on behalf of 5864
,V/        (  264): RouteController
,V/        (  264): RouteController
V/        (  264): RouteController
,V/DownloadManager( 5864): DownloadService onStartCommand
V/DownloadManager( 5864): DownloadService onStartCommand
,V/DownloadManager( 5864): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5904 uid=10052 gids={50052, 3003}
V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@428fca28 on behalf of 5864
W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/        (  264): RouteController
,V/DownloadManager( 5864): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@42900a80 on behalf of 5864
,V/DownloadManager( 5864): DownloadService onDestroy
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/ActivityManager(  965): Killing 4889:com.lge.drmservice/u0a66 (adj 15): empty #17
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  600): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  600): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  600): |CAC| updateNetCfgInfo
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC|                   Netconfig               
V/QCNEA   (  600): |CAC| *********************************************
V/QCNEA   (  600): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  600): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  600): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  600): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  600): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  600): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  600): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  600): |CAC| net type = 1
V/QCNEA   (  600): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  600): |CAC| Received ssid= NG700
V/QCNEA   (  600): |CAC| 	ssid           =NG700
V/QCNEA   (  600): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  600): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  600): |CAC| *********************************************
D/QCNEA   (  600): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  600): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  600): |CAC| dispatchNetCfg: updating:0xb83768dc
D/QCNEA   (  600): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/HyLog   ( 5904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5904): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5904): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5904): [loadRssi] File not exist 
V/LGRssiData( 5904): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5904): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 5904): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 5904): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/BaseRuntimeLoader( 5904): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 5904): onReceive CONNECTIVITY_CHANGE networkType=1
W/BaseRuntimeLoader( 5904): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5904): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 5904): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5904): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5904): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  965): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5925 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4903:com.lge.lgdmsgcm/1000 (adj 15): empty #17
E/PhoneMonitor( 5904): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5904): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/CheckinService( 1970): Checking schedule, now: 1450361912539 next: 1450361537590
,I/CheckinService( 1970): active receiver: enabled
,D/HyLog   ( 5925): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5925): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5925): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1970): Preparing to send checkin request
,I/EventLogService( 1970): Accumulating logs since 1450361505207
,I/CheckinRequestBuilder( 1970): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5946 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  965): Killing 4926:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,E/ActivityThread( 1970): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5946): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5946): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5946): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  965): Killing 4945:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5959 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361912673047049; DSPS: 17402294; Offset: 1450361381597180350
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 5959): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5959): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5959): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5959): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5974 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  965): Killing 4974:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
,D/HyLog   ( 5974): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5974): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5974): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 5974): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Wireless_Storage( 5974): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 5974): intf.getDisplayName() = lo
I/Wireless_Storage( 5974): intf.getDisplayName() = sit0
I/Wireless_Storage( 5974): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5974): intf.getDisplayName() = teql0
,I/Wireless_Storage( 5974): intf.getDisplayName() = wlan0
D/NFS     ( 5974): interface name:wlan0 name:wlan0
V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NFS     ( 5974): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5974): interface name:wlan0 name:wlan0
D/NFS     ( 5974): addr:192.168.1.140 broadcast:192.168.1.255
,I/Wireless_Storage( 5974): CONNECT : WIFI_CONNECT
,I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5986 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 5198:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/HyLog   ( 5986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5986): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/CheckinRequestBuilder( 1970): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x44febeb0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5998 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5998): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5998): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5998): VFY: replacing opcode 0x60 at 0x000b
,W/GAV2    ( 5986): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 5998): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5998): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5998): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5998): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5998): install
,I/MultiDex( 5998): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5998): loading existing secondary dex files
,I/MultiDex( 5998): load found 3 secondary dex files
,I/MultiDex( 5998): install done
,D/dalvikvm( 5998): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5998): VFY: unable to resolve instance field 61
,D/dalvikvm( 5998): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 5998): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5998): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5998): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5998): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5998): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5998): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 5998): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5998): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5998): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b7428
,D/dalvikvm( 5998): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b7428
,D/dalvikvm( 5998): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b7428, skipping init
,D/dalvikvm( 5998): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b7428
,D/dalvikvm( 5998): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b7428
,V/JNIHelp ( 5998): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5986): Binding Chromium to the main looper Looper (main, tid 1) {428af4f0}
,I/chromium( 5986): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5986): Initializing chromium process, renderers=0
,W/chromium( 5986): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5986): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5986): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5986): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5986): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5986): Remote Branch: 
I/Adreno-EGL( 5986): Local Patches: 
I/Adreno-EGL( 5986): Reconstruct Branch: 
,D/dalvikvm( 5998): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b7428
,D/dalvikvm( 5998): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428b7428
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 5998): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b7428
D/dalvikvm( 5998): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428b7428
,I/NSApplication( 5986): Starting up...
,I/ActivityManager(  965): Killing 5251:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 5824): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5824): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5824): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5824): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5824): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5824): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5781): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5781): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5824): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5824): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5824): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5824): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ProviderInstaller( 5998): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1544): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1544): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1544): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1970): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/wpa_supplicant( 2027): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2027): EAPOL: disable timer tick
,D/WearableService( 1876): callingUid 10006, callindPid: 1876
,E/MDM     ( 1425): [73] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 5998): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 5998): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5998): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1970): Restart initialization of location
,I/dalvikvm( 5998): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,W/dalvikvm( 5998): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5998): VFY: replacing opcode 0x6e at 0x0201
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  965): GC_EXPLICIT freed 2705K, 49% free 30677K/59284K, paused 3ms+7ms, total 95ms
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1db7000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1db7000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
V/LgDhcpStateMachineHelper(  965): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=1750112894
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/GCM     ( 1544): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1544): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
D/ConnectivityServiceHSM(  965): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 5998): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a78740
,D/dalvikvm( 5998): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a78740
,D/dalvikvm( 5998): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a78740, skipping init
,I/GoogleURLConnFactory( 1544): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1544): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1544): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1544): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1544): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1544): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1544): GC_CONCURRENT freed 1819K, 28% free 18048K/24832K, paused 2ms+3ms, total 25ms
,W/Uploader( 1544): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1544): No account for auth token provided
,W/Uploader( 1544):  no longer exists, so no auth token.
,W/Uploader( 1544): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/dalvikvm( 5998): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,W/ProcessCpuTracker(  965): Skipping unknown process pid 5860
,W/ProcessCpuTracker(  965): Skipping unknown process pid 5861
,W/ProcessCpuTracker(  965): Skipping unknown process pid 5875
,W/ProcessCpuTracker(  965): Skipping unknown process pid 5878
,W/ProcessCpuTracker(  965): Skipping unknown process pid 6081
D/dalvikvm( 6084): DexOpt: load 3ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 5998): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5998): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 100ms
,I/Adreno-EGL( 5998): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5998): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5998): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5998): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5998): Remote Branch: 
I/Adreno-EGL( 5998): Local Patches: 
I/Adreno-EGL( 5998): Reconstruct Branch: 
,I/Adreno-EGL( 5998): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5998): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5998): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5998): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5998): Remote Branch: 
I/Adreno-EGL( 5998): Local Patches: 
I/Adreno-EGL( 5998): Reconstruct Branch: 
,I/Adreno-EGL( 5998): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5998): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5998): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5998): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5998): Remote Branch: 
I/Adreno-EGL( 5998): Local Patches: 
I/Adreno-EGL( 5998): Reconstruct Branch: 
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=1014621439
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 5998): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1970): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/NativeCrypto( 1970): SSL shutdown failed: ssl=0x63e2f5d0: I/O error during system call, Connection timed out
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/NativeCrypto( 1970): SSL shutdown failed: ssl=0x6cdee070: I/O error during system call, Connection timed out
,I/CheckinTask( 1970): Sending checkin request (11454 bytes)
,I/CheckinRequestBuilder( 1970): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1970): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
,D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4030): begin check event
,I/AppUp4:CustModeStarterReceiver( 4030): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4030): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4030): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4030): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4030): handleAsync isTriedOnce : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/AppUp4:CustModeStarterReceiver( 4030): handleAsyncCustNotification do not startCustService
V/DownloadManager( 5864): DownloadService onCreate
I/DownloadManager( 5864): in removeSpuriousFiles
D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4606): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 5864): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@42905250 on behalf of 5864
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/DownloadManager( 5864): in trimDatabase
V/DownloadManager( 5864): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@42906748 on behalf of 5864
D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  965): MasterInitialState.processMessage what=3
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = false
V/DownloadManager( 5864): DownloadService onStartCommand
D/MobileConnectivityChangeReceiver( 5904): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5904): onReceive CONNECTIVITY_CHANGE networkType=1,
V/DownloadManager( 5864): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@429088f8 on behalf of 5864
W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMSGCM( 5959): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 5959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 5864): DownloadService onDestroy
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5974): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5974): CONNECT : WIFI_CONNECT
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4030): begin check event
,I/AppUp4:CustModeStarterReceiver( 4030): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5864): DownloadService onCreate
,I/DownloadManager( 5864): in removeSpuriousFiles
V/DownloadManager( 5864): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@4290cb40 on behalf of 5864
,I/DownloadManager( 5864): in trimDatabase
,V/DownloadManager( 5864): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@4290e9b0 on behalf of 5864
V/DownloadManager( 5864): DownloadService onStartCommand
,V/DownloadManager( 5864): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4327): networkInfo.isConnected() = true
,D/PhoneState( 4327): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5904): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5904): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/CheckinRequestBuilder( 1970): awaiting user notification for token
,V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@42910728 on behalf of 5864
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x44f9afc0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
V/DownloadManager( 5864): DownloadService onDestroy
,D/LGDMSGCM( 5959): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 5974): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5974): CONNECT : WIFI_CONNECT
W/ContextImpl( 5959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/CheckinRequestBuilder( 1970): Classify the device as Phone.
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinTask( 1970): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1970): Checking schedule, now: 1450361915625 next: 1450939311623
,D/dalvikvm( 1970): GC_CONCURRENT freed 1948K, 21% free 19623K/24832K, paused 6ms+4ms, total 62ms
,D/dalvikvm( 1970): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 1970): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/CheckinService( 1970): active receiver: disabled
,I/CheckinService( 1970): Checking schedule, now: 1450361915677 next: 1450939311623
,I/CheckinService( 1970): active receiver: disabled
,D/GCM     ( 1544): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4030): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
,D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
,D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4030): begin check event
,I/AppUp4:CustModeStarterReceiver( 4030): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5864): DownloadService onCreate
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4327): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4327): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4327): networkInfo.isConnected() = true
,D/PhoneState( 4327): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5904): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5904): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5959): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5974): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5974): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 5864): in removeSpuriousFiles
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 5864): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@429148f0 on behalf of 5864
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 5864): in trimDatabase
V/DownloadManager( 5864): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@42915f58 on behalf of 5864
V/DownloadManager( 5864): DownloadService onStartCommand
V/DownloadManager( 5864): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@42918498 on behalf of 5864
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 5864): DownloadService onDestroy
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 5986): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  965): Killing 5265:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3742): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3742): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  965): Handling package changes for user 0
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6184 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
,D/HyLog   ( 6184): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6184): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6184): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 6184): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6184): MmsConfig.loadMmsSettings
I/Babel   ( 6184): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6184): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6184): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 6184): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 6184): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6184): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 6184): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6184): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6184): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6184): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6184): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6184): MmsConfig.loadFromResources
,E/Babel   ( 6184): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6184): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/Settings( 6184): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GmsNetworkLocationProvi( 1425): DISABLE
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/LGRssiData( 6184): [loadRssi] File not exist 
V/LGRssiData( 6184): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6184): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6184): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6184): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6184): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4030): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4030): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4030): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4030): onReceive
D/AppUp4:CustFacade( 4030): Context : android.app.ReceiverRestrictedContext@428cdf80
D/AppUp4:CustFacade( 4030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4030): isOpenOperator : true
,D/AppUp4:CustFacade( 4030): isPhone : true
,I/LicenseContentProvider( 2984): start selecting data
,D/SIMObserver( 2984): simInfo1
,I/AppUp4:EulaManager( 4030): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4030): begin check event
D/AppUp4:Utils( 4030): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4030): Event For Nothing, skip.
,D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6233 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6233): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6233): BUILD Country: EU
,I/SystemConfig( 6233): BUILD Operator: OPEN
I/ActivityManager(  965): Killing 4228:com.android.vending/u0a50 (adj 15): empty #17
,I/SystemConfig( 6233): systemFeature RCS result false
,D/SystemConfig( 6233): refreshRcsSupport() :false
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6247 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): Killing 5781:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/HyLog   ( 6247): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6247): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6247): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): Killing 5824:com.lge.qremote/u0a96 (adj 15): empty #17
,I/IcingCorporaProvider( 2657): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6264 uid=10050 gids={50050, 3003, 1028, 1015}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  965): GC_EXPLICIT freed 2491K, 49% free 30746K/59284K, paused 3ms+15ms, total 158ms
,D/HyLog   ( 6264): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6264): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6264): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6264): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6264): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6264): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6264): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6264): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 6264): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6264): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6264): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6264): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6264): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6264): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6264): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/IcingCorporaProvider( 2657): UpdateCorporaTask done [took 494 ms] updated apps [took 494 ms] 
,W/Settings( 6264): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6264): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6264): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6264): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6264): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 6264): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6264): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6264): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6264): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6264): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6264): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 5864): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@4291d728 on behalf of 6264
,I/dalvikvm( 6264): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 6264): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6264): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 6264): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6264): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6264): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6264): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6264): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6264): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1970): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1970): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 6264): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  965): Killing 4606:com.lge.email/u0a24 (adj 15): empty #17
I/Icing   ( 1970): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6264): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6264): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6264): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6264): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6264): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6264): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6264): Total arena pages for JIT: 11
,I/dalvikvm( 6264): Total arena pages for JIT: 12
I/dalvikvm( 6264): Total arena pages for JIT: 13
,I/dalvikvm( 6264): Total arena pages for JIT: 14
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6264): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6264): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Finsky  ( 6264): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6264): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1425): client connected with version: 7571000
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6184): Thread[GAThread,5,main]: No campaign data found.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361932677929525; DSPS: 18057814; Offset: 1450361381597180014
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361940045, nextTick: 59977, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450361940053, nextTick: 59978, mDrawingTime: 1
,D/Finsky  ( 6264): [507] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6264): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361952678915176; DSPS: 18713206; Offset: 1450361381597189102
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361972679423850; DSPS: 19368583; Offset: 1450361381597178977
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450361992679929544; DSPS: 20023959; Offset: 1450361381597196390
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362000042, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362000056, nextTick: 59977, mDrawingTime: 0
,I/ActivityManager(  965): Killing 5904:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362012692883042; DSPS: 20679744; Offset: 1450361381597179917
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362032693373204; DSPS: 21335120; Offset: 1450361381597181798
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362052693870228; DSPS: 21990496; Offset: 1450361381597190541
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362060042, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362060055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362072698599169; DSPS: 22646011; Offset: 1450361381597189257
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362092699602550; DSPS: 23301404; Offset: 1450361381597185558
,D/wpa_supplicant( 2027): wlan0: BSS: Remove id 9 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 10 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 11 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 a0:c5:62:7a:49:97]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 9e:93:4e:3e:ba:c5]
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362112700591889; DSPS: 23956796; Offset: 1450361381597198335
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362120038, nextTick: 59973, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362120051, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362132702828969; DSPS: 24612230; Offset: 1450361381597177114
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362152704347547; DSPS: 25267640; Offset: 1450361381597169813
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362172705830401; DSPS: 25923048; Offset: 1450361381597187823
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362180047, nextTick: 59978, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362180050, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362192707401815; DSPS: 26578460; Offset: 1450361381597172323
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362212709043065; DSPS: 27233873; Offset: 1450361381597196142
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43381d30: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 6264): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6264): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6264): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6264): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6264): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6264): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6264): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6264): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 6264): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6264): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1211): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362232710553293; DSPS: 27889283; Offset: 1450361381597180491
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362240037, nextTick: 59987, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362240041, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362252712693418; DSPS: 28544713; Offset: 1450361381597184385
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362272713182434; DSPS: 29200089; Offset: 1450361381597185120
,I/ActivityManager(  965): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6669 uid=10068 gids={50068, 3003, 1028, 1015}
,D/HyLog   ( 6669): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6669): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6669): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ActivityThread( 6669): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GoogleURLConnFactory( 1970): Using platform SSLCertificateSocketFactory
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GAV2    ( 6669): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1544): GC_EXPLICIT freed 1709K, 28% free 18044K/24832K, paused 2ms+5ms, total 37ms
,D/dalvikvm(  965): GC_EXPLICIT freed 2382K, 49% free 30688K/59284K, paused 3ms+8ms, total 116ms
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4340d9b0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,W/SubscribedFeeds( 1970): Hard error
,D/SyncManager(  965): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 903168, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  965): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 903794, reason: Periodic
,I/ActivityManager(  965): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6711 uid=10072 gids={50072, 3003}
,D/HyLog   ( 6711): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6711): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6711): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/AbstractGoogleClient( 6711): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager(  965): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6731 uid=10016 gids={50016, 3003, 1028, 1015}
,D/HyLog   ( 6731): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6731): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6731): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CalendarProvider2( 6731): Created com.android.providers.calendar.CalendarAlarmManager@428d59c0(com.android.providers.calendar.CalendarProvider2@428cc928)
,I/Gmail   ( 6669): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6669): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6669): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6669): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6669): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5341, normalSync: true
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x431e6298: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4318e878: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/CalendarSyncAdapter( 6711): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6711): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6711): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6711): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6711): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:836)
E/CalendarSyncAdapter( 6711): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:412)
E/CalendarSyncAdapter( 6711): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:345)
E/CalendarSyncAdapter( 6711): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:463)
E/CalendarSyncAdapter( 6711): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6711): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6711): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6711): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6711): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6711): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6711): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6711): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6711): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6711): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6711): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6711): 	... 12 more
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/SyncManager(  965): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 903293, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  965): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 904179, reason: Periodic
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 9857K, 14% free 68590K/79068K, paused 34ms, total 34ms
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x432d1a30: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/SyncManager(  965): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, latestRunTime 903288, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  965): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, latestRunTime 904257, reason: Periodic
,I/SyncAdapterService( 5986): Ignoring sync request for non-current account
,I/ActivityManager(  965): Killing 5946:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  965): Killing 5925:com.android.chrome/u0a63 (adj 15): empty #18
,I/ActivityManager(  965): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6758 uid=10107 gids={50107, 3003, 1028, 1015}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6758): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6758): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6758): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicStore( 6758): Database version: 91
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,W/ContextImpl( 6758): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/BaseRuntimeLoader( 6758): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6758): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6758): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6758): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/ContextImpl( 6758): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/dalvikvm(  965): GC_EXPLICIT freed 3006K, 49% free 30740K/59284K, paused 3ms+8ms, total 116ms
,I/MediaRouter( 6758): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4336ddf8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/ContactsSyncAdapter( 1544): innerSync failed
D/ContactsSyncAdapter( 1544): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1544): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1544): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1544): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1544): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1544): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1544): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1544): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
D/ContactsSyncAdapter( 1544): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1544): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
D/ContactsSyncAdapter( 1544): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
D/ContactsSyncAdapter( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,D/SyncManager(  965): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 903304, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  965): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 904548, reason: Periodic
,I/ActivityManager(  965): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6779 uid=10063 gids={50063, 3003, 1028, 1015}
,D/HyLog   ( 6779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6779): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6779): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 24ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
,D/DelayedSyncController( 6779): Delaying sync.
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
I/ActivityManager(  965): Killing 5959:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm( 1544): GC_EXPLICIT freed 1587K, 28% free 18014K/24832K, paused 4ms+4ms, total 41ms
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,I/ConfigStore( 6758): Config Database version: 1
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x44f00388: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/MusicSyncAdapter( 6758): Sync failed due to an authentication issue.
,W/ContextImpl( 6758): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/ActivityManager(  965): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6806 uid=10073 gids={50073, 3003, 1028, 1015}
,D/SyncManager(  965): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 903315, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  965): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 904857, reason: Periodic
,W/ContextImpl( 6758): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/HyLog   ( 6806): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6806): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6806): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/ContextImpl( 6758): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/CacheService( 6758): onCreate
I/ActivityManager(  965): Start proc com.lge.app.richnote for service com.lge.app.richnote/.sync.syncadapter.GoogleDriveSyncService: pid=6822 uid=10034 gids={50034, 3003, 1028, 1015}
,W/ArtDownloadService( 6758): Setting cache size 0
,W/ArtDownloadService( 6758): Setting cache size 0
,D/HyLog   ( 6822): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6822): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6822): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/CacheService( 6758): onBind
,W/ContextImpl( 6758): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/CalendarProvider2( 6731): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6731): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  965): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6836 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 5974:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,D/HyLog   ( 6836): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6836): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6836): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/MusicLeanback( 6758): Conditions not met for autocaching.
,I/MusicLeanback( 6758): Stop autocaching.
,D/CacheService( 6758): onDestroy
I/ActivityManager(  965): Killing 5998:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Config  ( 6836): LGCalendar ver.4.2.6
,I/Config  ( 6836): start check model
I/Config  ( 6836): start check native_ca
,E/Config  ( 6836): [setCountryAndOperator] Operator=OPEN, Country=EU
,E/SyncAdapter( 6822): onPerformSync in richnote account name thalitester@gmail.com
,I/ActivityManager(  965): Killing 6184:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  965): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=6852 uid=10124 gids={50124, 3003, 1028, 1015, 3002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6852): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6852): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6852): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/BaseRuntimeLoader( 6852): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6852): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6852): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6852): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/AlertReceiver( 6836): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6836): Start InitializeAlertRingtoneService.onHandleIntent
,D/CalendarWidget( 6836): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 6836): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/AlertService( 6836): Beginning updateAlertNotification
,I/InitNotificationRingtoneService( 6836): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 6836): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 6836): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 6836): End InitializeAlertRingtoneService.onHandleIntent
,D/AlertService( 6836): No fired or scheduled alerts
,I/ActivityManager(  965): Killing 2984:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityThread( 4030): Removing dead content provider:android.content.ContentProviderProxy@428d4680
,D/PlayMovies( 6852): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/CalendarWidget( 6836): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 6836): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,I/MediaRouter( 6852): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 6852): MediaRouteManager.maybeRestoreRoute:188 sessionRestore routeId: 
,D/PlayMovies( 6852): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/GAV2    ( 6806): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/PlayMovies( 6852): TransferService.onCreate:52 creating transfer service
,D/WifiService(  965): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@44a2b6b0}
,D/PlayMovies( 6852): MediaRouteManager.onRouteAdded:140 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 6852): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataScheduler( 6806): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4322a870: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,E/PlayMovies( 6852): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:70 Cannot get user auth
E/PlayMovies( 6852): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 6852): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 6852): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 6852): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 6852): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 6852): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 6852): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 6852): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/PlayMovies( 6852): AccountManagerWrapper.blockingAuthenticate:165 Authentication failed
E/PlayMovies( 6852): com.google.android.videos.accounts.AccountManagerWrapper$AuthTokenException: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 6852): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:71)
E/PlayMovies( 6852): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 6852): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 6852): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 6852): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/PlayMovies( 6852): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 6852): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 6852): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 6852): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 6852): 	... 4 more
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/dalvikvm(  965): GC_EXPLICIT freed 2757K, 49% free 30755K/59284K, paused 2ms+7ms, total 87ms
,D/SyncManager(  965): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 903341, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  965): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 905581, reason: Periodic
,I/ActivityManager(  965): Killing 4030:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/GCoreUlr( 1425): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1425): Using Auth Proxy for data requests.
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1544): GC_EXPLICIT freed 921K, 28% free 18013K/24832K, paused 2ms+3ms, total 25ms
,D/CalendarWidget( 6836): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 6836): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,E/GCoreUlr( 1425): 
E/GCoreUlr( 1425): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1425): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1425): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1425): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1425): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1425): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1425): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1425): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1425): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1425): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1425): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1425): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1425): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1425): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1425): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1425): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager(  965): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 903357, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  965): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 905804, reason: Periodic
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,E/ReminderSync( 1970): AuthError [T SyncAdapterThread-1:id=252:priority=5:group=main]
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  965): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, latestRunTime 903363, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  965): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, latestRunTime 906027, reason: Periodic
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43fe7868: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
,E/HttpIssuerBase( 6806): Attempt to consume entity of HttpIssuer when no request is executing.
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
E/HttpIssuerBase( 6806): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 6806): java.io.IOException
E/HttpIssuerBase( 6806): 	at Eo.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 6806): 	at DS.b(DefaultAuthenticatedHttpIssuer.java:148)
E/HttpIssuerBase( 6806): 	at Pm.a(AccountMetadataUpdater.java:226)
E/HttpIssuerBase( 6806): 	at Pm.a(AccountMetadataUpdater.java:139)
E/HttpIssuerBase( 6806): 	at Qr.a(LegacySyncManager.java:776)
E/HttpIssuerBase( 6806): 	at Qr.a(LegacySyncManager.java:541)
E/HttpIssuerBase( 6806): 	at Qr.a(LegacySyncManager.java:95)
E/HttpIssuerBase( 6806): 	at Qt.run(LegacySyncManager.java:396)
E/HttpIssuerBase( 6806): 	at Vu.a(NetworkUtilitiesImpl.java:30)
E/HttpIssuerBase( 6806): 	at Qs.run(LegacySyncManager.java:393)
E/SyncManager( 6806): AuthenticatorException
E/SyncManager( 6806): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 6806): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/SyncManager( 6806): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 6806): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/SyncManager( 6806): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 6806): 	at android.os.Binder.execTransact(Binder.java:407)
E/SyncManager( 6806): 	at dalvik.system.NativeStart.run(Native Method)
,W/GAV2    ( 6806): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService(  965): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@44a2b6b0}
,E/Auth.Api.Credentials( 1970): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  965): Killing 6233:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362292714258206; DSPS: 29855484; Offset: 1450361381597192777
,I/GAV2    ( 6669): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 6758): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 6758): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:517 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/CacheService( 6758): onCreate
,D/CacheService( 6758): onBind
,I/MusicLeanback( 6758): Conditions not met for autocaching.
,I/MusicLeanback( 6758): Stop autocaching.
,D/CacheService( 6758): onDestroy
,D/dalvikvm( 1970): GC_EXPLICIT freed 1612K, 21% free 19652K/24832K, paused 4ms+7ms, total 68ms
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/GAV2    ( 6806): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362300039, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362300044, nextTick: 59987, mDrawingTime: 1
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3742): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3742): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.videos
,D/administrator(  965): Handling package changes for user 0
,I/ActivityManager(  965): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6951 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/HyLog   ( 6951): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6951): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6951): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4  ( 6951):  AppBoxContentProvider onCreate
,W/AppUp4  ( 6951):  [AppBoxDatabaseHelper] construct
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/AppUp4  ( 6951):  setFingerPrint start
I/AppUp4  ( 6951):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 6951):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 6951):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6951): AppBoxApplication onCreate()
,D/AppBoxBlacklist( 6951): ConfigFile is not exist. /cust/config/appmanager.cfg
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  965):   Scheme: "mmsto"
,D/PackageParser( 6951): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/PackageParser( 6951): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
D/AppUp4:Utils( 6951): [getPackageName] uri : package:com.google.android.videos
D/AppUp4  ( 6951): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 6951): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.videos
I/AppUp4:CustModeStarterReceiver( 6951): onReceive
D/AppUp4:CustFacade( 6951): Context : android.app.ReceiverRestrictedContext@428ca068
D/AppUp4:CustFacade( 6951): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6951): isOpenOperator : true
D/AppUp4:CustFacade( 6951): isPhone : true
,I/ActivityManager(  965): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=6985 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 6985): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6985): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6985): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/LicenseContentProvider( 6985): start selecting data
,W/BaseRuntimeLoader( 6985): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6985): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6985): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6985): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 6985): simInfo1
,I/AppUp4:EulaManager( 6951): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 6951): begin check event
D/AppUp4:Utils( 6951): [getPackageName] uri : package:com.google.android.videos
,I/AppUp4:CustModeStarterReceiver( 6951): Event For Nothing, skip.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7001 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): Killing 6264:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  965): Killing 1876:com.google.android.gms.wearable/u0a6 (adj 15): empty #18
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/HyLog   ( 7001): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7001): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7001): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/SystemConfig( 7001): BUILD Country: EU
,I/SystemConfig( 7001): BUILD Operator: OPEN
I/ActivityManager(  965): Killing 6711:com.google.android.syncadapters.calendar/u0a72 (adj 15): empty #17
,I/SystemConfig( 7001): systemFeature RCS result false
,D/SystemConfig( 7001): refreshRcsSupport() :false
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/IcingCorporaProvider( 2657): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,I/ActivityManager(  965): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7017 uid=10050 gids={50050, 3003, 1028, 1015}
,D/dalvikvm( 3916): GC_FOR_ALLOC freed 391K, 2% free 37963K/38604K, paused 33ms, total 36ms
,D/HyLog   ( 7017): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7017): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7017): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2657): UpdateCorporaTask done [took 98 ms] updated apps [took 98 ms] 
,I/dalvikvm( 7017): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 7017): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7017): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 7017): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 7017): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 7017): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7017): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 7017): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7017): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7017): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7017): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 7017): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7017): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7017): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7017): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 7017): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7017): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 7017): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7017): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 7017): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7017): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7017): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7017): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 5864): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5864): created cursor android.database.sqlite.SQLiteCursor@42925400 on behalf of 7017
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 7017): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 7017): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7017): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 7017): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 7017): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 7017): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 7017): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7017): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7017): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1970): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/Finsky  ( 7017): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  965): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7058 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PeopleContactsSync( 1970): CP2 sync disabled
,D/HyLog   ( 7058): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7058): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7058): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 7058): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7058): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 7058): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7058): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7058): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 7058): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7058): install
,I/ActivityManager(  965): Killing 6669:com.google.android.gm/u0a68 (adj 15): empty #17
I/MultiDex( 7058): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 7058): loading existing secondary dex files
,I/MultiDex( 7058): load found 3 secondary dex files
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
I/MultiDex( 7058): install done
,D/dalvikvm( 7058): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 7058): VFY: unable to resolve instance field 61
,D/dalvikvm( 7058): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 7058): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7058): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7058): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 7058): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7058): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7058): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7058): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7058): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 7058): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428be680
,D/dalvikvm( 7058): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428be680
,D/dalvikvm( 7058): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428be680, skipping init
,D/dalvikvm( 7058): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428be680
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 7058): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428be680
V/JNIHelp ( 7058): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 7058): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428be680
,D/dalvikvm( 7058): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428be680
D/dalvikvm( 7058): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428be680
,D/dalvikvm( 7058): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428be680
,I/ProviderInstaller( 7058): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1544): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1544): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1544): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1970): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 1970): Restart initialization of location
,I/dalvikvm( 7058): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
,W/dalvikvm( 7058): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 7058): VFY: replacing opcode 0x6e at 0x003f
,D/WearableService( 7058): callingUid 10006, callindPid: 7058
E/dalvikvm( 7058): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 7058): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 7058): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 7058): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7058): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 7058): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7058): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7058): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 7058): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7058): VFY: replacing opcode 0x6e at 0x0201
,E/MDM     ( 1425): [80] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7017): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7017): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7017): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7017): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm(  965): GC_EXPLICIT freed 2184K, 48% free 30870K/59284K, paused 5ms+15ms, total 176ms
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7017): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1544): GC_EXPLICIT freed 965K, 28% free 18022K/24832K, paused 2ms+5ms, total 40ms
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7017): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 7017): Total arena pages for JIT: 11
,I/dalvikvm( 7017): Total arena pages for JIT: 12
I/dalvikvm( 7017): Total arena pages for JIT: 13
,I/dalvikvm( 7017): Total arena pages for JIT: 14
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7017): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7017): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7017): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7017): [1] DailyHygiene.reschedule: Scheduling new run in 96 minutes (failures=3)
,D/DeviceConnectionService( 1425): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Killing 5986:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c69548 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362312715312326; DSPS: 30510879; Offset: 1450361381597178782
,D/Finsky  ( 7017): [546] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7017): [1] 5.onFinished: Installation state replication succeeded.
,E/.AppDataSearchProvider( 6758): Couldn't find corpus 'songs'
,E/.AppDataSearchProvider( 6758): Couldn't find corpus 'albums'
,E/.AppDataSearchProvider( 6758): Couldn't find corpus 'artists'
,E/.AppDataSearchProvider( 6758): Couldn't find corpus 'playlists'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362332716871713; DSPS: 31166290; Offset: 1450361381597181772
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362352717963587; DSPS: 31821686; Offset: 1450361381597175013
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362360039, nextTick: 59968, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362360055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362372718964706; DSPS: 32477079; Offset: 1450361381597169052
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362392720019130; DSPS: 33132473; Offset: 1450361381597185879
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362412721009928; DSPS: 33787866; Offset: 1450361381597169596
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362420031, nextTick: 59993, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362420055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362432722652917; DSPS: 34443279; Offset: 1450361381597195154
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362452723667592; DSPS: 35098673; Offset: 1450361381597172231
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362472724659335; DSPS: 35754065; Offset: 1450361381597187412
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362480031, nextTick: 59995, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362480056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362492726290171; DSPS: 36409479; Offset: 1450361381597170298
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362512726799319; DSPS: 37064855; Offset: 1450361381597191165
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362532727784633; DSPS: 37720248; Offset: 1450361381597169399
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362540028, nextTick: 60002, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362540047, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362552729350670; DSPS: 38375659; Offset: 1450361381597179040
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362572729859145; DSPS: 39031035; Offset: 1450361381597199233
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362592730875988; DSPS: 39686429; Offset: 1450361381597178479
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362600039, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362600055, nextTick: 59978, mDrawingTime: 0
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x42c9c720: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1544): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1544): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1544): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1544): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1544): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1544): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 7017): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7017): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7017): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 7017): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7017): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 7017): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7017): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 7017): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 7017): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 7017): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362612734009586; DSPS: 40341892; Offset: 1450361381597168766
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362632735067224; DSPS: 40997286; Offset: 1450361381597188807
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362652736537236; DSPS: 41652695; Offset: 1450361381597163457
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362660049, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362660056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362672737037004; DSPS: 42308071; Offset: 1450361381597174944
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362692737545995; DSPS: 42963447; Offset: 1450361381597195654
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362712738553409; DSPS: 43618841; Offset: 1450361381597165470
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362720054, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362720055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362732739571331; DSPS: 44274234; Offset: 1450361381597176312
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362752740056982; DSPS: 44929610; Offset: 1450361381597173682
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362772740591239; DSPS: 45584987; Offset: 1450361381597189140
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362780044, nextTick: 59974, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362780054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362792741116559; DSPS: 46240364; Offset: 1450361381597195661
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362812741617978; DSPS: 46895741; Offset: 1450361381597178281
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,I/EventLogService( 1970): Aggregate from 1450361912575 (log), 1450360601954 (data)
,D/GCM     ( 1544): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362832742683659; DSPS: 47551136; Offset: 1450361381597175847
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362840053, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362840055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362852743220542; DSPS: 48206513; Offset: 1450361381597193931
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362872743727105; DSPS: 48861890; Offset: 1450361381597181695
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362892744759386; DSPS: 49517284; Offset: 1450361381597176379
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362900047, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362900055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362912745274279; DSPS: 50172661; Offset: 1450361381597172473
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362932745778532; DSPS: 50828037; Offset: 1450361381597188445
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362952746278720; DSPS: 51483414; Offset: 1450361381597169834
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362960044, nextTick: 59984, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450362960047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362972752334567; DSPS: 52138972; Offset: 1450361381597183200
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450362992752868944; DSPS: 52794349; Offset: 1450361381597198778
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363012753371050; DSPS: 53449726; Offset: 1450361381597182086
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363020054, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363020055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363032759325884; DSPS: 54105281; Offset: 1450361381597185992
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363052760347795; DSPS: 54760674; Offset: 1450361381597200823
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363072761349300; DSPS: 55416067; Offset: 1450361381597195248
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363080068, nextTick: 59958, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363080073, nextTick: 59959, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363092763590148; DSPS: 56071501; Offset: 1450361381597177795
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363112764807323; DSPS: 56726901; Offset: 1450361381597174267
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363132765820246; DSPS: 57382294; Offset: 1450361381597180110
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363140034, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363140043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363152767371484; DSPS: 58037705; Offset: 1450361381597174951
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363172768368759; DSPS: 58693097; Offset: 1450361381597195664
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363192769452032; DSPS: 59348493; Offset: 1450361381597180304
,I/ProcessStatsService(  965): Prepared write state in 49ms
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363200084, nextTick: 59944, mDrawingTime: 3
D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363200087, nextTick: 59946, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  965): Pruning old procstats: /data/system/procstats/state-2015-12-16-20-31-11.bin
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1544): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1544): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1544): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1544): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1544): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1544): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363212771287674; DSPS: 60003913; Offset: 1450361381597184891
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363232773347410; DSPS: 60659341; Offset: 1450361381597169432
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363252773841331; DSPS: 61314717; Offset: 1450361381597175072
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363260042, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450363260047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363272775517787; DSPS: 61970132; Offset: 1450361381597173061
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450363292776530164; DSPS: 62625525; Offset: 1450361381597178358
,TIME-OUT KILL (timeout was 1800000ms)
```
