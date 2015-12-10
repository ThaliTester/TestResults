#### Test 50650278d6c551a_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
W/BaseAppContext( 1946): Using Auth Proxy for data requests.
,W/GAV2    ( 4664): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 4021:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2}
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/dalvikvm( 1946): GC_CONCURRENT freed 1616K, 22% free 19469K/24832K, paused 2ms+6ms, total 43ms
D/dalvikvm( 1946): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1946): fetch service done; releasing wakelock
I/ConfigFetchService( 1946): stopping self
D/AndroidRuntime( 4712): 
D/AndroidRuntime( 4712): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4712): CheckJNI is OFF
D/dalvikvm( 4712): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4712): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4712): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4712): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4712): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4712): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/memtrack( 4712): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4712): failed to load memtrack module: -2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1946): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4712): Calling main entry com.android.commands.am.Am
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4712
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (109 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  966): startService SlideAside
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{43267b58 stackId=1, 2 tasks}
D/AndroidRuntime( 4712): Shutting down VM
D/UsbSettingsControl( 2588): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2588): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4712): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 4ms
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3784): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4729 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3784): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/SlideAside( 3784): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/Icing   ( 1946): Loaded CLD2 Version V2.0 - 20141016
D/HyLog   ( 4729): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4729): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4729): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Icing   ( 1946): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4729): Binding Chromium to the background looper Looper (main, tid 1) {428a0818}
I/chromium( 4729): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4729): Initializing chromium process, renderers=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
W/BaseRuntimeLoader( 4729): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4729): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4729): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4729): Enabling debug mode 0
W/AwContents( 4729): nativeOnDraw failed; clearing to background color.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +363ms
I/InputMethodManagerService(  966): IME STATUS OFF
W/AwContents( 4729): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 4729): Timeline: Activity_idle id: android.os.BinderProxy@428a1ef8 time:110455
D/JsMessageQueue( 4729): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4729): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a6848
D/dalvikvm( 4729): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a6848
D/jxcore_app_log( 4729): JniHelper::setJavaVM(0x4176c838), pthread_self() = 1631356080
D/JX-Cordova( 4729): jxcore cordova android initializing
I/dalvikvm( 4729): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4729): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4729): VFY: replacing opcode 0x6e at 0x0045
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3} time:110846
D/ActivityManager(  966): no-history finish of ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{43292888 ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
D/UsbSettings( 2588): [AUTORUN] onStop()
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4729): GC_CONCURRENT freed 2777K, 12% free 21876K/24832K, paused 3ms+1ms, total 44ms
D/dalvikvm( 4729): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 4729): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 228K, 12% free 21864K/24832K, paused 22ms, total 22ms
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 193K, 12% free 21889K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4729): Grow heap (frag case) to 23.687MB for 144892-byte allocation
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 257K, 13% free 21936K/24976K, paused 36ms, total 37ms
,I/dalvikvm-heap( 4729): Grow heap (frag case) to 23.802MB for 217334-byte allocation
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 370K, 13% free 22010K/25192K, paused 46ms, total 46ms
,I/dalvikvm-heap( 4729): Grow heap (frag case) to 23.978MB for 325996-byte allocation
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 571K, 14% free 22132K/25512K, paused 43ms, total 43ms
I/dalvikvm-heap( 4729): Grow heap (frag case) to 24.252MB for 488990-byte allocation
D/dalvikvm( 4729): GC_FOR_ALLOC freed 870K, 15% free 22308K/25992K, paused 39ms, total 40ms
I/dalvikvm-heap( 4729): Grow heap (frag case) to 24.659MB for 733480-byte allocation
D/dalvikvm( 4729): GC_FOR_ALLOC freed 1291K, 16% free 22566K/26712K, paused 31ms, total 32ms
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2076): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/dalvikvm( 4729): GC_CONCURRENT freed 1676K, 15% free 22938K/26712K, paused 1ms+2ms, total 46ms
D/dalvikvm( 4729): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 4729): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 4729): GC_FOR_ALLOC freed 376K, 15% free 22895K/26712K, paused 25ms, total 26ms
I/dalvikvm-heap( 4729): Grow heap (frag case) to 26.106MB for 1650320-byte allocation
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.453735 Y: -0.390320 Z: 9.768021 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453735 .y:-0.390320 .z:9.768021
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/dalvikvm( 4729): GC_CONCURRENT freed 1662K, 18% free 23465K/28324K, paused 2ms+3ms, total 36ms
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.462601 Y: -0.392548 Z: 9.736420 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462601 .y:-0.392548 .z:9.736420
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 1400K, 17% free 23550K/28324K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4729): Grow heap (frag case) to 27.532MB for 2475476-byte allocation
,D/dalvikvm( 4729): GC_CONCURRENT freed 412K, 16% free 25912K/30744K, paused 2ms+3ms, total 62ms
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 4237K, 21% free 24504K/30744K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4729): Grow heap (frag case) to 29.644MB for 3713210-byte allocation
,D/dalvikvm( 4729): GC_CONCURRENT freed 294K, 19% free 27962K/34372K, paused 4ms+4ms, total 31ms
,D/dalvikvm( 4729): GC_FOR_ALLOC freed 3184K, 26% free 25480K/34372K, paused 24ms, total 24ms
,W/jxcore-log( 4729): Initializing JXcore engine
,W/jxcore-log( 4729): JXcore engine is ready
,D/dalvikvm( 4729): GC_CONCURRENT freed 331K, 19% free 28152K/34372K, paused 2ms+1ms, total 35ms
,D/dalvikvm( 4729): WAIT_FOR_CONCURRENT_GC blocked 32ms
,W/jxcore-log( 4729): Starting JXcore engine
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/jxcore-log( 4729): Platform android
W/jxcore-log( 4729): 
,W/jxcore-log( 4729): Process ARCH arm
W/jxcore-log( 4729): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/jxcore-log( 4729): JXcore Cordova bridge is ready!
I/jxcore-log( 4729): 
,W/jxcore-log( 4729): JXcore engine is started
,I/chromium( 4729): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4729): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4729): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4664): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4729): Toggling radios to true
I/jxcore-log( 4729): 
,D/BluetoothManagerService(  966): Message: 20
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44937e40:true
D/BluetoothAdapter( 4729): enable(): BT is already enabled..!
D/WifiService(  966): New client listening to asynchronous messages
D/WifiStateMachine(  966): handleMessage: E msg.what=131145
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doBoolean: DISCONNECT
I/jxcore-log( 4729): Radios toggled
I/jxcore-log( 4729): 
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2076): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2076): wlan0: Cancelling scan request
D/wpa_supplicant( 2076): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2076): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2076): TDLS: Tear down peers
D/wpa_supplicant( 2076): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4729): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4729): 
,I/jxcore-log( 4729): Perf Test app loaded loaded
I/jxcore-log( 4729): 
D/WifiService(  966): setWifiEnabled: true pid=4729, uid=10304
E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  966): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  966): disconnect pid=4729, uid=10304
,D/WifiService(  966): reconnect pid=4729, uid=10304
I/Choreographer( 4729): Skipped 68 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2076): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2076): wlan0: Deauthentication notification
D/wpa_supplicant( 2076): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2076): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2076): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2076): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2076): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2076): wlan0: Disconnect event - remove keys
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2076): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8999d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2076):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2076): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2076): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2076): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2076): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2076): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2076): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2076): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2076): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2076): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2076): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2076): nl80211: Event message available
D/wpa_supplicant( 2076): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2076): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
,D/WifiNative-wlan0(  966):    returned true
,D/WifiStateMachine(  966): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  966): invokeExitMethods: ConnectedState
,W/Settings(  966): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  966): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  966): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131146
,D/WifiStateMachine(  966): processMsg: DisconnectingState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiNative-wlan0(  966): doBoolean: RECONNECT
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2076): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2076): Fast associate: Old scan results
D/wpa_supplicant( 2076): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2076): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2076): wlan0: nl80211: scan request
,D/wpa_supplicant( 2076): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,I/jxcore-log( 4729): check test folder
I/jxcore-log( 4729): 
D/wpa_supplicant( 2076): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2076): nl80211: Event message available
D/wpa_supplicant( 2076): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2076): wlan0: nl80211: Scan trigger
,D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147460
I/jxcore-log( 4729): found test : ./testFindPeers.js
I/jxcore-log( 4729): 
,D/WifiStateMachine(  966): processMsg: DisconnectingState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): Network connection lost
D/WifiStateMachine(  966): Stopping DHCP and clearing IP
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  966): doBoolean: SET ps 1
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2076): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2076): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2076): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  966):    returned true
,D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2076): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2076): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  966):    returned true
,D/DhcpStateMachine(  966): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  966): addressRemoved: 192.168.1.121/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  966): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  966): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiHS20(  966): hidePasspointNotification off =false
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
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
V/QCNEA   (  401): |CAC| 	NetConfig: Default    =true
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
D/QCNEA   (  401): |CAC| dispatchNetCfg: updating:0xb73b28dc
,D/QCNEA   (  401): |CAC| readCallback: read len:0, ret:-1, errno:11
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  966): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  966): invokeExitMethods: DisconnectingState
,D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  966): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/QcConnectivityService(  966): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  966): Attempting to switch to mobile
D/QcConnectivityService(  966): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  966): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131213
D/WifiStateMachine(  966): processMsg: DisconnectedState
I/jxcore-log( 4729): found test : ./testSendData.js
I/jxcore-log( 4729): 
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131213
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
,D/WifiStateMachine(  966): handleMessage: X
,D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
I/ActivityManager(  966): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4798 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 4798): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4798): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4798): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 4798): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  271): RouteController
D/PCSuite ( 4798): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4798): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/NetworkManagementService(  966): route cmd failed: 
W/NetworkManagementService(  966): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  966): '
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  966): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  966): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  966): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  966): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  966): android_net_utils_resetConnections in env=0x61f4a520 clazz=0x6ce00001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1555): Read error: ssl=0x625d1408: I/O error during system call, Connection timed out
D/QcConnectivityService(  966): resetConnections(wlan0, 3)
I/ActivityManager(  966): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4835 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  966): Killing 4220:com.google.android.talk/u0a77 (adj 15): empty #17
V/NativeCrypto( 1555): SSL shutdown failed: ssl=0x625d1408: I/O error during system call, Broken pipe
,I/ConfigService( 1555): onDestroy
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4835): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  966): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  966): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
I/chromium( 4729): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/QRemote ( 4835): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4835): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4835): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4835): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4835): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4835): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4835): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4835): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4835): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  966): Killing 3962:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  966): StoppedState
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4074): onReceive
,D/AppUp4:CustFacade( 4074): Context : android.app.ReceiverRestrictedContext@428bf2f0
,D/AppUp4:CustFacade( 4074): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4074): isOpenOperator : true
,D/AppUp4:CustFacade( 4074): isPhone : true
,I/LicenseContentProvider( 2973): start selecting data
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4074): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4074): begin check event
,I/AppUp4:CustModeStarterReceiver( 4074): Event For GoodConnectivity
,D/EAS     ( 4646): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4646): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4646): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/wpa_supplicant( 2076): nl80211: Event message available
D/wpa_supplicant( 2076): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2076): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2076): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2076): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 2076): nl80211: Survey data missing
D/wpa_supplicant( 2076): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2076): wlan0: BSS: Add new id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): wlan0: BSS: Add new id 8 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): wlan0: BSS: Add new id 9 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 2076): wlan0: New scan results available
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2076): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2076): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2076): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2076): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2076): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2076): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2076): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2076): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2076): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2076): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2076): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2076): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2076): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2076): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2076): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56
D/wpa_supplicant( 2076): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2076): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2076): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2076): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2076): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2076): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2076): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2076): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2076): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2076): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2076): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb899b5a8  cur,rent_ssid=0x0
D/wpa_supplicant( 2076): scard is not null..
D/wpa_supplicant( 2076): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2076): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2076): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2076): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2076): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2076): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2076): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2076): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2076): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2076): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2076): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2076): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2076): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2076): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2076): wlan0: Cancelling scan request
D/wpa_supplicant( 2076): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2076): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2076): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2076): RSN: PMKSA cache search - network_ctx=0xb899b5a8 try_opportunistic=0
D/wpa_supplicant( 2076): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2076): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2076): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2076): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2076): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2076): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2076): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2076): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2076): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2076): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2076): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2076): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2076): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2076): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2076): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2076): nl80211: Unsubscribe mgmt frames handle 0xb899a590 (mode change)
D/wpa_supplicant( 2076): nl80211: Subscribe to mgmt frames with non-AP handle 0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2076): nl80211: Register frame type=0xd0 nl_handle=0xb899a590
D/wpa_supplicant( 2076): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2076): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2076):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076):   * freq=2412
D/wpa_supplicant( 2076):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2076):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2076):   * Auth Type 0
D/wpa_supplicant( 2076):   * WPA Versions 0x2
D/wpa_supplicant( 2076): nl80211: Connect request send successfully
D/wpa_supplicant( 2076): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2076): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2076): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2076): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2076): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 a0:c5:62:7a:49:96]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 10:9a:dd:8e:22:d9]
D/WifiMonitor(  966): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  966): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  966): handleMessage: E msg.what=147461
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  966): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2076): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/wpa_supplicant( 2076): nl80211: Event message available
D/wpa_supplicant( 2076): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2076): nl80211: Connect event
D/wpa_supplicant( 2076): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2076): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2076): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2076): wlan0: Association info event
D/wpa_supplicant( 2076): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2076): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2076): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2076): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2076): wlan0: freq=2412 MHz
D/wpa_supplicant( 2076): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2076): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2076): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2076): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2076): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2076): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): scard is not null..
D/wpa_supplicant( 2076): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2076): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2076): TDLS: Remove peers on association
D/wpa_supplicant( 2076): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2076): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2076): EAPOL: enable timer tick
D/wpa_supplicant( 2076): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2076): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2076): wlan0: Cancelling scan request
D/wpa_supplicant( 2076): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2076): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2076): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2076): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2076): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2076): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2076): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2076): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2076): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2076): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  966): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  966): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  966): handleMessage: X
D/wpa_supplicant( 2076): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 82 e8 41 02 1e dc 08 cf 6b 55 0c 81 7a d0 b9 ...
D/wpa_supplicant( 2076): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2076): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2076): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2076): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2076): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2076):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2076):   key_nonce - hexdump(len=32): 82 e8 41 02 1e dc 08 cf 6b 55 0c 81 7a d0 b9 30 66 2f 66 f5 e0 e9 5e 22 51 8e 4e c9 28 f4 19 84
D/wpa_supplicant( 2076):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2076):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2076):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2076):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2076): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 82 e8 41 02 1e dc 08 cf 6b 55 0c 81 7a d0 b9 ...
D/wpa_supplicant( 2076): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2076): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2076): Get randomness: len=32 entropy=11
D/wpa_supplicant( 2076): WPA: Renewed SNonce - hexdump(len=32): 96 c6 1a 42 ce 52 ec d4 8b 69 24 2e 32 d1 95 9c a2 42 4b 6c 52 9e 70 47 fa 73 21 e0 dd 0e 5e 16
D/wpa_supplicant( 2076): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): WPA: Nonce1 - hexdump(len=32): 96 c6 1a 42 ce 52 ec d4 8b 69 24 2e 32 d1 95 9c a2 42 4b 6c 52 9e 70 47 fa 73 21 e0 dd 0e 5e 16
D/wpa_supplicant( 2076): WPA: Nonce2 - hexdump(len=32): 82 e8 41 02 1e dc 08 cf 6b 55 0c 81 7a d0 b9 30 66 2f 66 f5 e0 e9 5e 22 51 8e 4e c9 28 f4 19 84
D/wpa_supplicant( 2076): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2076): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2076): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2076): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2076): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2076): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2076): WPA: Derived Key MIC - hexdump(len=16): e0 39 bf e3 e3 d7 b1 3f 62 ff f1 81 d2 ca b5 3a
D/wpa_supplicant( 2076): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 96 c6 1a 42 ce 52 ec d4 8b 69 24 2e 32 d1 95 ...
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  966): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/wpa_supplicant( 2076): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 82 e8 41 02 1e dc 08 cf 6b 55 0c 81 7a d0 b9 ...
D/wpa_supplicant( 2076): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2076): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2076): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2076): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2076):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2076):   key_nonce - hexdump(len=32): 82 e8 41 02 1e dc 08 cf 6b 55 0c 81 7a d0 b9 30 66 2f 66 f5 e0 e9 5e 22 51 8e 4e c9 28 f4 19 84
D/wpa_supplicant( 2076):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2076):   key_rsc - hexdump(len=8): d0 11 00 00 00 00 00 00
D/wpa_supplicant( 2076):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2076):   key_mic - hexdump(len=16): a3 9e 3a 62 73 89 30 e2 c6 5a 98 02 dc b5 90 0a
D/wpa_supplicant( 2076): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 82 e8 41 02 1e dc 08 cf 6b 55 0c 81 7a d0 b9 ...
D/wpa_supplicant( 2076): RSN: encrypted key data - hexdump(len=56): c8 fc 54 6e f9 22 82 d1 84 b8 6a 3a bf dd 3d 13 63 53 07 93 01 cb 05 c3 e0 c8 67 9b 0a 12 63 8e ...
D/wpa_supplicant( 2076): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2076): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2076): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2076): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 9f 9f ...
D/wpa_supplicant( 2076): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2076): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2076): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2076): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2076): WPA: Derived Key MIC - hexdump(len=16): 20 ed 2c 83 5c 13 87 65 38 a6 56 e8 c6 7e ac d2
D/wpa_supplicant( 2076): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2076): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb899ac54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2076):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2076): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2076): WPA: Group Key - hexdump(len=16): [REMOVED],
D/wpa_supplicant( 2076): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2076): WPA: RSC - hexdump(len=6): d0 11 00 00 00 00
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f9103a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2076):    broadcast key
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
I/wpa_supplicant( 2076): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2076): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2076): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2076): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  966): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  966): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/LgeMiscReceiver( 4372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
D/wpa_supplicant( 2076): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
I/LgeMiscReceiver( 4372): action = android.net.conn.CONNECTIVITY_CHANGE
D/wpa_supplicant( 2076): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2076): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2076): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2076): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2076): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2076): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2076): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2076): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2076): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2076): EAPOL authentication completed successfully
D/wpa_supplicant( 2076): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2076): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2076): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  966): handleMessage: E msg.what=147459
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): Network connection established
D/WifiNative-wlan0(  966): doString: STATUS
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2076): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2076): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/LgeMiscReceiver( 4372): networkInfo.isConnected() = false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiNative-wlan0(  966):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  966): ssid=NG700
D/WifiNative-wlan0(  966): id=0
D/WifiNative-wlan0(  966): mode=station
D/WifiNative-wlan0(  966): pairwise_cipher=CCMP
D/WifiNative-wlan0(  966): group_cipher=CCMP
D/WifiNative-wlan0(  966): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  966): wpa_state=COMPLETED
D/WifiNative-wlan0(  966): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  966): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  966): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  966): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  966): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  966): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  966): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  966): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  966): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  966): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  966): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/DhcpStateMachine(  966): WaitBeforeStartState
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-20ms what=147462 obj=android.net.wifi.StateChangeResult@43cc10f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-19ms what=147462 obj=android.net.wifi.StateChangeResult@43dad020 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147459
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-20ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-3ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
I/ActivityManager(  966): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4879 uid=10052 gids={50052, 3003}
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
W/linker  ( 4646): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/wpa_supplicant( 2076): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
D/HtmlEditor( 4646): JNI_OnLoad
D/WifiStateMachine(  966): handleMessage: E msg.what=196612
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2076): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4646): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4646): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4646): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4646): register_HtmlEditor, Success
D/HyLog   ( 4879): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4879): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4879): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HtmlEditor( 4646): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4646): register_HtmlEditorTimer, Success
D/HtmlEditor( 4646): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4646): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4646): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4646): register_HtmlEditorFont, Success
D/HtmlEditor( 4646): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4646): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4646): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4646): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4646): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4646): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4646): JNI_OnLoad Success
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/HubEmail( 4646): JNI_OnLoad()
I/HubEmail( 4646): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4646): registerNatives()
I/HubEmail( 4646): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4646): registerNativeMethods()
I/HubEmail( 4646): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4646): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfili,ng(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/LGRssiData( 4879): [loadRssi] File not exist 
V/LGRssiData( 4879): [loadRssi] File not exist 
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
V/TelephonyAutoProfiling( 4879): [loadFeatureFromXml] *** start feature loading from xml
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/BaseRuntimeLoader( 4879): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4879): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/WifiController(  966): battery changed pluggedType: 2
W/BaseRuntimeLoader( 4879): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4879): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4879): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4879): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4879): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 4879): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4879): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4879): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4879): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  966): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4895 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  966): Killing 4420:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4895): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4895): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4895): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2076): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  966): doBoolean: SET ps 0
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2076): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2076): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2076): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
,D/WifiNative-wlan0(  966): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2076): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2076): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  966):    returned null
,E/WifiStateMachine(  966): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  966): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2076): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2076): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  966):    returned null
E/WifiStateMachine(  966): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  966): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  966): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  966): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  271): Setting iface cfg
I/ActivityManager(  966): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4909 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  966): Killing 4571:com.android.defcontainer/u0a4 (adj 15): empty #17
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432426b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432426b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): addressUpdated: 192.168.1.121/24 on wlan0 flags 128 scope 0
,D/CommandListener(  271): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  966): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131212
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.121/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=196613
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  966): doBoolean: SET ps 1
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2076): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2076): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2076): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  966):    returned true
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 2
D/HyLog   ( 4909): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4909): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4909): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2076): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2076): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  966):    returned true
,D/WifiStateMachine(  966): DHCP successful
D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  966): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  966): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  966): VerifyingLinkState enter
,D/WifiStateMachine(  966): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  966): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  966): send additional Connectivity Action
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  966): handleMessage: E msg.what=135190
D/WifiStateMachine(  966): processMsg: VerifyingLinkState
D/WifiStateMachine(  966): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,D/WifiStateMachine(  966): transitionTo: destState=CaptivePortalCheckState
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiStateTracker(  966): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  966): 
W/WifiStateTracker(  966):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  966):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
E/Parcel  (  401): Reading a NULL string not supported here.
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  966): invokeEnterMethods: CaptivePortalCheckState
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/WifiStateMachine(  966): CaptivePortalCheckState enter
D/WifiStateMachine(  966): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/WifiStateMachine(  966): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/ActivityManager(  966): Killing 4606:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
D/LGDMClient( 2872): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
D/WifiStateMachine(  966): handleMessage: E msg.what=131092
D/WifiStateMachine(  966): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  966): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  966): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  966): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/WifiStateMachine(  966): invokeExitMethods: CaptivePortalCheckState
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  966): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/QcConnectivityService(  966): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/LGDMClient( 2872): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
E/ActivityThread(  966): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  966): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  966): handleConnectivityChange: preConnState=2 connState=1
I/LGDMClient( 2872): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  966): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4924 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/HyLog   ( 4924): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4924): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4924): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/LGDMClient( 2872): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/        (  271): RouteController
,V/        (  271): RouteController
D/LGDMClient( 2872): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2872): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2872): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/LGDMSGCM( 4924): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
I/ActivityManager(  966): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4950 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  966): Killing 4634:com.lge.bnr/1000 (adj 15): empty #17
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  401): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  401): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  401): |CAC| updateNetCfgInfo
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC|                   Netconfig               
V/QCNEA   (  401): |CAC| *********************************************
V/QCNEA   (  401): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  401): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  401): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  401): |CAC| 	NetConfig: ip4        =192.168.1.121
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
D/QCNEA   (  401): |CAC| dispatchNetCfg: updating:0xb73b28dc
D/QCNEA   (  401): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/HyLog   ( 4950): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4950): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4950): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinService( 1946): Checking schedule, now: 1449754853029 next: 1449754795586
,I/CheckinService( 1946): active receiver: enabled
,I/NFS     ( 4950): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/CheckinService( 1946): Preparing to send checkin request
,I/EventLogService( 1946): Accumulating logs since 1449754762879
,I/Wireless_Storage( 4950): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4950): intf.getDisplayName() = lo
,I/Wireless_Storage( 4950): intf.getDisplayName() = sit0
I/Wireless_Storage( 4950): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4950): intf.getDisplayName() = teql0
I/Wireless_Storage( 4950): intf.getDisplayName() = wlan0
,D/NFS     ( 4950): interface name:wlan0 name:wlan0
D/NFS     ( 4950): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4950): interface name:wlan0 name:wlan0
D/NFS     ( 4950): addr:192.168.1.121 broadcast:192.168.1.255
,I/Wireless_Storage( 4950): CONNECT : WIFI_CONNECT
,D/DhcpStateMachine(  966): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  966): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  966): GC_EXPLICIT freed 23540K, 49% free 29641K/57600K, paused 2ms+8ms, total 141ms
,I/ActivityManager(  966): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4973 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  966): Killing 4271:com.android.contacts/u0a21 (adj 15): empty #17
,D/HyLog   ( 4973): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4973): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4973): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinRequestBuilder( 1946): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1946): Failed to find provider info for com.google.android.wearable.settings
,W/GAV2    ( 4973): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 1555): GC_EXPLICIT freed 1213K, 29% free 17824K/24832K, paused 2ms+3ms, total 23ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WebViewChromium( 4973): Binding Chromium to the main looper Looper (main, tid 1) {428a9440}
,I/chromium( 4973): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4973): Initializing chromium process, renderers=0
,W/chromium( 4973): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4973): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4973): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4973): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4973): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4973): Remote Branch: 
I/Adreno-EGL( 4973): Local Patches: 
I/Adreno-EGL( 4973): Reconstruct Branch: 
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x432cc228: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1946): awaiting user notification for token
I/NSApplication( 4973): Starting up...
,I/ActivityManager(  966): Killing 4286:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  966): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5009 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+6ms, total 21ms
,D/HyLog   ( 5009): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5009): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5009): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 14ms
,D/QRemote ( 4835): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4835): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4835): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4835): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,W/dalvikvm( 5009): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5009): VFY: replacing opcode 0x60 at 0x000b
,D/QRemote ( 4835): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4835): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4798): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/PCSuite ( 4798): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/dalvikvm( 5009): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5009): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5009): VFY: replacing opcode 0x62 at 0x005e
D/QRemote ( 4835): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 4835): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4835): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4835): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
I/MultiDex( 5009): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5009): install
I/MultiDex( 5009): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 5009): loading existing secondary dex files
I/MultiDex( 5009): load found 3 secondary dex files
I/MultiDex( 5009): install done
,D/dalvikvm( 5009): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5009): VFY: unable to resolve instance field 61
,D/dalvikvm( 5009): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5009): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5009): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5009): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5009): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5009): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5009): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5009): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5009): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5009): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b05f0
D/dalvikvm( 5009): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b05f0
,D/dalvikvm( 5009): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b05f0, skipping init
,D/dalvikvm( 5009): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b05f0
D/dalvikvm( 5009): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b05f0
,V/JNIHelp ( 5009): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 5009): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b05f0
,D/dalvikvm( 5009): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428b05f0
D/dalvikvm( 5009): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b05f0
,D/dalvikvm( 5009): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428b05f0
,I/ProviderInstaller( 5009): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1555): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1555): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1946): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1861): callingUid 10006, callindPid: 1861
I/dalvikvm( 5009): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5009): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5009): VFY: replacing opcode 0x6e at 0x000d
,E/MDM     ( 1423): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1946): Restart initialization of location
,I/dalvikvm( 5009): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5009): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5009): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f70000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f70000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=3350848557
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2076): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2076): EAPOL: disable timer tick
,D/dalvikvm( 5009): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a92450
D/dalvikvm( 5009): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a92450
,D/dalvikvm( 5009): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a92450, skipping init
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings( 5009): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 5009): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  966): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 5035): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 5009): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5009): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 86ms
,I/Adreno-EGL( 5009): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5009): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5009): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5009): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5009): Remote Branch: 
I/Adreno-EGL( 5009): Local Patches: 
I/Adreno-EGL( 5009): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 5009): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5009): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5009): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5009): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5009): Remote Branch: 
I/Adreno-EGL( 5009): Local Patches: 
I/Adreno-EGL( 5009): Reconstruct Branch: 
,D/WifiStateMachine(  966): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  966): handleMessage: E msg.what=131212
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
,D/WifiStateMachine(  966): processMsg: DefaultState
,D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  966): handleMessage: X
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  966): send additional Connectivity Action
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/QcConnectivityService(  966): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  966): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  966):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  966): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
,I/Adreno-EGL( 5009): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5009): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5009): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5009): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5009): Remote Branch: 
I/Adreno-EGL( 5009): Local Patches: 
I/Adreno-EGL( 5009): Reconstruct Branch: 
,I/jxcore-log( 4729): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4729): 
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
W/ProcessCpuTracker(  966): Skipping unknown process pid 4867
W/ProcessCpuTracker(  966): Skipping unknown process pid 4870
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  277): PrepareKeyRequest: nonce=1919073301
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1946): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DhcpStateMachine(  966): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  966): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  966): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.121
V/LgDhcpStateMachineHelper(  966): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  966): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  966): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  966): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  966): RunningState
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinTask( 1946): Sending checkin request (11577 bytes)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1946): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1946): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1946): awaiting user notification for token
D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x42c4cfe8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/CheckinRequestBuilder( 1946): Classify the device as Phone.
,I/CheckinTask( 1946): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1946): Checking schedule, now: 1449754855674 next: 1450332251670
,I/CheckinService( 1946): active receiver: disabled
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2076): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4074): onReceive
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/AppUp4:CustFacade( 4074): Context : android.app.ReceiverRestrictedContext@428bf2f0
D/AppUp4:CustFacade( 4074): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4074): isOpenOperator : true
,D/AppUp4:CustFacade( 4074): isPhone : true
,I/LicenseContentProvider( 2973): start selecting data
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4074): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4074): begin check event
,I/AppUp4:CustModeStarterReceiver( 4074): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4074): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4074): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4074): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4074): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4074): handleAsyncCustNotification do not startCustService
,D/GCM     ( 1555): Connected
,V/DownloadManager( 3123): DownloadService onCreate
,D/EAS     ( 4646): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4646): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 3123): in removeSpuriousFiles
,D/eas_req ( 4646): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 3123): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@4294fc98 on behalf of 3123
,I/DownloadManager( 3123): in trimDatabase
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,V/DownloadManager( 3123): DownloadService onStartCommand
,V/DownloadManager( 3123): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 3123): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/Tethering(  966): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  966): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@42952e58 on behalf of 3123
I/LgeMiscReceiver( 4372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4372): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 4646): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4372): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 4879): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/GCM     ( 1555): Message class com.google.f.a.a.p
D/MobileConnectivityChangeReceiver( 4879): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@42952528 on behalf of 3123
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LGDMClient( 2872): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/DownloadManager( 3123): DownloadService onDestroy
,D/LGDMSGCM( 4924): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2872): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2872): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4950): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4950): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2872): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2872): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2872): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2872): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4074): onReceive
,D/AppUp4:CustFacade( 4074): Context : android.app.ReceiverRestrictedContext@428bf2f0
D/AppUp4:CustFacade( 4074): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4074): isOpenOperator : true
,D/AppUp4:CustFacade( 4074): isPhone : true
,I/LicenseContentProvider( 2973): start selecting data
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4074): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4074): begin check event
,I/AppUp4:CustModeStarterReceiver( 4074): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 3123): DownloadService onCreate
,I/DownloadManager( 3123): in removeSpuriousFiles
,V/DownloadManager( 3123): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4646): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@42957578 on behalf of 3123
,D/EAS     ( 4646): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 3123): in trimDatabase
,V/DownloadManager( 3123): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3123): DownloadService onStartCommand
V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@42959320 on behalf of 3123
,V/DownloadManager( 3123): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@4295b038 on behalf of 3123
I/LgeMiscReceiver( 4372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4372): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4372): networkInfo.isConnected() = true
D/PhoneState( 4372): setPdpRejectCasuse : false
,V/DownloadManager( 3123): DownloadService onDestroy
,D/MobileConnectivityChangeReceiver( 4879): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4879): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4646): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2872): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4924): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2872): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2872): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4950): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4950): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2872): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2872): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2872): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2872): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  292): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,D/WifiController(  966): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4074): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4074): onReceive
D/AppUp4:CustFacade( 4074): Context : android.app.ReceiverRestrictedContext@428bf2f0
D/AppUp4:CustFacade( 4074): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4074): isOpenOperator : true
,D/AppUp4:CustFacade( 4074): isPhone : true
,I/LicenseContentProvider( 2973): start selecting data
,D/SIMObserver( 2973): simInfo1
,I/AppUp4:EulaManager( 4074): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4074): begin check event
,I/AppUp4:CustModeStarterReceiver( 4074): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 3123): DownloadService onCreate
,D/EAS     ( 4646): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 3123): in removeSpuriousFiles
D/EAS     ( 4646): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 3123): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@4295f770 on behalf of 3123
,I/DownloadManager( 3123): in trimDatabase
,V/DownloadManager( 3123): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@42960c80 on behalf of 3123
,V/DownloadManager( 3123): DownloadService onStartCommand
,V/DownloadManager( 3123): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4372): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4372): networkInfo.isConnected() = true
,D/PhoneState( 4372): setPdpRejectCasuse : false
,D/dalvikvm( 3123): GC_EXPLICIT freed 494K, 33% free 16778K/24832K, paused 2ms+4ms, total 30ms
,D/dalvikvm(  966): GC_EXPLICIT freed 2084K, 49% free 29569K/57600K, paused 3ms+6ms, total 105ms
,V/DownloadManager( 3123): created cursor android.database.sqlite.SQLiteCursor@42962e30 on behalf of 3123
,W/Settings( 4646): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4879): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4879): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2872): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3123): DownloadService onDestroy
,D/LGDMClient( 2872): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4924): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2872): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4950): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4950): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2872): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2872): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2872): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2872): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  966): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/WifiServiceExtension(  966): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  966): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4973): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2076): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4308): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4308): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  966): Killing 4664:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.478790 Y: -0.404892 Z: 9.758514 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.478790 .y:-0.404892 .z:9.758514
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.475967 Y: -0.400986 Z: 9.759735 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.475967 .y:-0.400986 .z:9.759735
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449754860036, nextTick: 59995, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449754860038, nextTick: 59995, mDrawingTime: 0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2076): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 3784): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/SlideAside( 3784): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  966): Handling package changes for user 0
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "mms"
,I/InputReader(  966): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  966): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5171 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HyLog   ( 5171): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5171): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5171): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Babel   ( 5171): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5171): MmsConfig.loadMmsSettings
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/MediaCodecList( 5171): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5171): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5171): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5171): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5171): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5171): MmsConfig.loadFromDatabase
D/WifiController(  966): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1214): Disconnected process message: 10
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
V/GmsNetworkLocationProvi( 1423): DISABLE
W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5171): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5171): MmsConfig.loadFromResources
I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
E/Babel   ( 5171): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5171): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5171): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  966): battery changed pluggedType: 2
V/LGRssiData( 5171): [loadRssi] File not exist 
V/LGRssiData( 5171): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5171): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 5171): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5171): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5171): [getValue] FEATURE key : vzw_roaming_state, value : null
D/LocationProviderProxy(  966): applying state to connected service
D/LocationProviderProxy(  966): applying state to connected service
D/AppUp4:Utils( 4074): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4074): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4074): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 4074): onReceive
D/AppUp4:CustFacade( 4074): Context : android.app.ReceiverRestrictedContext@428bf2f0
D/AppUp4:CustFacade( 4074): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4074): isOpenOperator : true
D/AppUp4:CustFacade( 4074): isPhone : true
I/LicenseContentProvider( 2973): start selecting data
D/SIMObserver( 2973): simInfo1
I/AppUp4:EulaManager( 4074): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4074): begin check event
D/AppUp4:Utils( 4074): [getPackageName] uri : package:com.google.android.gms
I/AppUp4:CustModeStarterReceiver( 4074): Event For Nothing, skip.
,I/ActivityManager(  966): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5218 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5218): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5218): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5218): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5218): BUILD Country: EU
,I/SystemConfig( 5218): BUILD Operator: OPEN
I/ActivityManager(  966): Killing 4798:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  966): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5234 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,I/SystemConfig( 5218): systemFeature RCS result false
,D/SystemConfig( 5218): refreshRcsSupport() :false
I/ActivityManager(  966): Killing 4835:com.lge.qremote/u0a96 (adj 15): empty #17
,D/HyLog   ( 5234): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5234): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5234): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  966): Killing 3123:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2661): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1946): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1946): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  966): Delaying start of: ServiceRecord{449f3ae8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1946): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1946): GC_CONCURRENT freed 1935K, 22% free 19555K/24832K, paused 3ms+3ms, total 36ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2661): UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1154): GC_CONCURRENT freed 2903K, 11% free 25443K/28524K, paused 1ms+2ms, total 36ms
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2076): nl80211: survey data missing!
,E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  966): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  966): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  966): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  966): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  966): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  966): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  966): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2076): nl80211: survey data missing!
,E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/GAV4    ( 5171): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2076): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PowerManagerService(  966): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  966): [updateScreenState] screen on = false
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  966): _hal_sensors_flush: handle=35
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, enabled=1
,D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 7629 usec
,D/qcom_sensors_hal(  966): hal_acquire_resources
,I/qcom_sensors_hal(  966): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  966): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  966): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  966): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.468384 Y: -0.394714 Z: 9.756073 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468384 .y:-0.394714 .z:9.756073
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  966): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  966): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  966): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  966): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.452591 Y: -0.399521 Z: 9.758347 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452591 .y:-0.399521 .z:9.758347
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.459213 Y: -0.398758 Z: 9.780884 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459213 .y:-0.398758 .z:9.780884
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Sensors (  353): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  966): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  966): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  966): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  966): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  966): proximitySensorChanged  positive = true
I/KnockOnPowerController(  966): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.466522 Y: -0.384781 Z: 9.780197 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466522 .y:-0.384781 .z:9.780197
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.446762 Y: -0.400330 Z: 9.748245 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446762 .y:-0.400330 .z:9.748245
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.451050 Y: -0.415344 Z: 9.762848 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.444397 Y: -0.393188 Z: 9.788330 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.451050 .y:-0.415344 .z:9.762848
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.465759 Y: -0.391724 Z: 9.772369 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465759 .y:-0.391724 .z:9.772369
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  966): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@432666d8)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  966): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
I/WindowManager(  966): No lock screen! windowToken=null
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb8316450
,D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/WifiStateMachine(  966): handleScreenStateChanged: true
,D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2076): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  966): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  966): stopMonitoring
,D/wpa_supplicant( 2076): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131127
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=132097
D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  966): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2076): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2076): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  966): handleMessage: X
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 966
V/SRS_Proc(  277): ParamSet string: screen_state=on
,D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{428e7958 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3784): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WeatherAncestor( 1875): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:41:12
,I/SlideAside( 3784): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1875): 2 : This is isUpdating : false
,D/WeatherAncestor( 1875): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:41:12
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/WeatherService( 1875): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1875): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1875): 2 : shouldTimeTickRegistered : false
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1154): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1154): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/SurfaceControl(  966): Excessive delay in blankDisplay() while turning screen off: 383ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449754873290, nextTick: 46743, mDrawingTime: 0
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449754873317, nextTick: 46716, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/WeatherService( 1875): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:41:13
,D/WeatherService( 1875): 2 : ACTION screen on
,D/WeatherService( 1875): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1875): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:41:13
D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
D/GsmSST  ( 1448): Emergency Service
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.437485 Y: -0.394958 Z: 9.771606 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.437485 .y:-0.394958 .z:9.771606
,V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3}
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
D/qcom_sensors_hal(  966): hal_acquire_resources
D/qcom_sensors_hal(  966): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  966): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  966): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  966): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  966): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,D/UsbSettings( 2588): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/UsbSettings( 2588): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2588): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2588): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  966): Vibrator off
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{43d02eb0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
,D/WifiStateMachine(  966): handleScreenStateChanged: false
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  966): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 966
V/SRS_Proc(  277): ParamSet string: screen_state=off
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2076): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2076): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  966): CMD_SCREEN_OFF 
D/WifiController(  966): shouldWifiStayAwake TRUE
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1154): clear
,D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{4335de68 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43267b58 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
D/wpa_supplicant( 2076): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): handleMessage: X
D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
D/KeyguardViewManager( 1140): onScreenTurnedOff()
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
D/WeatherService( 1875): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:41:13
D/WeatherService( 1875): 2 : ACTION screen off
,D/WeatherService( 1875): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:41:13
D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
E/Parcel  (  401): Reading a NULL string not supported here.
,E/Parcel  (  401): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1448): Emergency Service
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/NfcService( 1472): NFC-C OFF
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,I/Sensors (  353): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,E/ThermalEngine(  292): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1555): Vacuum at: now=1449754882250 tag=VacuumService
,I/GoogleURLConnFactory( 1555): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1555): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1555): No account for auth token provided
,W/Uploader( 1555):  no longer exists, so no auth token.
,W/Uploader( 1555): No account for auth token provided
,D/dalvikvm( 1555): GC_CONCURRENT freed 1725K, 28% free 18046K/24832K, paused 19ms+5ms, total 96ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1449754891480788440; DSPS: 5280989; Offset: 1449754730317794056
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1449754911482437963; DSPS: 5936403; Offset: 1449754730317795630
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449754920052, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449754920059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1449754931484423164; DSPS: 6591828; Offset: 1449754730317797188
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1449754951485920917; DSPS: 7247237; Offset: 1449754730317799580
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1449754971487480857; DSPS: 7902648; Offset: 1449754730317803123
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1214): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449754980043, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449754980052, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1449754991489427985; DSPS: 8558072; Offset: 1449754730317797126
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1449755011490706884; DSPS: 9213474; Offset: 1449754730317794287
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1449755031492466042; DSPS: 9868892; Offset: 1449754730317783425

```
