#### Test 561510938d3c4f5_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1973): Using Auth Proxy for data requests.
W/BaseAppContext( 1973): Using Auth Proxy for data requests.
W/BaseAppContext( 1973): Using Auth Proxy for data requests.
,W/GAV2    ( 4602): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  962): Killing 4068:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1557): GC_EXPLICIT freed 1034K, 29% free 17816K/24832K, paused 1ms+2ms, total 22ms
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 1973): GC_CONCURRENT freed 1540K, 22% free 19486K/24832K, paused 2ms+4ms, total 46ms
I/ConfigFetchService( 1973): fetch service done; releasing wakelock
I/ConfigFetchService( 1973): stopping self
D/ChimeraCfgMgr( 1973): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1973): Module APK com.google.android.play.games already loaded
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4645): 
D/AndroidRuntime( 4645): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4645): CheckJNI is OFF
D/dalvikvm( 4645): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4645): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4645): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4645): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4645): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4645): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4645): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4645): failed to load memtrack module: -2
D/AndroidRuntime( 4645): Calling main entry com.android.commands.am.Am
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4645
I/Icing   ( 1973): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (124 us)
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  962): GC_FOR_ALLOC freed 24093K, 52% free 28830K/59736K, paused 196ms, total 196ms
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{43366c10 stackId=1, 2 tasks}
D/UsbSettingsControl( 2589): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2589): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/ActivityManager(  962): startService SlideAside
W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
D/AndroidRuntime( 4645): Shutting down VM
D/dalvikvm( 4645): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 4ms
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4675 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+3ms, total 27ms
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 4047): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/HyLog   ( 4675): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4675): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4675): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
I/SlideAside( 4047): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4047): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Icing   ( 1973): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1973): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4675): Binding Chromium to the background looper Looper (main, tid 1) {428a1f70}
I/chromium( 4675): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4675): Initializing chromium process, renderers=0
W/chromium( 4675): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4675): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4675): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4675): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4675): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4675): Remote Branch: 
I/Adreno-EGL( 4675): Local Patches: 
I/Adreno-EGL( 4675): Reconstruct Branch: 
I/dalvikvm( 4675): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4675): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4675): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4675): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4675): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4675): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4675): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4675): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4675): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4675): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4675): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4675): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4675): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4675): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4675): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4675): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4675): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4675): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4675): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4675): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4675): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4675): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4675): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4675): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4675): Enabling debug mode 0
W/AwContents( 4675): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  962): IME STATUS OFF
W/AwContents( 4675): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +376ms
I/ActivityManager( 4675): Timeline: Activity_idle id: android.os.BinderProxy@428a3740 time:111135
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/JsMessageQueue( 4675): Set native->JS mode to OnlineEventsBridgeMode
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/dalvikvm( 4675): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a7910
D/dalvikvm( 4675): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a7910
D/jxcore_app_log( 4675): JniHelper::setJavaVM(0x41764838), pthread_self() = 1639844416
D/JX-Cordova( 4675): jxcore cordova android initializing
I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3} time:111524
D/ActivityManager(  962): no-history finish of ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{4325bfd0 ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2589): [AUTORUN] onStop()
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/dalvikvm( 4675): GC_CONCURRENT freed 2643K, 12% free 22010K/24832K, paused 2ms+2ms, total 34ms
D/dalvikvm( 4675): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/dalvikvm( 4675): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 4675): GC_FOR_ALLOC freed 393K, 11% free 22315K/24832K, paused 23ms, total 24ms
D/dalvikvm( 4675): GC_FOR_ALLOC freed 86K, 11% free 22339K/24832K, paused 23ms, total 23ms
I/dalvikvm-heap( 4675): Grow heap (frag case) to 24.050MB for 63974-byte allocation
D/dalvikvm( 4675): GC_FOR_ALLOC freed 133K, 11% free 22352K/24896K, paused 28ms, total 28ms
I/dalvikvm-heap( 4675): Grow heap (frag case) to 24.093MB for 95956-byte allocation
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
D/dalvikvm( 4675): GC_FOR_ALLOC freed 188K, 11% free 22377K/24992K, paused 25ms, total 26ms
I/dalvikvm-heap( 4675): Grow heap (frag case) to 24.164MB for 143930-byte allocation
D/dalvikvm( 4675): GC_FOR_ALLOC freed 253K, 11% free 22424K/25136K, paused 23ms, total 23ms
I/dalvikvm-heap( 4675): Grow heap (frag case) to 24.278MB for 215890-byte allocation
D/dalvikvm( 4675): GC_FOR_ALLOC freed 367K, 12% free 22498K/25348K, paused 23ms, total 24ms
I/dalvikvm-heap( 4675): Grow heap (frag case) to 24.453MB for 323830-byte allocation
D/dalvikvm( 4675): GC_FOR_ALLOC freed 567K, 12% free 22618K/25668K, paused 23ms, total 23ms
D/dalvikvm( 4675): GC_FOR_ALLOC freed 862K, 12% free 22795K/25668K, paused 24ms, total 24ms
I/dalvikvm-heap( 4675): Grow heap (frag case) to 25.129MB for 728606-byte allocation
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 4675): GC_FOR_ALLOC freed 1278K, 13% free 23050K/26380K, paused 24ms, total 24ms
I/dalvikvm-heap( 4675): Grow heap (frag case) to 25.726MB for 1092904-byte allocation
D/dalvikvm( 4675): GC_CONCURRENT freed 1868K, 15% free 23449K/27448K, paused 1ms+4ms, total 35ms
D/dalvikvm( 4675): GC_FOR_ALLOC freed 197K, 15% free 23352K/27448K, paused 24ms, total 24ms
I/dalvikvm-heap( 4675): Grow heap (frag case) to 26.541MB for 1639352-byte allocation
D/dalvikvm( 4675): GC_CONCURRENT freed 1752K, 18% free 23953K/29052K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 4675): GC_FOR_ALLOC freed 1124K, 18% free 23955K/29052K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4675): Grow heap (frag case) to 27.912MB for 2459024-byte allocation
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.452728 Y: -0.418854 Z: 9.792511 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452728 .y:-0.418854 .z:9.792511
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/dalvikvm( 4675): GC_CONCURRENT freed 429K, 17% free 26314K/31456K, paused 2ms+2ms, total 33ms
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.453766 Y: -0.416138 Z: 9.793304 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453766 .y:-0.416138 .z:9.793304
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4675): GC_FOR_ALLOC freed 4088K, 21% free 24973K/31456K, paused 34ms, total 34ms
,I/dalvikvm-heap( 4675): Grow heap (frag case) to 30.080MB for 3688532-byte allocation
,D/dalvikvm( 4675): GC_CONCURRENT freed 351K, 19% free 28457K/35060K, paused 2ms+2ms, total 54ms
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4675): GC_FOR_ALLOC freed 4325K, 26% free 26081K/35060K, paused 39ms, total 39ms
,W/jxcore-log( 4675): Initializing JXcore engine
W/jxcore-log( 4675): JXcore engine is ready
,D/dalvikvm( 4675): GC_CONCURRENT freed 400K, 18% free 28887K/35060K, paused 1ms+1ms, total 26ms
,D/dalvikvm( 4675): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 4675): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 4675): Starting JXcore engine
,W/jxcore-log( 4675): Platform android
W/jxcore-log( 4675): 
,W/jxcore-log( 4675): Process ARCH arm
W/jxcore-log( 4675): 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4675): JXcore Cordova bridge is ready!
I/jxcore-log( 4675): 
,W/jxcore-log( 4675): JXcore engine is started
,I/chromium( 4675): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4675): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4675): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4675): Toggling radios to true
I/jxcore-log( 4675): 
,D/BluetoothManagerService(  962): Message: 20
,D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d08538:true
,D/BluetoothAdapter( 4675): enable(): BT is already enabled..!
D/WifiService(  962): New client listening to asynchronous messages
D/WifiStateMachine(  962): handleMessage: E msg.what=131145
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DISCONNECT
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2026): TDLS: Tear down peers
D/wpa_supplicant( 2026): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4675): Radios toggled
I/jxcore-log( 4675): 
,I/jxcore-log( 4675): My device name is: LGE-LG-D802
I/jxcore-log( 4675): 
D/WifiService(  962): setWifiEnabled: true pid=4675, uid=10304
E/WifiService(  962): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  962): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  962): disconnect pid=4675, uid=10304
D/WifiService(  962): reconnect pid=4675, uid=10304
,D/wpa_supplicant( 2026): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2026): wlan0: Deauthentication notification
D/wpa_supplicant( 2026): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2026): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2026): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2026): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2026): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb79e3d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Inte,rface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2026): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
W/Settings(  962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131146
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiNative-wlan0(  962): doBoolean: RECONNECT
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2026): Fast associate: Old scan results
D/wpa_supplicant( 2026): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2026): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2026): wlan0: nl80211: scan request
D/wpa_supplicant( 2026): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147460
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/wpa_supplicant( 2026): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection lost
D/WifiStateMachine(  962): Stopping DHCP and clearing IP
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/DhcpStateMachine(  962): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  962): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiP2pService(  962): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiHS20(  962): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
,E/Parcel  (  476): Reading a NULL string not supported here.
D/QCNEA   (  476): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  476): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  476): |CAC| updateNetCfgInfo
V/QCNEA   (  476): |CAC| *********************************************
V/QCNEA   (  476): |CAC|                   Netconfig               
V/QCNEA   (  476): |CAC| *********************************************
V/QCNEA   (  476): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  476): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  476): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  476): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  476): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  476): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  476): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  476): |CAC| *********************************************
D/QCNEA   (  476): |CAC| Received bssid= 
D/QCNEA   (  476): |CAC| net type = 3
V/QCNEA   (  476): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  476): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  476): |CAC| 	ssid           =NG700
V/QCNEA   (  476): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  476): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  476): |CAC| *********************************************
D/QCNEA   (  476): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  476): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  476): |CAC| dispatchNetCfg: updating:0xb8f468dc
,D/QCNEA   (  476): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  476): Reading a NULL string not supported here.
,E/Parcel  (  476): Reading a NULL string not supported here.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4735 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  271): RouteController
D/HyLog   ( 4735): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4735): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4735): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  271): RouteController
V/        (  271): RouteController
V/        (  271): RouteController
,I/PCSuite ( 4735): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
D/PCSuite ( 4735): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4735): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  271): RouteController
W/NetworkManagementService(  962): route cmd failed: 
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
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x628bd2d8 clazz=0x6d700001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1557): Read error: ssl=0x639f0690: I/O error during system call, Connection timed out
I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4771 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
,I/ActivityManager(  962): Killing 4155:com.google.android.talk/u0a77 (adj 15): empty #17
V/NativeCrypto( 1557): SSL shutdown failed: ssl=0x639f0690: I/O error during system call, Broken pipe
,D/HyLog   ( 4771): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4771): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4771): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/QRemote ( 4771): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4771): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4771): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4771): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4771): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4771): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4771): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4771): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 2137:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  962): StoppedState
,I/GAV2    ( 4602): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1557): onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Choreographer( 4675): Skipped 165 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4675): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@428b4030
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3031): start selecting data
,D/SIMObserver( 3031): simInfo1
,D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2026): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2026): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2026): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2026): nl80211: Survey data missing
D/wpa_supplicant( 2026): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Add new id 7 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2026): wlan0: New scan results available
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2026): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2026): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2026): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2026): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2026): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2026): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2026): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2026): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): WPS: AP[4] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2026): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2026): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2026): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2026): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2026): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2026): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb79e55a8  current_ssid=0x0
D/wpa_supplicant( 2026): scard is not null,..
D/wpa_supplicant( 2026): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2026): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2026): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2026): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2026): RSN: PMKSA cache search - network_ctx=0xb79e55a8 try_opportunistic=0
D/wpa_supplicant( 2026): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RSN: No PMKSA cache entry found,
,D/wpa_supplicant( 2026): wlan0: RSN: using IEEE 802.11i/D9.0,
,D/wpa_supplicant( 2026): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2026): wlan0: WPA: clearing AP WPA IE,
,D/wpa_supplicant( 2026): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2026): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2026): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2026): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2026): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2026): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2026): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2026): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0),
D/wpa_supplicant( 2026): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2026): nl80211: Unsubscribe mgmt frames handle 0xb79e4590 (mode change)
D/wpa_supplicant( 2026): nl80211: Subscribe to mgmt frames with non-AP handle 0xb79e4590
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0a
,D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590,
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590
,D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590,
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590,
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2026): nl80211: Register frame type=0xd0 nl_handle=0xb79e4590
D/wpa_supplicant( 2026): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2026): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2026):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2026):   * freq=2412
,D/wpa_supplicant( 2026):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2026):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026):   * Auth Type 0
D/wpa_supplicant( 2026):   * WPA Versions 0x2
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:97],
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 dc:4a:3e:0f:c2:f1]
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 2026): nl80211: Connect request send successfully
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - EAP fail=0,
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  962): handleMessage: E msg.what=147461,
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState,
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987,
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2026): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2026): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2026): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2026): WPS: Unknown Vendor Extension (Vendor ID 311)
W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE ,
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/wpa_supplicant( 2026): nl80211: Event message available
D/wpa_supplicant( 2026): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2026): nl80211: Connect event
D/wpa_supplicant( 2026): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2026): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2026): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2026): wlan0: Association info event
D/wpa_supplicant( 2026): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2026): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2026): wlan0: freq=2412 MHz
D/wpa_supplicant( 2026): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2026): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2026): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2026): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): scard is not null..
D/wpa_supplicant( 2026): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2026): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2026): TDLS: Remove peers on association
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2026): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2026): EAPOL: enable timer tick
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): wlan0: Cancelling scan request
,D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
,D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity
D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ad 2c 7d b6 c0 80 6a 5d 0f 4f fc 3c 71 24 b4 ...
D/wpa_supplicant( 2026): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): ad 2c 7d b6 c0 80 6a 5d 0f 4f fc 3c 71 24 b4 67 35 29 e0 09 bd 1b 7c 7b 9b 95 5f 62 61 1d 69 c4
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ad 2c 7d b6 c0 80 6a 5d 0f 4f fc 3c 71 24 b4 ...
D/wpa_supplicant( 2026): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2026): Get randomness: len=32 entropy=9
D/wpa_supplicant( 2026): WPA: Renewed SNonce - hexdump(len=32): 92 d6 45 03 fe cb 03 9d 99 26 b6 f3 d7 9d c7 83 79 1b 5a d8 ac f8 3b c3 83 02 f7 bd 7f 00 e0 24
D/wpa_supplicant( 2026): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): WPA: Nonce1 - hexdump(len=32): 92 d6 45 03 fe cb 03 9d 99 26 b6 f3 d7 9d c7 83 79 1b 5a d8 ac f8 3b c3 83 02 f7 bd 7f 00 e0 24
D/wpa_supplicant( 2026): WPA: Nonce2 - hexdump(len=32): ad 2c 7d b6 c0 80 6a 5d 0f 4f fc 3c 71 24 b4 67 35 29 e0 09 bd 1b 7c 7b 9b 95 5f 62 61 1d 69 c4
D/wpa_supplicant( 2026): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2026): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): 9d 94 4c 06 11 55 68 9a 2a 38 a8 db 1c 0b e3 47
,D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 92 d6 45 03 fe cb 03 9d 99 26 b6 f3 d7 9d c7 ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/wpa_supplicant( 2026): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ad 2c 7d b6 c0 80 6a 5d 0f 4f fc 3c 71 24 b4 ...
D/wpa_supplicant( 2026): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2026): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2026): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2026): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2026):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2026):   key_nonce - hexdump(len=32): ad 2c 7d b6 c0 80 6a 5d 0f 4f fc 3c 71 24 b4 67 35 29 e0 09 bd 1b 7c 7b 9b 95 5f 62 61 1d 69 c4
D/wpa_supplicant( 2026):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_rsc - hexdump(len=8): 04 06 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2026):   key_mic - hexdump(len=16): bb 24 fc 01 8d d7 21 2b a9 c1 25 c4 a0 4c 39 06
D/wpa_supplicant( 2026): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ad 2c 7d b6 c0 80 6a 5d 0f 4f fc 3c 71 24 b4 ...
D/wpa_supplicant( 2026): RSN: encrypted key data - hexdump(len=56): 65 c2 94 36 38 c0 8d fb 17 85 54 40 b9 a4 17 09 c2 43 bf 87 c2 2f bc c8 8c d9 0b 01 2c 67 5f 23 ...
D/wpa_supplicant( 2026): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2026): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2026): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 8d 6d ...
D/wpa_supplicant( 2026): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2026): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2026): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): WPA: Derived Key MIC - hexdump(len=16): 51 80 47 d5 04 6d e6 9c c0 f7 f6 0f ec 09 bf 3d
,D/wpa_supplicant( 2026): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2026): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb79e4c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2026):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2026): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2026): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
,D/wpa_supplicant( 2026): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2026): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2026): WPA: RSC - hexdump(len=6): 04 06 00 00 00 00,
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ec803a key_idx=1 set_tx=0 seq_len=6 key_len=16,
D/wpa_supplicant( 2026):    broadcast key
I/wpa_supplicant( 2026): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2026): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2026): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2026): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2026): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2026): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2026): wpa_supplicant_set_state, isWPS : 0
,D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): EAPOL: External notification - portValid=1,
D/wpa_supplicant( 2026): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2026): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2026): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 2026): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 2026): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2026): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2026): EAPOL authentication completed successfully
D/wpa_supplicant( 2026): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2026): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2026): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): Network connection established
,D/WifiNative-wlan0(  962): doString: STATUS
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2026): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@42c38400 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@43155b10 target=com.android.internal.util.StateMachine$SmHandler }
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/DhcpStateMachine(  962): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,I/ActivityManager(  962): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4817 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-6ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/HyLog   ( 4817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4817): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4817): DownloadService onCreate
,D/EAS     ( 4585): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4585): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4817): in removeSpuriousFiles
,D/eas_req ( 4585): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4817): DownloadService onStartCommand
,I/LgeMiscReceiver( 4306): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4306): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4306): networkInfo.isConnected() = false
,V/DownloadManager( 4817): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428ddf80 on behalf of 4817
,V/DownloadManager( 4817): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4817): in trimDatabase
,V/DownloadManager( 4817): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428e0188 on behalf of 4817
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428e1058 on behalf of 4817
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
,D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
D/WifiP2pService(  962): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43216f18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43216f18 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring up wlan0
,D/WifiStateMachine(  962): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131212
,D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
V/DownloadManager( 4817): DownloadService onDestroy
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
,D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4841 uid=10052 gids={50052, 3003}
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2026): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2026): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2026): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
W/linker  ( 4585): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): DHCP successful
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
,D/WifiStateMachine(  962): VerifyingLinkState enter
,D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
,E/Parcel  (  476): Reading a NULL string not supported here.
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
,D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/HyLog   ( 4841): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4841): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/WifiStateMachine(  962): handleMessage: X
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/HyLog   ( 4841): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/HtmlEditor( 4585): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4585): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4585): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4585): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4585): register_HtmlEditor, Success
D/HtmlEditor( 4585): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4585): register_HtmlEditorTimer, Success
D/HtmlEditor( 4585): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4585): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4585): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4585): register_HtmlEditorFont, Success
D/HtmlEditor( 4585): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4585): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4585): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  476): Reading a NULL string not supported here.
,E/Parcel  (  476): Reading a NULL string not supported here.
,E/Parcel  (  476): Reading a NULL string not supported here.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
D/HtmlEditor( 4585): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4585): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4585): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4585): JNI_OnLoad Success
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/HubEmail( 4585): JNI_OnLoad()
I/HubEmail( 4585): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4585): registerNatives()
I/HubEmail( 4585): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4585): registerNativeMethods()
,I/HubEmail( 4585): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
W/Settings( 4585): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/        (  271): RouteController
I/ActivityManager(  962): Killing 3922:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/        (  271): RouteController
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  271): RouteController
,V/LGRssiData( 4841): [loadRssi] File not exist 
V/LGRssiData( 4841): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4841): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
W/BaseRuntimeLoader( 4841): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4841): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4841): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4841): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4841): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4841): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4841): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  271): RouteController
,V/        (  271): RouteController
D/MobileConnectivityChangeReceiver( 4841): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/        (  271): RouteController
,D/MobileConnectivityChangeReceiver( 4841): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4841): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4841): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
,V/        (  271): RouteController
I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4869 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  962): Killing 4350:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/        (  271): RouteController
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
I/CheckinService( 1973): Checking schedule, now: 1452860470922 next: 1452860413933
I/CheckinService( 1973): active receiver: enabled
D/QCNEA   (  476): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  476): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  476): |CAC| updateNetCfgInfo
V/QCNEA   (  476): |CAC| *********************************************
V/QCNEA   (  476): |CAC|                   Netconfig               
V/QCNEA   (  476): |CAC| *********************************************
V/QCNEA   (  476): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  476): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  476): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  476): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  476): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  476): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  476): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  476): |CAC| *********************************************
D/QCNEA   (  476): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  476): |CAC| net type = 1
V/QCNEA   (  476): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  476): |CAC| Received ssid= NG700
V/QCNEA   (  476): |CAC| 	ssid           =NG700
V/QCNEA   (  476): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  476): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  476): |CAC| *********************************************
D/QCNEA   (  476): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  476): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  476): |CAC| dispatchNetCfg: updating:0xb8f468dc
D/QCNEA   (  476): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/HyLog   ( 4869): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4869): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4869): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1973): Preparing to send checkin request
,I/EventLogService( 1973): Accumulating logs since 1452860381457
,I/CheckinRequestBuilder( 1973): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1973): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4890 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  962): Killing 4509:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/HyLog   ( 4890): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4890): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4890): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2920): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  962): Killing 4543:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/LGDMClient( 2920): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2920): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4910 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,E/LGDMClient( 2920): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2920): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2920): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2920): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/HyLog   ( 4910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4910): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/HyLog   ( 4910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4910): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4926 uid=10101 gids={50101, 1028, 1015, 3003}
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4926): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): Killing 4571:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4926): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4926): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4926): intf.getDisplayName() = lo
I/Wireless_Storage( 4926): intf.getDisplayName() = sit0
I/Wireless_Storage( 4926): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4926): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4926): intf.getDisplayName() = wlan0
D/NFS     ( 4926): interface name:wlan0 name:wlan0
D/NFS     ( 4926): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4926): interface name:wlan0 name:wlan0
D/NFS     ( 4926): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4926): CONNECT : WIFI_CONNECT
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4939 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 4203:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4939): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1557): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1557): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1557): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1557): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1557): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1557): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 4939): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/CheckinRequestBuilder( 1973): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x432bf618: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4956 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4956): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4956): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4956): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4956): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4956): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4956): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4956): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4956): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4956): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4956): install
,I/MultiDex( 4956): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4956): loading existing secondary dex files
,I/MultiDex( 4956): load found 3 secondary dex files
,I/MultiDex( 4956): install done
,D/dalvikvm( 4956): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4956): VFY: unable to resolve instance field 61
,D/dalvikvm( 4956): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4956): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4956): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4956): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4956): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4956): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4956): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4956): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4956): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4956): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a7748
,D/dalvikvm( 4956): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a7748
,D/dalvikvm( 4956): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a7748, skipping init
D/dalvikvm( 4956): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a7748
,D/dalvikvm( 4956): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a7748
,V/JNIHelp ( 4956): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4956): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428a7748
,D/dalvikvm( 4956): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428a7748
D/dalvikvm( 4956): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428a7748
,D/dalvikvm( 4956): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428a7748
,I/ProviderInstaller( 4956): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm(  962): GC_EXPLICIT freed 2086K, 51% free 29690K/59736K, paused 3ms+6ms, total 87ms
,V/WebViewChromium( 4939): Binding Chromium to the main looper Looper (main, tid 1) {428a0590}
,I/chromium( 4939): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4939): Initializing chromium process, renderers=0
,I/dalvikvm( 4956): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4956): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4956): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4956): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4956): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4956): VFY: replacing opcode 0x6e at 0x0201
,W/chromium( 4939): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4939): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4939): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4939): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4939): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4939): Remote Branch: 
I/Adreno-EGL( 4939): Local Patches: 
I/Adreno-EGL( 4939): Reconstruct Branch: 
,I/NSApplication( 4939): Starting up...
,I/ActivityManager(  962): Killing 4219:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb203b000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb203b000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4771): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/QRemote ( 4771): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,I/QRemote ( 4771): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4735): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4735): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/QRemote ( 4771): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4771): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4771): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1557): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=3242596953
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/AuthorizationBluetoothService( 1557): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1557): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1973): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WearableService( 1883): callingUid 10006, callindPid: 1883
,D/LocationInitializer( 1973): Restart initialization of location
,E/MDM     ( 1425): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/dalvikvm( 4956): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5c220
D/dalvikvm( 4956): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5c220
,D/dalvikvm( 4956): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a5c220, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/wpa_supplicant( 2026): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2026): EAPOL: disable timer tick
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  277): CdmEngine::OpenSession
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
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=1845823766
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,W/Settings( 4956): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4956): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/dalvikvm( 4999): DexOpt: load 3ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4956): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4956): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 77ms
,I/Adreno-EGL( 4956): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4956): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4956): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4956): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4956): Remote Branch: 
I/Adreno-EGL( 4956): Local Patches: 
I/Adreno-EGL( 4956): Reconstruct Branch: 
,I/Adreno-EGL( 4956): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4956): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4956): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4956): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4956): Remote Branch: 
I/Adreno-EGL( 4956): Local Patches: 
I/Adreno-EGL( 4956): Reconstruct Branch: 
,I/Adreno-EGL( 4956): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4956): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4956): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4956): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4956): Remote Branch: 
I/Adreno-EGL( 4956): Local Patches: 
I/Adreno-EGL( 4956): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1973): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  962): RunningState
W/ProcessCpuTracker(  962): Skipping unknown process pid 5002
W/ProcessCpuTracker(  962): Skipping unknown process pid 5022
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
,D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1450): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinTask( 1973): Sending checkin request (11497 bytes)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1973): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1973): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1557): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1557): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1557): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1557): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1557): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1557): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x45117718: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1973): awaiting user notification for token
,I/CheckinRequestBuilder( 1973): Classify the device as Phone.
,I/CheckinTask( 1973): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1973): Checking schedule, now: 1452860473155 next: 1453437869149
,I/CheckinService( 1973): active receiver: disabled
,D/GCM     ( 1557): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1557): Connected
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,E/Parcel  (  476): Reading a NULL string not supported here.
,E/Parcel  (  476): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: X
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/GCM     ( 1557): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@428b4030
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3031): start selecting data
,D/SIMObserver( 3031): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4022): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4022): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4022): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4022): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4022): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4585): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4817): DownloadService onCreate
,D/EAS     ( 4585): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4585): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LgeMiscReceiver( 4306): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4306): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4306): networkInfo.isConnected() = false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/MobileConnectivityChangeReceiver( 4841): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4841): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4817): in removeSpuriousFiles
,V/DownloadManager( 4817): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428e7928 on behalf of 4817
,W/Settings( 4585): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4817): in trimDatabase
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4817): DownloadService onStartCommand
V/DownloadManager( 4817): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2920): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4817): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428ea8f8 on behalf of 4817
,D/LGDMSGCM( 4910): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428eafc8 on behalf of 4817
,D/LGDMClient( 2920): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 4926): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4926): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 4817): DownloadService onDestroy
I/LGDMClient( 2920): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2920): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2920): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2920): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2920): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@428b4030
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3031): start selecting data
,D/SIMObserver( 3031): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4817): DownloadService onCreate
,D/EAS     ( 4585): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4585): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4817): in removeSpuriousFiles
,V/DownloadManager( 4817): DownloadService onStartCommand
,V/DownloadManager( 4817): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428f0f38 on behalf of 4817
,V/DownloadManager( 4817): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428f1cc8 on behalf of 4817
,I/DownloadManager( 4817): in trimDatabase
,V/DownloadManager( 4817): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4306): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4306): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4306): networkInfo.isConnected() = true
,D/PhoneState( 4306): setPdpRejectCasuse : false
,W/Settings( 4585): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4841): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4841): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4817): DownloadService onDestroy
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428f37f0 on behalf of 4817
,D/LGDMClient( 2920): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2920): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4910): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2920): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2920): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/NFS     ( 4926): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4926): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2920): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,W/ContextImpl( 4910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2920): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2920): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/ThermalEngine(  293): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4022): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
,D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@428b4030
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3031): start selecting data
,D/SIMObserver( 3031): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4022): begin check event
,I/AppUp4:CustModeStarterReceiver( 4022): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4585): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4817): DownloadService onCreate
,D/EAS     ( 4585): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4306): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4306): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4306): networkInfo.isConnected() = true
,D/PhoneState( 4306): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4841): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4841): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2920): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4910): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 4585): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 4910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/LGDMClient( 2920): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/DownloadManager( 4817): in removeSpuriousFiles
,V/DownloadManager( 4817): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428f7020 on behalf of 4817
,I/DownloadManager( 4817): in trimDatabase
I/LGDMClient( 2920): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 4817): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/NFS     ( 4926): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4926): CONNECT : WIFI_CONNECT
,V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428f89d8 on behalf of 4817
,V/DownloadManager( 4817): DownloadService onStartCommand
,V/DownloadManager( 4817): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LGDMClient( 2920): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2920): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 4817): created cursor android.database.sqlite.SQLiteCursor@428fab88 on behalf of 4817
D/LGDMClient( 2920): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2920): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4817): DownloadService onDestroy
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4939): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  962): Killing 4602:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/Finsky  ( 4236): [399] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4236): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.457321 Y: -0.413528 Z: 9.796844 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457321 .y:-0.413528 .z:9.796844
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.456100 Y: -0.412827 Z: 9.807281 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456100 .y:-0.412827 .z:9.807281
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 4047): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 4047): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  962): Handling package changes for user 0
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5127 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/dalvikvm(  275): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 62ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 42ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
,I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HyLog   ( 5127): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+4ms, total 31ms
D/HyLog   ( 5127): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5127): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,I/Babel   ( 5127): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5127): MmsConfig.loadMmsSettings
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Babel   ( 5127): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5127): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5127): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5127): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5127): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5127): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,V/GmsNetworkLocationProvi( 1425): DISABLE
,W/BaseRuntimeLoader( 5127): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5127): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5127): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5127): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5127): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5127): MmsConfig.loadFromResources
,E/Babel   ( 5127): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5127): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5127): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5127): [loadRssi] File not exist 
V/LGRssiData( 5127): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5127): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5127): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5127): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5127): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 4022): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 4022): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4022): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4022): onReceive
D/AppUp4:CustFacade( 4022): Context : android.app.ReceiverRestrictedContext@428b4030
D/AppUp4:CustFacade( 4022): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4022): isOpenOperator : true
,D/AppUp4:CustFacade( 4022): isPhone : true
,I/LicenseContentProvider( 3031): start selecting data
,D/SIMObserver( 3031): simInfo1
,I/AppUp4:EulaManager( 4022): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4022): begin check event
D/AppUp4:Utils( 4022): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4022): Event For Nothing, skip.
,D/LocationProviderProxy(  962): applying state to connected service
,D/LocationProviderProxy(  962): applying state to connected service
I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5176 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5176): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5176): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5176): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5176): BUILD Country: EU
,I/SystemConfig( 5176): BUILD Operator: OPEN
I/SystemConfig( 5176): systemFeature RCS result false
,D/SystemConfig( 5176): refreshRcsSupport() :false
I/ActivityManager(  962): Killing 4735:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5191 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5191): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5191): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5191): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): Killing 4771:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  962): Killing 4817:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2655): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  962): GC_EXPLICIT freed 2594K, 51% free 29827K/59736K, paused 3ms+9ms, total 109ms
,D/PackageBroadcastService( 1973): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1973): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  962): Delaying start of: ServiceRecord{446699c8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1973): updateResources: need to parse f{com.google.android.gms}
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 1973): GC_CONCURRENT freed 1977K, 22% free 19544K/24832K, paused 4ms+4ms, total 39ms
,I/IcingCorporaProvider( 2655): UpdateCorporaTask done [took 340 ms] updated apps [took 340 ms] 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  962): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5127): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2026): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  962): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  962): [updateScreenState] screen on = false
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  962): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8906 usec
,D/qcom_sensors_hal(  962): hal_acquire_resources
,I/qcom_sensors_hal(  962): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,D/qcom_sensors_hal(  962): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,I/qcom_sensors_hal(  962): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  962): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.446747 Y: -0.415619 Z: 9.811371 ,
D/qcom_sensors_hal(  962): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  962): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446747 .y:-0.415619 .z:9.811371
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  962): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  962): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.458115 Y: -0.395767 Z: 9.798584 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458115 .y:-0.395767 .z:9.798584
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.448608 Y: -0.406372 Z: 9.813019 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448608 .y:-0.406372 .z:9.813019
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Sensors (  431): sns_pwr.c(292):acquiring wakelock
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  962): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  962): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  962): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  962): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  962): proximitySensorChanged  positive = true
I/KnockOnPowerController(  962): current mode = 1  value = 1 1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.455994 Y: -0.400742 Z: 9.805405 
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.457108 Y: -0.411835 Z: 9.782104 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.455994 .y:-0.400742 .z:9.805405
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0,
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.449524 Y: -0.404465 Z: 9.807678 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449524 .y:-0.404465 .z:9.807678
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.454742 Y: -0.403687 Z: 9.810333 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454742 .y:-0.403687 .z:9.810333
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.452286 Y: -0.410065 Z: 9.823090 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452286 .y:-0.410065 .z:9.823090
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  962): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@432102c0)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb7836450
D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  962): **** SHOWN CALLED ****
,I/WindowManager(  962): No lock screen! windowToken=null
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  962): handleScreenStateChanged: true
,D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2026): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  962): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  962): stopMonitoring
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=on
,D/wpa_supplicant( 2026): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131127
D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  962): handleMessage: X,
D/WifiStateMachine(  962): handleMessage: E msg.what=132097
D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  962): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2026): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2026): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  962): handleMessage: X
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
,E/SlideAside( 4047): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
V/SRS_Proc(  277): ParamSet string: screen_state=on
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433e9fe8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1847): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:21:31
,I/SlideAside( 4047): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1847): 2 : This is isUpdating : false
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1847): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:21:31
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1847): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1847): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1847): 2 : shouldTimeTickRegistered : false
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1156): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1156): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  962): Excessive delay in blankDisplay() while turning screen off: 401ms
D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860491701, nextTick: 28332, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.447510 Y: -0.431442 Z: 9.807098 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447510 .y:-0.431442 .z:9.807098
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860491768, nextTick: 28265, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.436172 Y: -0.404510 Z: 9.833313 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.436172 .y:-0.404510 .z:9.833313
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
,D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GsmSST  ( 1450): Emergency Service
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
D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
D/WeatherService( 1847): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:21:31
,D/WeatherService( 1847): 2 : ACTION screen on
,D/WeatherService( 1847): 2 : shouldTimeTickRegistered : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1847): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:21:31
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1142): notifyScreenOffLocked
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.452194 Y: -0.392609 Z: 9.847397 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452194 .y:-0.392609 .z:9.847397
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3}
D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
D/qcom_sensors_hal(  962): hal_acquire_resources
D/qcom_sensors_hal(  962): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  962): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  962): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  962): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
,V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
,D/UsbSettings( 2589): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{43e64e40 u0 com.test.thalitest/.MainActivity t3} (stop complete)
I/LGImmersionVibrator(  962): Vibrator off
V/UsbSettings( 2589): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2589): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2589): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/WifiStateMachine(  962): handleScreenStateChanged: false
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
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
D/wpa_supplicant( 2026): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2026): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
V/SRS_Proc(  277): ParamSet string: screen_state=off
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
D/qdlights( 1156): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 75, B = 75
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1156): clear
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{42cdb898 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
D/KeyguardViewManager( 1142): onScreenTurnedOff()
D/wpa_supplicant( 2026): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): handleMessage: X
E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
D/qdlights( 1156): set_light_notifications: 2,ff004545,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 69, B = 69
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1156): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 63, B = 63
D/WeatherService( 1847): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:21:31
D/WeatherService( 1847): 2 : ACTION screen off
,D/WeatherService( 1847): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:21:31
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
E/Parcel  (  476): Reading a NULL string not supported here.
,E/Parcel  (  476): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1156): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 57, B = 57
,D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
,D/NfcService( 1474): NFC-C OFF
,D/qdlights( 1156): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 51, B = 51
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
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
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  431): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  293): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Netstats( 1973): User is not opted-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1973): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1973): removeStateFiles() called
,D/PerfProfileCollectorService( 1973): User is not opt-in to Usage & Diagnostics.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860509816175315; DSPS: 5276447; Offset: 1452860348791791771
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860520060, nextTick: 59973, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860520061, nextTick: 59972, mDrawingTime: 0
,I/VacuumService( 1557): Vacuum at: now=1452860522112 tag=VacuumService
,I/GoogleURLConnFactory( 1557): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1557): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1557): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1557): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1557): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1557): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1557): GC_CONCURRENT freed 1793K, 28% free 18071K/24832K, paused 3ms+10ms, total 83ms
,D/dalvikvm( 1557): WAIT_FOR_CONCURRENT_GC blocked 11ms
,W/Uploader( 1557): No account for auth token provided
,W/Uploader( 1557): No account for auth token provided
,W/Uploader( 1557):  no longer exists, so no auth token.
,W/Uploader( 1557): No account for auth token provided
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860529817483224; DSPS: 5931850; Offset: 1452860348791787424
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860549818798684; DSPS: 6587253; Offset: 1452860348791790628
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860569819851332; DSPS: 7242647; Offset: 1452860348791805678
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860580039, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860580044, nextTick: 59988, mDrawingTime: 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860589822023357; DSPS: 7898078; Offset: 1452860348791810955
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860609822482047; DSPS: 8553453; Offset: 1452860348791811881
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860629823617977; DSPS: 9208851; Offset: 1452860348791788144
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860640041, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860640054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860649824046928; DSPS: 9864225; Offset: 1452860348791789848
,D/wpa_supplicant( 2026): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2026): wlan0: BSS: Remove id 7 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2026): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 a0:c5:62:7a:49:97]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 dc:4a:3e:0f:c2:f1]
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860669824940774; DSPS: 10519614; Offset: 1452860348791798685
,D/dalvikvm( 2640): GC_CONCURRENT freed 7833K, 33% free 16819K/24832K, paused 2ms+1ms, total 32ms
,D/dalvikvm( 2640): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1557): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1557): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1557): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1557): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1557): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1557): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x43106638: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1557): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1557): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1557): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1557): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1557): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1557): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1557): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1557): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4236): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4236): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4236): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4236): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4236): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4236): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4236): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4236): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4236): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4236): isDataSchedulerEnabled():false
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860689826268996; DSPS: 11175018; Offset: 1452860348791784133
,I/LocationManagerService(  962): remove 430dad18
,D/LocationManagerService(  962): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2640): GC_CONCURRENT freed 1908K, 32% free 16958K/24832K, paused 13ms+2ms, total 38ms
,D/dalvikvm( 2640): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2640): GC_CONCURRENT freed 1474K, 30% free 17532K/24832K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 2640): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2640): GC_FOR_ALLOC freed 1717K, 30% free 17466K/24832K, paused 20ms, total 20ms
,I/Mlt MonitorService( 2640): parseLastkmsg to dump
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860700053, nextTick: 59975, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860700054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860709827581644; DSPS: 11830421; Offset: 1452860348791784525
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860729828449553; DSPS: 12485809; Offset: 1452860348791797942
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860749829316577; DSPS: 13141197; Offset: 1452860348791810474
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860760066, nextTick: 59964, mDrawingTime: 2
D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860760067, nextTick: 59965, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860769830754434; DSPS: 13796605; Offset: 1452860348791783487
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860789831619374; DSPS: 14451993; Offset: 1452860348791793935
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860809832055199; DSPS: 15107367; Offset: 1452860348791802514
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860820040, nextTick: 59988, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860820044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860829833535661; DSPS: 15762776; Offset: 1452860348791787615
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860849833955081; DSPS: 16418149; Offset: 1452860348791810306
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860869834839760; DSPS: 17073538; Offset: 1452860348791809975
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860880037, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860880055, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860889835964023; DSPS: 17728935; Offset: 1452860348791805088
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860909837274381; DSPS: 18384338; Offset: 1452860348791803190
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860929838129685; DSPS: 19039726; Offset: 1452860348791804002
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860940037, nextTick: 59965, mDrawingTime: 13
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452860940056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860949839452385; DSPS: 19695130; Offset: 1452860348791783928
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860969841119410; DSPS: 20350544; Offset: 1452860348791803004
,I/ActivityManager(  962): Killing 4585:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43366c10 stackId=1, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452860989842474767; DSPS: 21005949; Offset: 1452860348791785070
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861000020, nextTick: 60002, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861000056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861009842912155; DSPS: 21661323; Offset: 1452860348791795212
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861029843816470; DSPS: 22316713; Offset: 1452860348791784000
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861049844706150; DSPS: 22972102; Offset: 1452860348791788670
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861060042, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861060054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861069846175257; DSPS: 23627510; Offset: 1452860348791792933
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861089847256708; DSPS: 24282905; Offset: 1452860348791806269
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861109847726544; DSPS: 24938281; Offset: 1452860348791787824
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861120043, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861120055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861129848627630; DSPS: 25593670; Offset: 1452860348791803900
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861149849518091; DSPS: 26249060; Offset: 1452860348791778834
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861169850417979; DSPS: 26904449; Offset: 1452860348791793712
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861180036, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861180054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861189851896670; DSPS: 27559857; Offset: 1452860348791807559
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,I/EventLogService( 1973): Aggregate from 1452860470954 (log), 1452858972000 (data)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1156): GC_CONCURRENT freed 2878K, 11% free 25450K/28504K, paused 18ms+2ms, total 99ms
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861209852325360; DSPS: 28215231; Offset: 1452860348791809003
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861229857296238; DSPS: 28870754; Offset: 1452860348791805516
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861240023, nextTick: 59998, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861240057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861249858190032; DSPS: 29526144; Offset: 1452860348791783782
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861269858614659; DSPS: 30181517; Offset: 1452860348791811681
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861289862320226; DSPS: 30836999; Offset: 1452860348791794103
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861300045, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861300048, nextTick: 59984, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861309863221051; DSPS: 31492388; Offset: 1452860348791809919
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861329864349012; DSPS: 32147785; Offset: 1452860348791808729
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861349864872598; DSPS: 32803163; Offset: 1452860348791782999
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861360036, nextTick: 59969, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861360054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861369867585507; DSPS: 33458612; Offset: 1452860348791779843
,D/GCM     ( 1557): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861389868726905; DSPS: 34114009; Offset: 1452860348791792091
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861409869171117; DSPS: 34769383; Offset: 1452860348791809057
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861420036, nextTick: 59983, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861420053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861429869612411; DSPS: 35424758; Offset: 1452860348791792587
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861449870587560; DSPS: 36080150; Offset: 1452860348791791174
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861469872084584; DSPS: 36735559; Offset: 1452860348791792836
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861480025, nextTick: 59994, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861480060, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861489872951399; DSPS: 37390947; Offset: 1452860348791805159
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861509874218996; DSPS: 38046349; Offset: 1452860348791791018
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861529875845811; DSPS: 38701762; Offset: 1452860348791800401
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861540040, nextTick: 59972, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861540053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861549876275802; DSPS: 39357136; Offset: 1452860348791803146
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861569877131160; DSPS: 40012524; Offset: 1452860348791804012
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861589885036934; DSPS: 40668143; Offset: 1452860348791805733
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861600042, nextTick: 59969, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861600054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861609885463489; DSPS: 41323517; Offset: 1452860348791805042
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861629886321606; DSPS: 41978905; Offset: 1452860348791808667
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861649889206649; DSPS: 42634360; Offset: 1452860348791794540
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861660028, nextTick: 60000, mDrawingTime: 5
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861660055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861669890160236; DSPS: 43289751; Offset: 1452860348791802082
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861689892340698; DSPS: 43945183; Offset: 1452860348791785279
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861709892775273; DSPS: 44600557; Offset: 1452860348791792607
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861720037, nextTick: 59983, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861720045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861729893741827; DSPS: 45255949; Offset: 1452860348791782599
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861749894172185; DSPS: 45911323; Offset: 1452860348791785711
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861769895052074; DSPS: 46566712; Offset: 1452860348791780590
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861780045, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861780054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861789895477170; DSPS: 47222085; Offset: 1452860348791808958
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861809896828464; DSPS: 47877490; Offset: 1452860348791786961
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861829897697727; DSPS: 48532878; Offset: 1452860348791801731
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861840042, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861840054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861849898579126; DSPS: 49188267; Offset: 1452860348791798121
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861869899503806; DSPS: 49843657; Offset: 1452860348791807273
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861889900464059; DSPS: 50499049; Offset: 1452860348791790964
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861900046, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861900054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861909902380614; DSPS: 51154472; Offset: 1452860348791784911
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861929907872481; DSPS: 51810012; Offset: 1452860348791783614
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861949914119400; DSPS: 52465576; Offset: 1452860348791804947
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861960043, nextTick: 59976, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452861960055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861969914994705; DSPS: 53120965; Offset: 1452860348791795243
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452861989915423917; DSPS: 53776339; Offset: 1452860348791797209
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862009923075576; DSPS: 54431950; Offset: 1452860348791788955
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862020039, nextTick: 59956, mDrawingTime: 15
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862020080, nextTick: 59952, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862029923958171; DSPS: 55087339; Offset: 1452860348791786541
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862049924828425; DSPS: 55742727; Offset: 1452860348791802302
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862069925276594; DSPS: 56398102; Offset: 1452860348791792708
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862080018, nextTick: 60006, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862080044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862089930012576; DSPS: 57053617; Offset: 1452860348791798465
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862109931915330; DSPS: 57709039; Offset: 1452860348791809129
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862129932348759; DSPS: 58364414; Offset: 1452860348791784795
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862140035, nextTick: 59984, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862140054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862149932811200; DSPS: 59019789; Offset: 1452860348791789472
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862169934471660; DSPS: 59675203; Offset: 1452860348791801983
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862189934903684; DSPS: 60330577; Offset: 1452860348791806761
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862200078, nextTick: 59950, mDrawingTime: 4
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862200079, nextTick: 59953, mDrawingTime: 0
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
I/ProcessStatsService(  962): Prepared write state in 54ms
,I/ProcessStatsService(  962): Pruning old procstats: /data/system/procstats/state-2016-01-14-16-26-00.bin
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862209935347531; DSPS: 60985952; Offset: 1452860348791792844
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862229938233148; DSPS: 61641407; Offset: 1452860348791779291
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862249939108087; DSPS: 62296795; Offset: 1452860348791799738
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862260066, nextTick: 59964, mDrawingTime: 2
D/Clock   ( 1142): Clock updated, drawingStartTime : 1452862260067, nextTick: 59966, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862269939535841; DSPS: 62952169; Offset: 1452860348791800246
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  962): GC_CONCURRENT freed 3192K, 50% free 29906K/59736K, paused 5ms+14ms, total 195ms
,I/GLSUser ( 1557): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1557): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1557): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1557): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1557): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1557): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1557): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,TIME-OUT KILL (timeout was 1800000ms)
```
