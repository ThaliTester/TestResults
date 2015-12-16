#### Test 506502789b39735_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4669): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  949): Killing 4109:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 1 tasks}
D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2}
I/ConfigFetchService( 1949): fetch service done; releasing wakelock
I/ConfigFetchService( 1949): stopping self
D/dalvikvm( 1537): GC_EXPLICIT freed 1202K, 29% free 17822K/24832K, paused 1ms+3ms, total 22ms
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4712): 
D/AndroidRuntime( 4712): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4712): CheckJNI is OFF
D/dalvikvm( 4712): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4712): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4712): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4712): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4712): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4712): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1949): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
E/memtrack( 4712): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4712): failed to load memtrack module: -2
D/Icing   ( 1949): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1949): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4712): Calling main entry com.android.commands.am.Am
I/ActivityManager(  949): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4712
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (112 us)
V/ActivityManager(  949): Moving to PAUSING: ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  949): resumeTopActivityLocked: Pausing null
V/ActivityManager(  949): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  949): startService SlideAside
W/ContextImpl(  949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  949): setFocusedStack: mFocusedStack=ActivityStack{43381c28 stackId=1, 2 tasks}
D/AndroidRuntime( 4712): Shutting down VM
D/UsbSettingsControl( 2608): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2608): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3787): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4712): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
D/ActivityManager(  949): allPausedActivitiesComplete: r=ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  949): Moving to PAUSED: ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
D/ActivityManager(  949): resumeTopActivityLocked: Restarting ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  949): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4729 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
I/SlideAside( 3787): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
V/ActivityManager(  949): Moving to RESUMED: ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4729): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4729): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4729): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
D/SlideAside( 3787): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/WebViewChromium( 4729): Binding Chromium to the background looper Looper (main, tid 1) {428ffe38}
I/chromium( 4729): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4729): Initializing chromium process, renderers=0
W/chromium( 4729): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4729): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4729): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4729): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4729): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4729): Remote Branch: 
I/Adreno-EGL( 4729): Local Patches: 
I/Adreno-EGL( 4729): Reconstruct Branch: 
I/dalvikvm( 4729): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4729): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4729): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4729): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4729): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4729): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4729): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4729): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4729): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4729): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4729): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4729): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4729): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4729): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4729): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4729): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4729): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4729): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4729): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4729): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4729): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4729): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4729): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4729): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4729): Enabling debug mode 0
,W/AwContents( 4729): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  949): IME STATUS OFF
,W/AwContents( 4729): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  949): Displayed com.test.thalitest/.MainActivity: +387ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager( 4729): Timeline: Activity_idle id: android.os.BinderProxy@42901608 time:110423
,D/JsMessageQueue( 4729): Set native->JS mode to OnlineEventsBridgeMode
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 4729): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x429057d8
D/dalvikvm( 4729): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x429057d8
D/jxcore_app_log( 4729): JniHelper::setJavaVM(0x417e5808), pthread_self() = 1632561656
D/JX-Cordova( 4729): jxcore cordova android initializing
D/ActivityManager(  949): no-history finish of ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  949): Finishing activity token=Token{43414160 ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  949): Moving to FINISHING: ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  949): Timeline: Activity_windows_visible id: ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3} time:110803
D/UsbSettings( 2608): [AUTORUN] onStop()
V/ActivityManager(  949): Moving to STOPPING: ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  949): Moving to STOPPED: ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  949): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/dalvikvm( 4729): GC_CONCURRENT freed 2814K, 13% free 21838K/24832K, paused 7ms+1ms, total 48ms
D/dalvikvm( 4729): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/dalvikvm( 4729): GC_FOR_ALLOC freed 196K, 12% free 21853K/24832K, paused 21ms, total 21ms
D/dalvikvm( 4729): GC_FOR_ALLOC freed 191K, 12% free 21879K/24832K, paused 20ms, total 20ms
I/dalvikvm-heap( 4729): Grow heap (frag case) to 23.677MB for 144892-byte allocation
D/dalvikvm( 4729): GC_FOR_ALLOC freed 255K, 13% free 21926K/24976K, paused 20ms, total 20ms
I/dalvikvm-heap( 4729): Grow heap (frag case) to 23.792MB for 217334-byte allocation
D/dalvikvm( 4729): GC_FOR_ALLOC freed 367K, 13% free 22000K/25192K, paused 20ms, total 20ms
I/dalvikvm-heap( 4729): Grow heap (frag case) to 23.968MB for 325996-byte allocation
D/dalvikvm( 4729): GC_FOR_ALLOC freed 568K, 14% free 22122K/25512K, paused 21ms, total 21ms
I/dalvikvm-heap( 4729): Grow heap (frag case) to 24.243MB for 488990-byte allocation
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 865K, 15% free 22298K/25992K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4729): Grow heap (frag case) to 24.649MB for 733480-byte allocation
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 1285K, 16% free 22556K/26712K, paused 21ms, total 21ms
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
,D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  949): handleMessage: X
,D/dalvikvm( 4729): GC_CONCURRENT freed 1675K, 15% free 22928K/26712K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 4729): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 356K, 15% free 22898K/26712K, paused 21ms, total 21ms
I/dalvikvm-heap( 4729): Grow heap (frag case) to 26.109MB for 1650320-byte allocation
,D/dalvikvm( 4729): GC_CONCURRENT freed 1903K, 17% free 23538K/28324K, paused 2ms+5ms, total 52ms
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 1179K, 17% free 23516K/28324K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4729): Grow heap (frag case) to 27.500MB for 2475476-byte allocation
,D/dalvikvm( 4729): GC_CONCURRENT freed 267K, 16% free 25901K/30744K, paused 2ms+4ms, total 35ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 4325K, 21% free 24505K/30744K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4729): Grow heap (frag case) to 29.645MB for 3713210-byte allocation
,D/dalvikvm( 4729): GC_CONCURRENT freed 394K, 18% free 28200K/34372K, paused 2ms+14ms, total 57ms
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 3101K, 26% free 25453K/34372K, paused 22ms, total 22ms
,W/jxcore-log( 4729): Initializing JXcore engine
,W/jxcore-log( 4729): JXcore engine is ready
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.432327 Y: -0.400940 Z: 9.741089 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.432327 .y:-0.400940 .z:9.741089
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,D/dalvikvm( 4729): GC_CONCURRENT freed 311K, 19% free 28111K/34372K, paused 1ms+1ms, total 24ms
,D/dalvikvm( 4729): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 4729): Starting JXcore engine
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.457611 Y: -0.389389 Z: 9.764938 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457611 .y:-0.389389 .z:9.764938
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,W/jxcore-log( 4729): Platform android
W/jxcore-log( 4729): 
,W/jxcore-log( 4729): Process ARCH arm
W/jxcore-log( 4729): 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/jxcore-log( 4729): JXcore Cordova bridge is ready!
I/jxcore-log( 4729): 
,W/jxcore-log( 4729): JXcore engine is started
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/chromium( 4729): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4729): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4729): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/jxcore-log( 4729): Toggling radios to true
I/jxcore-log( 4729): 
D/BluetoothManagerService(  949): Message: 20
D/BluetoothManagerService(  949): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4339d3d8:true
D/BluetoothAdapter( 4729): enable(): BT is already enabled..!
D/WifiService(  949): New client listening to asynchronous messages
D/WifiStateMachine(  949): handleMessage: E msg.what=131145
D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiNative-wlan0(  949): doBoolean: DISCONNECT
I/jxcore-log( 4729): Radios toggled
I/jxcore-log( 4729): 
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2035): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2035): wlan0: Cancelling scan request
D/wpa_supplicant( 2035): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2035): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2035): TDLS: Tear down peers
D/wpa_supplicant( 2035): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothManagerService(  949): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  949): setWifiEnabled: true pid=4729, uid=10304
E/WifiService(  949): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  949): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  949): disconnect pid=4729, uid=10304
D/WifiService(  949): reconnect pid=4729, uid=10304
I/jxcore-log( 4729): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4729): 
I/jxcore-log( 4729): Perf Test app loaded loaded
I/jxcore-log( 4729): 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2035): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2035): wlan0: Deauthentication notification
D/wpa_supplicant( 2035): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2035): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2035): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2035): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2035): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2035): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb712bd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2035): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2035): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2035): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2035): nl80211: Event message available
D/wpa_supplicant( 2035): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2035): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiNative-wlan0(  949):    returned true
D/WifiStateMachine(  949): transitionTo: destState=DisconnectingState
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  949): handleMessage: new destination call exit/enter
D/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  949): invokeExitMethods: ConnectedState
W/Settings(  949): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  949): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  949): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=131146
D/WifiStateMachine(  949): processMsg: DisconnectingState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiNative-wlan0(  949): doBoolean: RECONNECT
I/Choreographer( 4729): Skipped 59 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2035): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2035): Fast associate: Old scan results
D/wpa_supplicant( 2035): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2035): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2035): wlan0: nl80211: scan request
D/wpa_supplicant( 2035): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiNative-wlan0(  949):    returned true
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=147460
D/WifiStateMachine(  949): processMsg: DisconnectingState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): Network connection lost
D/wpa_supplicant( 2035): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2035): nl80211: Event message available
D/wpa_supplicant( 2035): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2035): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  949): Stopping DHCP and clearing IP
D/WifiStateMachine(  949): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  949): doBoolean: SET ps 1
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2035): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2035): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2035): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  949):    returned true
D/WifiNative-wlan0(  949): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  949): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  949): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  949):    returned true
D/DhcpStateMachine(  949): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4729): check test folder
I/jxcore-log( 4729): 
I/GAV2    ( 4669): Thread[GAThread,5,main]: No campaign data found.
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  949): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
I/jxcore-log( 4729): found test : ./testFindPeers.js
I/jxcore-log( 4729): 
D/WifiStateMachine(  949): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  949): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
D/WifiHS20(  949): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  949): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
D/QCNEA   (  604): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  604): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  604): |CAC| updateNetCfgInfo
V/QCNEA   (  604): |CAC| *********************************************
V/QCNEA   (  604): |CAC|                   Netconfig               
V/QCNEA   (  604): |CAC| *********************************************
V/QCNEA   (  604): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  604): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  604): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  604): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  604): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  604): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  604): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  604): |CAC| *********************************************
D/QCNEA   (  604): |CAC| Received bssid= 
D/QCNEA   (  604): |CAC| net type = 3
V/QCNEA   (  604): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  604): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  604): |CAC| 	ssid           =NG700
V/QCNEA   (  604): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  604): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  604): |CAC| *********************************************
D/QCNEA   (  604): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  604): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  604): |CAC| dispatchNetCfg: updating:0xb79938dc
D/QCNEA   (  604): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  949): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/ActivityManager(  949): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4785 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  949): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  949): handleMessage: new destination call exit/enter
D/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  949): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  949): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=147462
D/WifiStateMachine(  949): processMsg: DisconnectedState
,D/WifiStateMachine(  949): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/NetworkManagementService(  949): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=147462
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiStateMachine(  949): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine(  949): processMsg: ConnectModeState
D/QcConnectivityService(  949): Attempting to switch to mobile
D/QcConnectivityService(  949): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  949): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=131213
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): processMsg: DriverStartedState
D/WifiStateMachine(  949): processMsg: DriverStartedStateExt
D/WifiStateMachine(  949): processMsg: SupplicantStartedState
D/WifiStateMachine(  949): processMsg: DefaultState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=131213
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/NetworkManagementService(  949): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  949): processMsg: DriverStartedState
D/WifiStateMachine(  949): processMsg: DriverStartedStateExt
D/WifiStateMachine(  949): processMsg: SupplicantStartedState
D/WifiStateMachine(  949): processMsg: DefaultState
D/WifiStateMachine(  949): handleMessage: X
D/NetworkManagementService(  949): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
I/jxcore-log( 4729): found test : ./testSendData.js
I/jxcore-log( 4729): 
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 4785): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4785): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4785): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
W/NetworkManagementService(  949): route cmd failed: 
W/NetworkManagementService(  949): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  949): '
W/NetworkManagementService(  949): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  949): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  949): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  949): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  949): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  949): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  949): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  949): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  949): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  949): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  949): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  949): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  949): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  949): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  949): android_net_utils_resetConnections in env=0x62070e20 clazz=0x6c600001 iface=wlan0 mask=0x3
D/QcConnectivityService(  949): resetConnections(wlan0, 3)
,V/NativeCrypto( 1537): Read error: ssl=0x63e05d90: I/O error during system call, Connection timed out
,I/PCSuite ( 4785): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/NativeCrypto( 1537): SSL shutdown failed: ssl=0x63e05d90: I/O error during system call, Broken pipe
,D/PCSuite ( 4785): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4785): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  949): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4821 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  949): Killing 4191:com.google.android.talk/u0a77 (adj 15): empty #17
,D/Nat464Xlat(  949): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GpsLocationProvider(  949): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  949): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  949): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
I/TelephonyProvider( 1465): getPreferredApnId: subscription=0
I/chromium( 4729): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/LocSvc_java(  949): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  949): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1465): getPreferredApnId: subscription=0
D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4821): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4821): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4821): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4821): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4821): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4821): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4821): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4821): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4821): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4821): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  949): Killing 3127:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  949): StoppedState
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
D/WifiStateMachine(  949): processMsg: DisconnectedState
,D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): processMsg: DriverStartedState
D/WifiStateMachine(  949): processMsg: DriverStartedStateExt
D/WifiStateMachine(  949): processMsg: SupplicantStartedState
D/WifiStateMachine(  949): processMsg: DefaultState
,D/WifiStateMachine(  949): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1537): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  949): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  949): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  949): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4075): onReceive
,D/AppUp4:CustFacade( 4075): Context : android.app.ReceiverRestrictedContext@42913ea0
,D/AppUp4:CustFacade( 4075): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4075): isOpenOperator : true
,D/AppUp4:CustFacade( 4075): isPhone : true
,I/LicenseContentProvider( 2973): start selecting data
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4075): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4075): begin check event
,I/AppUp4:CustModeStarterReceiver( 4075): Event For GoodConnectivity
,D/wpa_supplicant( 2035): nl80211: Event message available
D/wpa_supplicant( 2035): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2035): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2035): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2035): nl80211: Received scan results (11 BSSes)
D/wpa_supplicant( 2035): nl80211: Survey data missing
D/wpa_supplicant( 2035): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2035): wlan0: BSS: Add new id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Add new id 7 BSSID fc:6f:b7:3e:78:0a SSID 'UPC249917252'
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Add new id 8 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Add new id 9 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Add new id 10 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): BSS: last_scan_res_used=11/32 last_scan_full=0
D/wpa_supplicant( 2035): wlan0: New scan results available
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2035): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2035): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2035): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2035): WPS: AP fc:6f:b7:3e:78:0a type 0 added
D/wpa_supplicant( 2035): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2035): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2035): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[3] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[4] fc:6f:b7:3e:78:0a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[5] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[6] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2035): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-47 wps
D/wpa_supplicant( 2035): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2035): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59
D/wpa_supplicant( 2035): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2035): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2035): wlan0:    selected based on RSN IE
D/wpa_supplicant( 20,35): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2035): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb712d5a8  current_ssid=0x0
D/wpa_supplicant( 2035): scard is not null..
D/wpa_supplicant( 2035): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2035): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2035): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2035): wlan0: Cancelling scan request
D/wpa_supplicant( 2035): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2035): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2035): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2035): RSN: PMKSA cache search - network_ctx=0xb712d5a8 try_opportunistic=0
D/wpa_supplicant( 2035): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2035): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2035): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2035): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2035): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2035): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2035): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2035): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2035): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2035): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2035): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2035): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2035): nl80211: Unsubscribe mgmt frames handle 0xb712c590 (mode change)
D/wpa_supplicant( 2035): nl80211: Subscribe to mgmt frames with non-AP handle 0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb712c590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2035): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2035):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035):   * freq=2412
D/wpa_supplicant( 2035):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2035):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035):   * Auth Type 0
D/wpa_supplicant( 2035):   * WPA Versions 0x2
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 fc:6f:b7:3e:78:0a]
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 64:7c:34:12:7f:81]
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 fe:94:e3:11:35:3c]
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 a0:c5:62:7a:49:96]
D/wpa_supplicant( 2035): nl80211: Connect request send successfully
D/wpa_supplicant( 2035): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2035): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  949): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  949): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  949): handleMessage: E msg.what=147461
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): processMsg: DriverStartedState
D/WifiStateMachine(  949): processMsg: DriverStartedStateExt
D/WifiStateMachine(  949): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  949): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2035): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2035): nl80211: Event message available
D/wpa_supplicant( 2035): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2035): nl80211: Connect event
D/wpa_supplicant( 2035): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2035): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2035): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2035): wlan0: Association info event
D/wpa_supplicant( 2035): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2035): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2035): wlan0: freq=2412 MHz
D/wpa_supplicant( 2035): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2035): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2035): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2035): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): scard is not null..
D/wpa_supplicant( 2035): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2035): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2035): TDLS: Remove peers on association
D/wpa_supplicant( 2035): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2035): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2035): EAPOL: enable timer tick
D/wpa_supplicant( 2035): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2035): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2035): wlan0: Cancelling scan request
D/wpa_supplicant( 2035): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=147462
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiMonitor(  949): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  949): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  949): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=147462
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiStateMachine(  949): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): handleMessage: X
I/ActivityManager(  949): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4854 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2035): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e3 65 ab 0f 85 1a ab 9a e9 ba 3a 7c c7 eb 42 ...
D/wpa_supplicant( 2035): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2035): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2035): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2035): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2035): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2035):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2035):   key_nonce - hexdump(len=32): e3 65 ab 0f 85 1a ab 9a e9 ba 3a 7c c7 eb 42 66 84 77 f9 46 7c f6 5f ff b1 63 44 ef b8 b3 e5 6a
D/wpa_supplicant( 2035):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 e3 65 ab 0f 85 1a ab 9a e9 ba 3a 7c c7 eb 42 ...
D/wpa_supplicant( 2035): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2035): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2035): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2035): WPA: Renewed SNonce - hexdump(len=32): 5e d4 4a cb b2 c5 47 dd 53 9d d4 07 38 77 2b 57 b4 54 8b 33 cd 4f 1e 86 c3 47 64 6d 06 8b e8 a1
D/wpa_supplicant( 2035): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): WPA: Nonce1 - hexdump(len=32): 5e d4 4a cb b2 c5 47 dd 53 9d d4 07 38 77 2b 57 b4 54 8b 33 cd 4f 1e 86 c3 47 64 6d 06 8b e8 a1
D/wpa_supplicant( 2035): WPA: Nonce2 - hexdump(len=32): e3 65 ab 0f 85 1a ab 9a e9 ba 3a 7c c7 eb 42 66 84 77 f9 46 7c f6 5f ff b1 63 44 ef b8 b3 e5 6a
D/wpa_supplicant( 2035): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2035): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2035): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2035): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2035): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2035): WPA: Derived Key MIC - hexdump(len=16): fc 3d 0c 65 2c 2d d4 41 28 d6 11 bc 74 81 fb 70
D/wpa_supplicant( 2035): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 5e d4 4a cb b2 c5 47 dd 53 9d d4 07 38 77 2b ...
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  949): handleMessage: E msg.what=147462
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiStateMachine(  949): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  949): processMsg: ConnectModeState
,D/WifiStateMachine(  949): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/HyLog   ( 4854): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4854): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4854): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2035): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e3 65 ab 0f 85 1a ab 9a e9 ba 3a 7c c7 eb 42 ...
D/wpa_supplicant( 2035): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2035): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2035): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2035): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2035):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2035):   key_nonce - hexdump(len=32): e3 65 ab 0f 85 1a ab 9a e9 ba 3a 7c c7 eb 42 66 84 77 f9 46 7c f6 5f ff b1 63 44 ef b8 b3 e5 6a
D/wpa_supplicant( 2035):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_rsc - hexdump(len=8): 57 76 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_mic - hexdump(len=16): f7 2d 64 7a a9 90 76 b0 d5 dc 2b 37 48 3b 05 95
D/wpa_supplicant( 2035): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 e3 65 ab 0f 85 1a ab 9a e9 ba 3a 7c c7 eb 42 ...
D/wpa_supplicant( 2035): RSN: encrypted key data - hexdump(len=56): 9e d0 cc c2 1d 28 9c 5f ab 8d 01 ec 08 64 ba 06 ea fc 96 7d 64 0b a6 ec 95 a7 6a 51 e4 ab bd 97 ...
D/wpa_supplicant( 2035): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2035): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2035): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2035): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 e6 70 ...
D/wpa_supplicant( 2035): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2035): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2035): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2035): WPA: Derived Key MIC - hexdump(len=16): 3a df 45 19 89 d2 75 e6 2b 8f 8b 35 43 c4 f6 c1
D/wpa_supplicant( 2035): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2035): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb712cc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2035):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2035): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2035): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2035): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2035): WPA: RSC - hexdump(len=6): 57 76 00 00 00 00
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ed703a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2035):    broadcast key
D/WifiStateMachine(  949): handleMessage: E msg.what=147462
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiStateMachine(  949): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): handleMessage: X
I/wpa_supplicant( 2035): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: Cancelling authentication timeout
D/WifiMonitor(  949): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 2035): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2035): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  949): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  949): handleMessage: E msg.what=147459
D/WifiStateMachine(  949): processMsg: DisconnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): Network connection established
D/wpa_supplicant( 2035): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/WifiNative-wlan0(  949): doString: STATUS
D/wpa_supplicant( 2035): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2035): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2035): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2035): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2035): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2035): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2035): EAPOL authentication completed successfully
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2035): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  949):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  949): ssid=NG700
D/WifiNative-wlan0(  949): id=0
D/WifiNative-wlan0(  949): mode=station
D/WifiNative-wlan0(  949): pairwise_cipher=CCMP
D/WifiNative-wlan0(  949): group_cipher=CCMP
D/WifiNative-wlan0(  949): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  949): wpa_state=COMPLETED
D/WifiNative-wlan0(  949): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  949): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  949): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  949): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  949): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  949): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  949): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  949): handleMessage: new destination call exit/enter
D/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  949): invokeExitMethods: DisconnectedState
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  949): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  949): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  949): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  949): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  949): WaitBeforeStartState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=147462
D/WifiStateMachine(  949): processMsg: ObtainingIpState
D/WifiStateMachine(  949): ObtainingIpState{ when=-12ms what=147462 obj=android.net.wifi.StateChangeResult@43df1168 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=147462
D/WifiStateMachine(  949): processMsg: ObtainingIpState
D/WifiStateMachine(  949): ObtainingIpState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@43e0f140 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=147459
D/WifiStateMachine(  949): processMsg: ObtainingIpState
D/WifiStateMachine(  949): ObtainingIpState{ when=-9ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=131155
D/WifiStateMachine(  949): processMsg: ObtainingIpState
D/WifiStateMachine(  949): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2035): nl80211: survey data missing!
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=196612
D/WifiStateMachine(  949): processMsg: ObtainingIpState
D/WifiStateMachine(  949): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiNative-wlan0(  949): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/WifiController(  949): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  949): battery changed pluggedType: 2
V/DownloadManager( 4854): DownloadService onCreate
D/EAS     ( 4652): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4652): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4854): in removeSpuriousFiles
,D/eas_req ( 4652): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4854): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@4293a178 on behalf of 4854
,I/DownloadManager( 4854): in trimDatabase
,V/DownloadManager( 4854): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@4293cfe8 on behalf of 4854
,V/DownloadManager( 4854): DownloadService onStartCommand
,V/DownloadManager( 4854): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@4293f4d8 on behalf of 4854
I/LgeMiscReceiver( 4377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4377): networkInfo.isConnected() = false
,V/DownloadManager( 4854): DownloadService onDestroy
,W/linker  ( 4652): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4652): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4652): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4652): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4652): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4652): register_HtmlEditor, Success
D/HtmlEditor( 4652): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4652): register_HtmlEditorTimer, Success
,D/HtmlEditor( 4652): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4652): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4652): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4652): register_HtmlEditorFont, Success
D/HtmlEditor( 4652): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4652): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4652): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4652): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4652): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4652): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4652): JNI_OnLoad Success
I/HubEmail( 4652): JNI_OnLoad()
,I/HubEmail( 4652): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4652): registerNatives()
I/HubEmail( 4652): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4652): registerNativeMethods()
,I/HubEmail( 4652): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4652): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  949):    returned true
D/WifiStateMachine(  949): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  949): doBoolean: SET ps 0
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2035): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2035): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2035): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  949):    returned true
,D/WifiNative-wlan0(  949): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  949):    returned null
E/WifiStateMachine(  949): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  949): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  949):    returned null
E/WifiStateMachine(  949): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  949): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  949): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  949): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  949): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/ActivityManager(  949): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4892 uid=10052 gids={50052, 3003}
D/WifiP2pService(  949): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433950a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  949): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433950a0 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up wlan0
D/WifiStateMachine(  949): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  949): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=131212
D/WifiStateMachine(  949): processMsg: ObtainingIpState
D/WifiStateMachine(  949): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): processMsg: DriverStartedState
D/WifiStateMachine(  949): processMsg: DriverStartedStateExt
D/WifiStateMachine(  949): processMsg: SupplicantStartedState
D/WifiStateMachine(  949): processMsg: DefaultState
D/WifiStateMachine(  949): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=196613
D/WifiStateMachine(  949): processMsg: ObtainingIpState
D/WifiStateMachine(  949): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  949): doBoolean: SET ps 1
,I/ActivityManager(  949): Killing 3947:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2035): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2035): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2035): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/HyLog   ( 4892): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4892): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4892): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiNative-wlan0(  949):    returned true
,D/WifiNative-wlan0(  949): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  949):    returned true
,D/WifiStateMachine(  949): DHCP successful
D/WifiStateMachine(  949): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  949): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  949): handleMessage: new destination call exit/enter
D/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  949): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  949): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  949): VerifyingLinkState enter
,D/WifiStateMachine(  949): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  949): handleMessage: X
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  949): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
D/WifiStateMachine(  949): handleMessage: E msg.what=135190
D/WifiP2pService(  949): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  949): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  949): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  949): 
W/WifiStateTracker(  949):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  949):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  949): processMsg: VerifyingLinkState
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  949): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  949): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  949): handleMessage: new destination call exit/enter
D/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  949): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  949): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  949): CaptivePortalCheckState enter
D/WifiStateMachine(  949): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  949): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  949): handleMessage: X
,D/GpsLocationProvider(  949): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1465): getPreferredApnId: subscription=0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1465): getPreferredApnId: subscription=0
D/Nat464Xlat(  949): requiresClat: netType=1, hasIPv4Address=true
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  949): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  949): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  949): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  949): handleMessage: E msg.what=131092
D/WifiStateMachine(  949): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  949): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Parcel  (  604): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  949): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  949): transitionTo: destState=ConnectedState
D/WifiStateMachine(  949): handleMessage: new destination call exit/enter
D/WifiStateMachine(  949): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  949): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  949): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  949): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  949): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  949): handleMessage: X
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  949): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/QcConnectivityService(  949): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  949): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  949): handleInetConditionChange: no active default network - ignore
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  604): Reading a NULL string not supported here.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  949): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  949): [getValue] FEATURE key : vzw_roaming_state, value : null
E/ActivityThread(  949): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  949): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  949): handleConnectivityChange: preConnState=2 connState=1
,V/LGRssiData( 4892): [loadRssi] File not exist 
V/LGRssiData( 4892): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4892): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 4892): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/BaseRuntimeLoader( 4892): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 4892): onReceive CONNECTIVITY_CHANGE networkType=1
W/BaseRuntimeLoader( 4892): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4892): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4892): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4892): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4892): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4892): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
I/ActivityManager(  949): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4910 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  949): Killing 4358:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
V/        (  264): RouteController
V/        (  264): RouteController
,E/PhoneMonitor( 4892): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4892): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4910): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
V/        (  264): RouteController
I/CheckinService( 1949): Checking schedule, now: 1450229683935 next: 1450229627605
I/CheckinService( 1949): active receiver: enabled
V/        (  264): RouteController
,D/Nat464Xlat(  949): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  604): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  604): |CAC| updateWlanNetCfgInfo
,D/QCNEA   (  604): |CAC| updateNetCfgInfo
V/QCNEA   (  604): |CAC| *********************************************
V/QCNEA   (  604): |CAC|                   Netconfig               
V/QCNEA   (  604): |CAC| *********************************************
V/QCNEA   (  604): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  604): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  604): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  604): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  604): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  604): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  604): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  604): |CAC| *********************************************
D/QCNEA   (  604): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  604): |CAC| net type = 1
V/QCNEA   (  604): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  604): |CAC| Received ssid= NG700
V/QCNEA   (  604): |CAC| 	ssid           =NG700
V/QCNEA   (  604): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  604): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  604): |CAC| *********************************************
D/QCNEA   (  604): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  604): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  604): |CAC| dispatchNetCfg: updating:0xb79938dc
,D/QCNEA   (  604): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  949): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  949): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1465): getPreferredApnId: subscription=0
I/CheckinService( 1949): Preparing to send checkin request
,I/EventLogService( 1949): Accumulating logs since 1450229655086
I/TelephonyProvider( 1465): getPreferredApnId: subscription=0
D/LocSvc_java(  949): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  949): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinRequestBuilder( 1949): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  949): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4939 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  949): Killing 4578:com.android.defcontainer/u0a4 (adj 15): empty #17
E/ActivityThread( 1949): Failed to find provider info for com.google.android.wearable.settings
,D/DhcpStateMachine(  949): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  949): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  949): GC_EXPLICIT freed 23248K, 49% free 29656K/57628K, paused 2ms+7ms, total 123ms
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4939): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  949): Killing 4610:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2867): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2867): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2867): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  949): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4960 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/LGDMClient( 2867): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2867): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2867): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2867): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4960): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4960): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4960): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4960): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  949): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4974 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  949): Killing 4637:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,D/HyLog   ( 4974): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4974): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4974): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4974): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4974): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4974): intf.getDisplayName() = lo
I/Wireless_Storage( 4974): intf.getDisplayName() = sit0
,I/Wireless_Storage( 4974): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4974): intf.getDisplayName() = teql0
I/Wireless_Storage( 4974): intf.getDisplayName() = wlan0
D/NFS     ( 4974): interface name:wlan0 name:wlan0
D/NFS     ( 4974): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4974): interface name:wlan0 name:wlan0
D/NFS     ( 4974): addr:192.168.1.140 broadcast:192.168.1.255
,I/Wireless_Storage( 4974): CONNECT : WIFI_CONNECT
,I/ActivityManager(  949): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4986 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  949): Killing 4240:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4986): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1537): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  949): updateLightListLocked :r=NotificationRecord(0x42e39b30: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1949): awaiting user notification for token
D/NotificationService(  949): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GAV2    ( 4986): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  949): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5003 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5003): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5003): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5003): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5003): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5003): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5003): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5003): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5003): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5003): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5003): install
,I/MultiDex( 5003): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5003): loading existing secondary dex files
,I/MultiDex( 5003): load found 3 secondary dex files
,I/MultiDex( 5003): install done
,D/dalvikvm( 5003): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5003): VFY: unable to resolve instance field 61
,D/dalvikvm( 5003): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5003): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5003): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5003): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5003): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5003): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5003): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5003): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5003): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5003): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429056b0
D/dalvikvm( 5003): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429056b0
,D/dalvikvm( 5003): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429056b0, skipping init
,D/dalvikvm( 5003): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429056b0
D/dalvikvm( 5003): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429056b0
,V/JNIHelp ( 5003): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 4986): Binding Chromium to the main looper Looper (main, tid 1) {428fe4f8}
,I/chromium( 4986): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4986): Initializing chromium process, renderers=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,W/chromium( 4986): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4986): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4986): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4986): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4986): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4986): Remote Branch: 
I/Adreno-EGL( 4986): Local Patches: 
I/Adreno-EGL( 4986): Reconstruct Branch: 
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  949): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 5003): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429056b0
D/dalvikvm( 5003): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x429056b0
,D/dalvikvm( 5003): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429056b0
,D/dalvikvm( 5003): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x429056b0
,I/NSApplication( 4986): Starting up...
,I/ActivityManager(  949): Killing 4255:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4821): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4821): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4821): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4821): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/ProviderInstaller( 5003): Installed default security provider GmsCore_OpenSSL
,D/QRemote ( 4821): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4821): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4785): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4785): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4821): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 4821): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4821): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4821): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1537): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1537): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1537): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1949): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1874): callingUid 10006, callindPid: 1874
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/MDM     ( 1427): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 5003): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5003): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5003): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5003): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
D/LocationInitializer( 1949): Restart initialization of location
W/dalvikvm( 5003): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5003): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fa2000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fa2000
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
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=1864642241
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5003): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42af2a20
,D/dalvikvm( 5003): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42af2a20
,D/dalvikvm( 5003): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42af2a20, skipping init
,D/wpa_supplicant( 2035): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2035): EAPOL: disable timer tick
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5003): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5049): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 5003): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5003): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 1ms, rewrite 79ms
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  949): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Adreno-EGL( 5003): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5003): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5003): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5003): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5003): Remote Branch: 
I/Adreno-EGL( 5003): Local Patches: 
I/Adreno-EGL( 5003): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 5003): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5003): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5003): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5003): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5003): Remote Branch: 
I/Adreno-EGL( 5003): Local Patches: 
I/Adreno-EGL( 5003): Reconstruct Branch: 
,D/DhcpStateMachine(  949): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  949): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  949): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  949): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
,V/LgDhcpStateMachineHelper(  949): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  949): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  949): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  949): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  949): RunningState
,I/Adreno-EGL( 5003): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5003): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5003): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5003): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5003): Remote Branch: 
I/Adreno-EGL( 5003): Local Patches: 
I/Adreno-EGL( 5003): Reconstruct Branch: 
,W/Settings( 5003): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4729): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4729): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  949): battery changed pluggedType: 2
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/WifiStateMachine(  949): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  949): handleMessage: E msg.what=131212
D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): processMsg: DriverStartedState
D/WifiStateMachine(  949): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  949): processMsg: SupplicantStartedState
,D/WifiStateMachine(  949): processMsg: DefaultState
,D/WifiStateMachine(  949): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  949): handleMessage: X
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  949): send additional Connectivity Action
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  949): handleConnectivityChange:1 is conntected
D/LocSvc_java(  949): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1465): getPreferredApnId: subscription=0
D/LocSvc_java(  949): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  949): ignore wifi update if we are not in OPENING or CLOSING
D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
D/GpsLocationProvider(  949): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1465): getPreferredApnId: subscription=0
,D/QcConnectivityService(  949): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  949):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  949): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  949): requiresClat: netType=1, hasIPv4Address=true
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=2434708809
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1949): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1949): GC_CONCURRENT freed 1572K, 22% free 19577K/24832K, paused 4ms+6ms, total 66ms
,I/CheckinTask( 1949): Sending checkin request (11625 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1949): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1949): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1537): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1949): awaiting user notification for token
D/NotificationService(  949): updateLightListLocked :r=NotificationRecord(0x43d99868: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  949): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1949): Classify the device as Phone.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinTask( 1949): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/CheckinService( 1949): Checking schedule, now: 1450229686452 next: 1450807082445
,I/CheckinService( 1949): active receiver: disabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/WifiController(  949): battery changed pluggedType: 2
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  949): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1537): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  949): handleMessage: X
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  949): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  949): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4075): onReceive
,D/AppUp4:CustFacade( 4075): Context : android.app.ReceiverRestrictedContext@42913ea0
,D/AppUp4:CustFacade( 4075): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4075): isOpenOperator : true
,D/AppUp4:CustFacade( 4075): isPhone : true
,I/LicenseContentProvider( 2973): start selecting data
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4075): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4075): begin check event
,I/AppUp4:CustModeStarterReceiver( 4075): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4075): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4075): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4075): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4075): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4075): handleAsyncCustNotification do not startCustService
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  949): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  949): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EAS     ( 4652): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4652): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4652): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4854): DownloadService onCreate
I/DownloadManager( 4854): in removeSpuriousFiles
V/DownloadManager( 4854): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@429453a0 on behalf of 4854
I/DownloadManager( 4854): in trimDatabase
V/DownloadManager( 4854): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4377): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 4892): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4652): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4892): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@42946490 on behalf of 4854
V/DownloadManager( 4854): DownloadService onStartCommand
V/DownloadManager( 4854): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2867): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@42948f08 on behalf of 4854
D/LGDMClient( 2867): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4960): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2867): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 4854): DownloadService onDestroy
,W/ContextImpl( 4960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4974): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4974): CONNECT : WIFI_CONNECT
E/LGDMClient( 2867): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2867): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2867): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2867): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/GCM     ( 1537): Connected
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/GCM     ( 1537): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4075): onReceive
D/AppUp4:CustFacade( 4075): Context : android.app.ReceiverRestrictedContext@42913ea0
D/AppUp4:CustFacade( 4075): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4075): isOpenOperator : true
,D/AppUp4:CustFacade( 4075): isPhone : true
,I/LicenseContentProvider( 2973): start selecting data
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4075): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4075): begin check event
,I/AppUp4:CustModeStarterReceiver( 4075): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4854): DownloadService onCreate
,I/DownloadManager( 4854): in removeSpuriousFiles
,V/DownloadManager( 4854): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4652): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4652): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@4294d728 on behalf of 4854
,I/DownloadManager( 4854): in trimDatabase
V/DownloadManager( 4854): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4854): DownloadService onStartCommand
,V/DownloadManager( 4854): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@4294f000 on behalf of 4854
I/LgeMiscReceiver( 4377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4377): networkInfo.isConnected() = true
,D/PhoneState( 4377): setPdpRejectCasuse : false
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@42950d18 on behalf of 4854
,D/MobileConnectivityChangeReceiver( 4892): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4652): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4892): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2867): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4854): DownloadService onDestroy
,D/LGDMSGCM( 4960): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2867): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2867): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4974): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4974): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2867): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2867): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2867): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2867): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  949): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  283): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  949): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  949): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4075): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4075): onReceive
,D/AppUp4:CustFacade( 4075): Context : android.app.ReceiverRestrictedContext@42913ea0
D/AppUp4:CustFacade( 4075): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4075): isOpenOperator : true
,D/AppUp4:CustFacade( 4075): isPhone : true
,I/LicenseContentProvider( 2973): start selecting data
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4075): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4075): begin check event
,I/AppUp4:CustModeStarterReceiver( 4075): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  949): GC_EXPLICIT freed 2121K, 49% free 29578K/57628K, paused 5ms+11ms, total 167ms
,V/DownloadManager( 4854): DownloadService onCreate
,D/EAS     ( 4652): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4652): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4854): in removeSpuriousFiles
,V/DownloadManager( 4854): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@42955d10 on behalf of 4854
,V/DownloadManager( 4854): DownloadService onStartCommand
V/DownloadManager( 4854): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4854): in trimDatabase
,V/DownloadManager( 4854): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4377): networkInfo.isConnected() = true
D/PhoneState( 4377): setPdpRejectCasuse : false
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@429584d0 on behalf of 4854
W/Settings( 4652): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4854): created cursor android.database.sqlite.SQLiteCursor@429586e8 on behalf of 4854
D/MobileConnectivityChangeReceiver( 4892): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4892): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4854): DownloadService onDestroy
,D/LGDMClient( 2867): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2867): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4960): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/ContextImpl( 4960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2867): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4974): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4974): CONNECT : WIFI_CONNECT
E/LGDMClient( 2867): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2867): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/LGDMClient( 2867): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/LGDMClient( 2867): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/WifiController(  949): battery changed pluggedType: 2
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  949): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/WifiController(  949): battery changed pluggedType: 2
,I/WifiServiceExtension(  949): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  949): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  949): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  949): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV2    ( 4986): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  949): battery changed pluggedType: 2
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/WifiController(  949): battery changed pluggedType: 2
D/HeadsetStateMachine( 1217): Disconnected process message: 10
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
,D/WifiStateMachine(  949): processMsg: ConnectedState
,D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  949): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/Finsky  ( 4272): [399] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4272): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  949): Killing 4669:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.443497 Y: -0.382904 Z: 9.771606 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443497 .y:-0.382904 .z:9.771606
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.480148 Y: -0.401367 Z: 9.789093 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.480148 .y:-0.401367 .z:9.789093
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
,D/WifiStateMachine(  949): processMsg: ConnectedState
,D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  949): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PackageManager(  949):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  949):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  949):   Scheme: "sms"
I/PackageManager(  949): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  949):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  949):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  949):   Scheme: "smsto"
I/PackageManager(  949): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  949): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5211 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/InputReader(  949): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+11ms, total 63ms
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1504): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1504): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
E/SlideAside( 3787): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1504): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3787): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 44ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/administrator(  949): Handling package changes for user 0
,I/PackageManager(  949):   Action: "android.intent.action.SENDTO"
I/PackageManager(  949):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  949):   Scheme: "mms"
I/PackageManager(  949): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 3ms+1ms, total 16ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 5211): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5211): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5211): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  949):   Action: "android.intent.action.SENDTO"
I/PackageManager(  949):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  949):   Scheme: "mmsto"
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/PackageManager(  949): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]Launcher( 1504): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  949): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  949):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  949):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  949):   Scheme: "sms"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  949):   Action: "android.intent.action.SENDTO"
I/PackageManager(  949):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  949):   Scheme: "smsto"
I/PackageManager(  949): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  949):   Action: "android.intent.action.SENDTO"
I/PackageManager(  949):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  949):   Scheme: "mms"
I/PackageManager(  949): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  949):   Action: "android.intent.action.SENDTO"
I/PackageManager(  949):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  949):   Scheme: "mmsto"
I/PackageManager(  949): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  949): battery changed pluggedType: 2
,I/Babel   ( 5211): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5211): MmsConfig.loadMmsSettings
,I/Babel   ( 5211): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5211): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5211): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5211): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5211): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5211): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5211): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5211): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5211): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5211): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5211): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5211): MmsConfig.loadFromResources
,E/Babel   ( 5211): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5211): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5211): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1504): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1427): DISABLE
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/TelephonyAutoProfiling(  949): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  949): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5211): [loadRssi] File not exist 
V/LGRssiData( 5211): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5211): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5211): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5211): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5211): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 4075): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4075): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4075): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4075): onReceive
D/AppUp4:CustFacade( 4075): Context : android.app.ReceiverRestrictedContext@42913ea0
D/AppUp4:CustFacade( 4075): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4075): isOpenOperator : true
,D/AppUp4:CustFacade( 4075): isPhone : true
I/LicenseContentProvider( 2973): start selecting data
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4075): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4075): begin check event
,D/AppUp4:Utils( 4075): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4075): Event For Nothing, skip.
,D/LocationProviderProxy(  949): applying state to connected service
,D/LocationProviderProxy(  949): applying state to connected service
I/ActivityManager(  949): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5260 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5260): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  949): Killing 4785:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
,I/SystemConfig( 5260): BUILD Country: EU
,I/SystemConfig( 5260): BUILD Operator: OPEN
D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  949): Killing 4821:com.lge.qremote/u0a96 (adj 15): empty #17
,I/SystemConfig( 5260): systemFeature RCS result false
,D/SystemConfig( 5260): refreshRcsSupport() :false
I/ActivityManager(  949): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5275 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5275): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5275): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5275): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  949): Killing 4854:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2680): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 2 tasks}
D/ActivityManager(  949): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1949): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  949): Delaying start of: ServiceRecord{448d1520 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageBroadcastService( 1949): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1949): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2680): UpdateCorporaTask done [took 235 ms] updated apps [took 235 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  949): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
,D/WifiStateMachine(  949): processMsg: ConnectedState
,D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  949): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  949): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  949): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  949): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  949): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  949): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  949): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  949): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  949): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
,D/WifiStateMachine(  949): processMsg: ConnectedState
,D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  949): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5211): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229700031, nextTick: 60001, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229700032, nextTick: 60000, mDrawingTime: 1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
,D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  949): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  949): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  949): [updateScreenState] screen on = false
D/KnockOnPowerController(  949): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  949): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  949): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  949): _hal_sensors_flush: handle=35
,I/qcom_sensors_hal(  949): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  949): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  949): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/KnockOnPowerController(  949): [setProximitySensorEnabled] enable = true
D/qcom_sensors_hal(  949): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6327 usec
,D/qcom_sensors_hal(  949): hal_acquire_resources
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,I/qcom_sensors_hal(  949): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,D/qcom_sensors_hal(  949): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
I/qcom_sensors_hal(  949): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  949): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.454666 Y: -0.401459 Z: 9.784698 
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454666 .y:-0.401459 .z:9.784698
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  949): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  949): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  949): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  949): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.444794 Y: -0.395203 Z: 9.786163 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444794 .y:-0.395203 .z:9.786163
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,I/Sensors (  317): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  949): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  949): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  949): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.437607 Y: -0.400177 Z: 9.773987 
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.437607 .y:-0.400177 .z:9.773987
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  949): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  949): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  949): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.444260 Y: -0.401230 Z: 9.781067 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444260 .y:-0.401230 .z:9.781067
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.447830 Y: -0.395660 Z: 9.792953 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447830 .y:-0.395660 .z:9.792953
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.449341 Y: -0.411285 Z: 9.776627 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449341 .y:-0.411285 .z:9.776627
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.452454 Y: -0.407944 Z: 9.780609 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452454 .y:-0.407944 .z:9.780609
,D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  949): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4434c258)
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb84e4450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  949): **** SHOWN CALLED ****
I/WindowManager(  949): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1489): setPowerMode; state=4
,D/WifiStateMachine(  949): handleScreenStateChanged: true
,D/WifiStateMachine(  949): handleMessage: E msg.what=131154
D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  949): doString: SIGNAL_POLL
,D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  949): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  949): handleMessage: X
,D/WifiStateMachine(  949): handleMessage: E msg.what=131127
D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
,D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=131158
D/WifiStateMachine(  949): processMsg: ConnectedState
,D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): processMsg: DriverStartedState
D/WifiStateMachine(  949): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=132097
D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): processMsg: DriverStartedState
,D/WifiStateMachine(  949): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  949): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2035): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2035): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  949): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false,
,D/WifiOffDelayIfNotUsed(  949): stopMonitoring
,E/AudioSystem(  949): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 949
,V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43409fd0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.456665 Y: -0.376862 Z: 9.759064 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456665 .y:-0.376862 .z:9.759064
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3787): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WeatherAncestor( 1860): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 2:35:4
,I/SlideAside( 3787): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1860): 2 : This is isUpdating : false
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1860): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 2:35:4
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1860): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
D/WeatherService( 1860): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1860): 2 : shouldTimeTickRegistered : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  949): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  949): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  949): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  949): hal_process_report_ind: X: -0.456894 Y: -0.394958 Z: 9.771652 
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456894 .y:-0.394958 .z:9.771652
D/qcom_sensors_hal(  949): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=0
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
D/WifiStateMachine(  949): handleMessage: E msg.what=131155
D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiStateMachine(  949): handleMessage: X
,D/qdlights( 1156): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1156): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  949): Excessive delay in blankDisplay() while turning screen off: 410ms
D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229704946, nextTick: 55085, mDrawingTime: 1
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229704969, nextTick: 55064, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1489): setPowerMode; state=4
D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
,D/WeatherService( 1860): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:35:4
,D/WeatherService( 1860): 2 : ACTION screen on
D/WeatherService( 1860): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1860): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:35:4
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling(  949): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/PhoneApp( 1465): Action intent recieved:android.intent.action.SCREEN_ON
D/GsmSST  ( 1465): Emergency Service
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  949): ACTION_SCREEN_ON
D/GsmSST  ( 1465): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1465): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
V/TelephonyAutoProfiling( 1465): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : support_assisted_dialing, value : null
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  949): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  949): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : vzw_gfit, value : null
I/qcom_sensors_hal(  949): _hal_sensors_activate: handle=0, Initialized the timestamp 
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : trf_based_vzw, value : null
D/qcom_sensors_hal(  949): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/PhoneInterfaceManager( 1465): [PhoneIntfMgr] sigLevel = 5
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
V/ActivityManager(  949): Moving to PAUSING: ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3}
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/qcom_sensors_hal(  949): hal_acquire_resources
D/qcom_sensors_hal(  949): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  949): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  949): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  949): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  949): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  949): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  949): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
V/ActivityManager(  949): Moving to PAUSED: ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  949): Moving to STOPPING: ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,V/ActivityManager(  949): Moving to DESTROYING: ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
I/LGImmersionVibrator(  949): Vibrator off
,D/UsbSettings( 2608): [AUTORUN] onDestroy() : getDefaultFunction =boot
,D/WifiStateMachine(  949): handleScreenStateChanged: false
V/UsbSettings( 2608): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2608): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2608): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/WifiStateMachine(  949): handleMessage: E msg.what=131154
,D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
D/WifiStateMachine(  949): handleMessage: X
D/WifiStateMachine(  949): handleMessage: E msg.what=131158
D/WifiStateMachine(  949): processMsg: ConnectedState
D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiStateMachine(  949): processMsg: ConnectModeState
D/WifiStateMachine(  949): processMsg: DriverStartedState
D/WifiStateMachine(  949): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  949): doBoolean: DRIVER SETSUSPENDMODE 1
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,E/AudioSystem(  949): AudioSystem::setParameters()...keyValue screen_state=off
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
D/KeyguardViewManager( 1142): onScreenTurnedOff()
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 949
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
V/ActivityManager(  949): Moving to STOPPED: ActivityRecord{43d74498 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  949): CMD_SCREEN_OFF 
,D/WifiController(  949): shouldWifiStayAwake TRUE
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd  len = 0, 0
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1156): clear
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  949): Moving to DESTROYED: ActivityRecord{432d66a0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 1 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Going to sleep and all paused
D/WifiNative-wlan0(  949):    returned true
D/WifiStateMachine(  949): handleMessage: X
D/NativeNfcBrcmPowerMode( 1489): setPowerMode; state=2
I/[LGHome]EVENT( 1504): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
D/WeatherService( 1860): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:35:5
D/WeatherService( 1860): 2 : ACTION screen off
D/WeatherService( 1860): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:35:5
V/TelephonyAutoProfiling(  949): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1465): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
D/GsmSST  ( 1465): Emergency Service
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1465): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1465): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1465): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1465): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1465): Action intent recieved:android.intent.action.SCREEN_OFF
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): ACTION_SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
D/BrcmNfcJni( 1489): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1489): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1477): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/NfcService( 1489): NFC-C OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  949): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/HeadsetStateMachine( 1217): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
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
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/WifiController(  949): battery changed pluggedType: 2
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Sensors (  317): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  949): handleMessage: E msg.what=131155
,D/WifiStateMachine(  949): processMsg: ConnectedState
,D/WifiStateMachine(  949): processMsg: L2ConnectedState
,D/WifiStateMachine(  949): handleMessage: X
,E/ThermalEngine(  283): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1465): getIsInUseVoLTE : false
,D/PhoneApp( 1465): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1537): Vacuum at: now=1450229714226 tag=VacuumService
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  949): battery changed pluggedType: 2
,W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229723040281565; DSPS: 5274279; Offset: 1450229562082060130
,I/GoogleURLConnFactory( 1537): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1537): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1537): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1537): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1537): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1537): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1537): No account for auth token provided
,D/dalvikvm( 1537): GC_CONCURRENT freed 1736K, 28% free 18051K/24832K, paused 3ms+4ms, total 45ms
,W/Uploader( 1537):  no longer exists, so no auth token.
,W/Uploader( 1537): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229743042072495; DSPS: 5929698; Offset: 1450229562082050523
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  949): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229760035, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229760045, nextTick: 59967, mDrawingTime: 7
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229763043685924; DSPS: 6585111; Offset: 1450229562082046520
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229783045346021; DSPS: 7240525; Offset: 1450229562082058668
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229803047128669; DSPS: 7895943; Offset: 1450229562082071296
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229820029, nextTick: 59998, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229820045, nextTick: 59975, mDrawingTime: 6
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229823048702985; DSPS: 8551355; Offset: 1450229562082058698
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229843050830842; DSPS: 9206785; Offset: 1450229562082050325
,I/jxcore-log( 4729): Connected to the server!
I/jxcore-log( 4729): 
,I/chromium( 4729): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229863052245157; DSPS: 9862191; Offset: 1450229562082060831
,D/wpa_supplicant( 2035): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 7 BSSID fc:6f:b7:3e:78:0a SSID 'UPC249917252' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 8 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 9 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 10 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 fc:6f:b7:3e:78:0a]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 64:7c:34:12:7f:81]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 fe:94:e3:11:35:3c]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 a0:c5:62:7a:49:96]
,D/WifiMonitor(  949): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11]
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229880043, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229880047, nextTick: 59980, mDrawingTime: 3
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229883053739733; DSPS: 10517600; Offset: 1450229562082060046
,D/dalvikvm( 2663): GC_CONCURRENT freed 7675K, 32% free 16982K/24832K, paused 2ms+2ms, total 60ms
,D/dalvikvm(  949): GC_EXPLICIT freed 2378K, 49% free 29807K/57628K, paused 5ms+15ms, total 191ms
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1537): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  949): updateLightListLocked :r=NotificationRecord(0x4331e5e8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  949): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1537): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1537): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1537): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1537): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1537): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1537): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1537): 	at dalvik.system.NativeStart.run(Native Method)
E/PlayEventLogger( 4272): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4272): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4272): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4272): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4272): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4272): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4272): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4272): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4272): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4272): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229903055582329; DSPS: 11173020; Offset: 1450229562082071587
,I/LocationManagerService(  949): remove 4335c798
,D/LocationManagerService(  949): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  949): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  949): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  949): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  949): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2663): GC_CONCURRENT freed 1717K, 31% free 17313K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2663): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/Mlt MonitorService( 2663): parseLastkmsg to dump
,D/dalvikvm( 2663): GC_CONCURRENT freed 2014K, 31% free 17220K/24832K, paused 2ms+3ms, total 41ms
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229923057182061; DSPS: 11828433; Offset: 1450229562082053888
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229940063, nextTick: 59967, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450229940064, nextTick: 59968, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229943058448043; DSPS: 12483834; Offset: 1450229562082068649
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229963060848817; DSPS: 13139273; Offset: 1450229562082058534
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450229983062372664; DSPS: 13794683; Offset: 1450229562082056502
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230000044, nextTick: 59984, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230000049, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230003063886666; DSPS: 14450093; Offset: 1450229562082044625
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230023065537648; DSPS: 15105507; Offset: 1450229562082047658
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230043067366807; DSPS: 15760927; Offset: 1450229562082045763
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230060035, nextTick: 59958, mDrawingTime: 14
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230060061, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230063069173674; DSPS: 16416346; Offset: 1450229562082052092
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230083070954448; DSPS: 17071764; Offset: 1450229562082062847
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230103072441420; DSPS: 17727173; Offset: 1450229562082054458
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230120019, nextTick: 59970, mDrawingTime: 19
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230120057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230123073865266; DSPS: 18382579; Offset: 1450229562082074495
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230143075356978; DSPS: 19037988; Offset: 1450229562082070846
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230163077204001; DSPS: 19693409; Offset: 1450229562082056296
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  949): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/TangibleManager( 1477): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1477): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1477): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1477): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230180016, nextTick: 60002, mDrawingTime: 11
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230180064, nextTick: 59969, mDrawingTime: 0
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230183078819201; DSPS: 20348822; Offset: 1450229562082054065
,I/ActivityManager(  949): Killing 4652:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  949): resumeTopActivitiesLocked(): target Stack:ActivityStack{43381c28 stackId=1, 1 tasks}
,D/ActivityManager(  949): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230203081290445; DSPS: 21004263; Offset: 1450229562082053385
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230223083028145; DSPS: 21659680; Offset: 1450229562082051583
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230240024, nextTick: 59963, mDrawingTime: 19
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230240069, nextTick: 59957, mDrawingTime: 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230243084772825; DSPS: 22315097; Offset: 1450229562082056761
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230263086377609; DSPS: 22970509; Offset: 1450229562082074631
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230283088170726; DSPS: 23625928; Offset: 1450229562082067211
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230300015, nextTick: 60000, mDrawingTime: 12
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230300065, nextTick: 59967, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230303090084103; DSPS: 24281351; Offset: 1450229562082057980
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230323091831701; DSPS: 24936768; Offset: 1450229562082066076
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230343093336641; DSPS: 25592178; Offset: 1450229562082045138
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230360045, nextTick: 59978, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230360049, nextTick: 59979, mDrawingTime: 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230363095197623; DSPS: 26247598; Offset: 1450229562082075065
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230383096548344; DSPS: 26903003; Offset: 1450229562082052495
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230403098342034; DSPS: 27558422; Offset: 1450229562082045648
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  949): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  949): Done.
,D/QcConnectivityService(  949): Setting timer for 720seconds
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230420069, nextTick: 59953, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230420074, nextTick: 59955, mDrawingTime: 2
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230423099991715; DSPS: 28213836; Offset: 1450229562082047380
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230443101792228; DSPS: 28869255; Offset: 1450229562082047355
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230463103632689; DSPS: 29524675; Offset: 1450229562082056762
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230480044, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230480048, nextTick: 59981, mDrawingTime: 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230483105189088; DSPS: 30180086; Offset: 1450229562082056764
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230503106739080; DSPS: 30835497; Offset: 1450229562082050360
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230523108548603; DSPS: 31490916; Offset: 1450229562082059346
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230540053, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230540061, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230543110997554; DSPS: 32146356; Offset: 1450229562082066890
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230563112346088; DSPS: 32801760; Offset: 1450229562082072651
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230583113872070; DSPS: 33457170; Offset: 1450229562082072754
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230600040, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230600043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230603115488521; DSPS: 34112583; Offset: 1450229562082071773
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230623117111221; DSPS: 34767997; Offset: 1450229562082046524
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230643118602776; DSPS: 35423405; Offset: 1450229562082073235
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230660062, nextTick: 59965, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230660066, nextTick: 59965, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230663120456154; DSPS: 36078826; Offset: 1450229562082065041
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230683122295887; DSPS: 36734246; Offset: 1450229562082073720
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230703123767806; DSPS: 37389655; Offset: 1450229562082050277
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230720041, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230720045, nextTick: 59983, mDrawingTime: 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230723125098058; DSPS: 38045058; Offset: 1450229562082068273
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230743126462947; DSPS: 38700463; Offset: 1450229562082059871
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230763128662887; DSPS: 39355895; Offset: 1450229562082062546
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230780045, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230780062, nextTick: 59969, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230783130793244; DSPS: 40011325; Offset: 1450229562082056672
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230803132169747; DSPS: 40666730; Offset: 1450229562082059884
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230823133834843; DSPS: 41322145; Offset: 1450229562082046513
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230840074, nextTick: 59957, mDrawingTime: 2
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230840075, nextTick: 59958, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230843135666292; DSPS: 41977565; Offset: 1450229562082046908
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230863137122901; DSPS: 42632972; Offset: 1450229562082069191
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230883138996695; DSPS: 43288394; Offset: 1450229562082050895
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230900042, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230900051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230903140751480; DSPS: 43943811; Offset: 1450229562082066178
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230923142402514; DSPS: 44599225; Offset: 1450229562082069263
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230943143744901; DSPS: 45254629; Offset: 1450229562082068876
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230960052, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450230960059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230963145293384; DSPS: 45910040; Offset: 1450229562082060963
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450230983146606136; DSPS: 46565443; Offset: 1450229562082061459
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231003148149514; DSPS: 47220854; Offset: 1450229562082048440
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231020050, nextTick: 59971, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231020058, nextTick: 59969, mDrawingTime: 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231023150347424; DSPS: 47876286; Offset: 1450229562082049085
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231043151720853; DSPS: 48531691; Offset: 1450229562082049223
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231063153177356; DSPS: 49187098; Offset: 1450229562082071399
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231080045, nextTick: 59978, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231080051, nextTick: 59978, mDrawingTime: 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231083154518182; DSPS: 49842502; Offset: 1450229562082069452
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231103156038799; DSPS: 50497912; Offset: 1450229562082064190
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231123157962749; DSPS: 51153335; Offset: 1450229562082065533
,D/GCM     ( 1537): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  949): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  949): Done.
,D/QcConnectivityService(  949): Setting timer for 720seconds
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1537): [DefaultAuthDelegateService] Use browser flow? false
,E/Ads     ( 1949): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  949): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  949): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231140036, nextTick: 59980, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231140048, nextTick: 59962, mDrawingTime: 8
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231143160285763; DSPS: 51808771; Offset: 1450229562082069211
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231163162149974; DSPS: 52464192; Offset: 1450229562082071849
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231183163502987; DSPS: 53119597; Offset: 1450229562082051571
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231200042, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231200047, nextTick: 59959, mDrawingTime: 11
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231203164966990; DSPS: 53775005; Offset: 1450229562082050731
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231223166318180; DSPS: 54430409; Offset: 1450229562082059147
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231243167601037; DSPS: 55085811; Offset: 1450229562082060266
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231260031, nextTick: 59982, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231260061, nextTick: 59968, mDrawingTime: 3
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231263169142591; DSPS: 55741222; Offset: 1450229562082045424
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231283171150970; DSPS: 56396647; Offset: 1450229562082070160
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231303172754296; DSPS: 57052060; Offset: 1450229562082056054
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231320041, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231320047, nextTick: 59973, mDrawingTime: 5
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231323174561892; DSPS: 57707479; Offset: 1450229562082063113
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231343176105270; DSPS: 58362890; Offset: 1450229562082050095
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231363177678908; DSPS: 59018301; Offset: 1450229562082067336
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231380078, nextTick: 59950, mDrawingTime: 4
,I/ProcessStatsService(  949): Prepared write state in 59ms
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231380080, nextTick: 59949, mDrawingTime: 3
D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  949): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-55.bin
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231383179512598; DSPS: 59673721; Offset: 1450229562082069972
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231403181672383; DSPS: 60329152; Offset: 1450229562082063008,
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231423183332843; DSPS: 60984567; Offset: 1450229562082045002
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231440036, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450231440053, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231443185177680; DSPS: 61639987; Offset: 1450229562082058784
,D/LocationManagerService(  949): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1537): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/EventLogService( 1949): Aggregate from 1450229683983 (log), 1450229655086 (data)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1949): GC_CONCURRENT freed 1943K, 22% free 19595K/24832K, paused 4ms+4ms, total 49ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231463186853557; DSPS: 62295402; Offset: 1450229562082056194
,D/qcom_sensors_hal(  949): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  949): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  949): hal_ts_offset_is: Apps: 1450231483188421153; DSPS: 62950813; Offset: 1450229562082067394
,TIME-OUT KILL (timeout was 1800000ms)
```
