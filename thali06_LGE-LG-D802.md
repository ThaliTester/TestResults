#### Test 50650278ec2c976_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1967): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1967): launchTask
W/dalvikvm( 1967): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1967): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1967): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UX7mBEVuX9773Ri_o9bpkEfU59qknI3QikhWCVprECdZ6InBMAWAAavCdJ8ehYzVSjUE8b2loFTr8shZN-AH7RVjoLP9MCFzr4sJj1v19NnbGx2KaT5UoGHb4imG6MY3DFrVhH1DkJuGFrt4BuKOZPDKuF3vmbg-7z-0q-_3BJxYx6D9mC0GK5KQEy-SUF8ikTk4Wz
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1967): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1967): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1967): No vision deps
I/GoogleURLConnFactory( 1967): Using platform SSLCertificateSocketFactory
I/PeopleContactsSync( 1967): CP2 sync disabled
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
I/dalvikvm( 1967): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1967): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1967): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/GAV2    ( 4649): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
--------- beginning of /dev/log/system
I/ActivityManager(  960): Killing 4129:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1967): GC_CONCURRENT freed 1541K, 22% free 19435K/24832K, paused 3ms+4ms, total 34ms
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1967): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1967): fetch service done; releasing wakelock
I/ConfigFetchService( 1967): stopping self
I/Icing   ( 1967): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1967): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1967): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.443985 Y: -0.383255 Z: 9.782333 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443985 .y:-0.383255 .z:9.782333
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.454498 Y: -0.403412 Z: 9.777481 
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.446716 Y: -0.394531 Z: 9.759720 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.454498 .y:-0.403412 .z:9.777481
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4708): 
D/AndroidRuntime( 4708): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4708): CheckJNI is OFF
D/dalvikvm( 4708): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4708): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4708): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4708): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4708): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4708): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4708): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4708): failed to load memtrack module: -2
D/AndroidRuntime( 4708): Calling main entry com.android.commands.am.Am
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4708
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (141 us)
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  960): resumeTopActivityLocked: Pausing null
V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  960): startService SlideAside
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  960): setFocusedStack: mFocusedStack=ActivityStack{43701348 stackId=1, 2 tasks}
D/AndroidRuntime( 4708): Shutting down VM
D/UsbSettingsControl( 2592): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2592): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 4071): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Restarting ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4708): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4725 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4725): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4725): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4725): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 25ms
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
I/SlideAside( 4071): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4071): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/WebViewChromium( 4725): Binding Chromium to the background looper Looper (main, tid 1) {42dedee8}
I/chromium( 4725): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4725): Initializing chromium process, renderers=0
I/Adreno-EGL( 4725): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4725): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4725): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4725): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4725): Remote Branch: 
I/Adreno-EGL( 4725): Local Patches: 
I/Adreno-EGL( 4725): Reconstruct Branch: 
W/chromium( 4725): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/dalvikvm( 4725): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4725): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4725): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4725): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4725): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4725): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4725): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4725): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4725): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4725): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4725): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4725): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4725): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4725): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4725): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4725): Enabling debug mode 0
W/AwContents( 4725): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  960): IME STATUS OFF
W/AwContents( 4725): nativeOnDraw failed; clearing to background color.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +376ms
I/ActivityManager( 4725): Timeline: Activity_idle id: android.os.BinderProxy@42def9b8 time:113851
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/JsMessageQueue( 4725): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4725): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42df3888
D/dalvikvm( 4725): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42df3888
D/jxcore_app_log( 4725): JniHelper::setJavaVM(0x41d9a808), pthread_self() = 1630837840
D/JX-Cordova( 4725): jxcore cordova android initializing
I/dalvikvm( 4725): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4725): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4725): VFY: replacing opcode 0x6e at 0x0045
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3} time:114256
D/ActivityManager(  960): no-history finish of ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  960): Finishing activity token=Token{42e05550 ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2592): [AUTORUN] onStop()
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
D/dalvikvm( 4725): GC_CONCURRENT freed 2808K, 13% free 21834K/24832K, paused 2ms+1ms, total 48ms
D/dalvikvm( 4725): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 4725): GC_FOR_ALLOC freed 89K, 12% free 21859K/24832K, paused 23ms, total 23ms
I/dalvikvm-heap( 4725): Grow heap (frag case) to 23.581MB for 64402-byte allocation
D/dalvikvm( 4725): GC_FOR_ALLOC freed 153K, 13% free 21857K/24896K, paused 22ms, total 22ms
I/dalvikvm-heap( 4725): Grow heap (frag case) to 23.610MB for 96598-byte allocation
D/dalvikvm( 4725): GC_FOR_ALLOC freed 185K, 13% free 21889K/24992K, paused 22ms, total 22ms
I/dalvikvm-heap( 4725): Grow heap (frag case) to 23.688MB for 144892-byte allocation
D/dalvikvm( 4725): GC_FOR_ALLOC freed 256K, 13% free 21937K/25136K, paused 23ms, total 23ms
I/dalvikvm-heap( 4725): Grow heap (frag case) to 23.803MB for 217334-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/dalvikvm( 4725): GC_FOR_ALLOC freed 369K, 14% free 22010K/25352K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 23.978MB for 325996-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 570K, 14% free 22132K/25672K, paused 22ms, total 23ms
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 868K, 14% free 22309K/25672K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 24.659MB for 733480-byte allocation
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 1289K, 15% free 22567K/26392K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 25.261MB for 1100216-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
D/dalvikvm( 4725): GC_CONCURRENT freed 1853K, 17% free 23017K/27468K, paused 1ms+4ms, total 47ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 152K, 17% free 22945K/27468K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 26.154MB for 1650320-byte allocation
,D/dalvikvm( 4725): GC_CONCURRENT freed 1692K, 20% free 23461K/29080K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 1413K, 20% free 23551K/29080K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 27.533MB for 2475476-byte allocation
,D/dalvikvm( 4725): GC_CONCURRENT freed 295K, 18% free 25855K/31500K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4725): GC_FOR_ALLOC freed 4337K, 23% free 24521K/31500K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4725): Grow heap (frag case) to 29.661MB for 3713210-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/dalvikvm( 4725): GC_CONCURRENT freed 246K, 21% free 28066K/35128K, paused 2ms+4ms, total 35ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/jxcore-log( 4725): Initializing JXcore engine
,W/jxcore-log( 4725): JXcore engine is ready
,W/jxcore-log( 4725): Starting JXcore engine
,W/jxcore-log( 4725): Platform android
W/jxcore-log( 4725): 
,W/jxcore-log( 4725): Process ARCH arm
W/jxcore-log( 4725): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 4725): GC_CONCURRENT freed 6273K, 28% free 25534K/35128K, paused 2ms+3ms, total 42ms
,I/jxcore-log( 4725): JXcore Cordova bridge is ready!
I/jxcore-log( 4725): 
,W/jxcore-log( 4725): JXcore engine is started
,I/chromium( 4725): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4725): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4725): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/GAV2    ( 4649): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,I/ConfigService( 1546): onDestroy
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,I/jxcore-log( 4725): Toggling radios to true
I/jxcore-log( 4725): 
,D/BluetoothManagerService(  960): Message: 20
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44c262d8:true
,D/BluetoothAdapter( 4725): enable(): BT is already enabled..!
,D/WifiStateMachine(  960): handleMessage: E msg.what=131145
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doBoolean: DISCONNECT
,I/jxcore-log( 4725): Radios toggled
I/jxcore-log( 4725): 
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  960): New client listening to asynchronous messages
D/WifiService(  960): setWifiEnabled: true pid=4725, uid=10304
E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  960): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  960): disconnect pid=4725, uid=10304
,D/WifiService(  960): reconnect pid=4725, uid=10304
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2022): TDLS: Tear down peers
D/wpa_supplicant( 2022): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4725): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4725): 
I/jxcore-log( 4725): Perf Test app loaded loaded
I/jxcore-log( 4725): 
I/Choreographer( 4725): Skipped 69 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2022): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 2022): wlan0: Deauthentication notification
D/wpa_supplicant( 2022): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2022): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2022): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2022): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2022): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2022): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7bf5d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2022): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiNative-wlan0(  960):    returned true
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2022): nl80211: Ignore disconnect event triggered during reassociation
D/WifiStateMachine(  960): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: ConnectedState
W/Settings(  960): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  960): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  960): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131146
,D/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiNative-wlan0(  960): doBoolean: RECONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2022): Fast associate: Old scan results
D/wpa_supplicant( 2022): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2022): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2022): wlan0: nl80211: scan request
D/wpa_supplicant( 2022): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2022): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2022): wlan0: nl80211: Scan trigger
I/jxcore-log( 4725): check test folder
I/jxcore-log( 4725): 
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147460
D/WifiStateMachine(  960): processMsg: DisconnectingState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): Network connection lost
D/WifiStateMachine(  960): Stopping DHCP and clearing IP
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  960): doBoolean: SET ps 1
I/jxcore-log( 4725): found test : ./testFindPeers.js
I/jxcore-log( 4725): 
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
,D/DhcpStateMachine(  960): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiP2pService(  960): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  960): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  960): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiHS20(  960): hidePasspointNotification off =false
,D/QcConnectivityService(  960): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
D/QCNEA   (  408): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  408): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  408): |CAC| updateNetCfgInfo
V/QCNEA   (  408): |CAC| *********************************************
V/QCNEA   (  408): |CAC|                   Netconfig               
V/QCNEA   (  408): |CAC| *********************************************
V/QCNEA   (  408): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  408): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  408): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  408): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  408): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  408): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  408): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  408): |CAC| *********************************************
D/QCNEA   (  408): |CAC| Received bssid= 
D/QCNEA   (  408): |CAC| net type = 3
V/QCNEA   (  408): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  408): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  408): |CAC| 	ssid           =NG700
V/QCNEA   (  408): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  408): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  408): |CAC| *********************************************
D/QCNEA   (  408): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  408): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  408): |CAC| dispatchNetCfg: updating:0xb8a1a8dc
D/QCNEA   (  408): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  960): Attempting to switch to mobile
D/QcConnectivityService(  960): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=1 connState=2
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/,WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131213
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): handleMessage: X
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
I/jxcore-log( 4725): found test : ./testSendData.js
I/jxcore-log( 4725): 
D/NetworkManagementService(  960): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4794 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
W/NetworkManagementService(  960): route cmd failed: 
W/NetworkManagementService(  960): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  960): '
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  960): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  960): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  960): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  960): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  960): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  960): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  960): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  960): android_net_utils_resetConnections in env=0x5c7f2690 clazz=0x6b900001 iface=wlan0 mask=0x3
D/QcConnectivityService(  960): resetConnections(wlan0, 3)
,D/HyLog   ( 4794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4794): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/NativeCrypto( 1546): Read error: ssl=0x60e45c38: I/O error during system call, Connection timed out
,V/NativeCrypto( 1546): SSL shutdown failed: ssl=0x60e45c38: I/O error during system call, Broken pipe
,I/PCSuite ( 4794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4794): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  960): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4831 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/ActivityManager(  960): Killing 4218:com.google.android.talk/u0a77 (adj 15): empty #17
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
I/chromium( 4725): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/HyLog   ( 4831): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4831): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4831): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4831): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4831): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4831): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4831): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4831): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4831): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4831): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4831): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  960): Killing 3134:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  960): StoppedState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  960): battery changed pluggedType: 2
D/HeadsetStateMachine( 1224): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: DisconnectedState
,D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): handleMessage: X
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4083): onReceive
,D/AppUp4:CustFacade( 4083): Context : android.app.ReceiverRestrictedContext@42e01f48
,D/AppUp4:CustFacade( 4083): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4083): isOpenOperator : true
,D/AppUp4:CustFacade( 4083): isPhone : true
,I/LicenseContentProvider( 2968): start selecting data
,D/SIMObserver( 2968): simInfo1
,I/AppUp4:EulaManager( 4083): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4083): begin check event
,I/AppUp4:CustModeStarterReceiver( 4083): Event For GoodConnectivity
,I/ActivityManager(  960): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4860 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4860): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4860): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2022): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2022): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2022): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2022): nl80211: Survey data missing
D/wpa_supplicant( 2022): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 6 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2022): wlan0: New scan results available
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2022): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2022): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2022): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2022): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2022): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2022): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2022): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2022): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2022): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2022): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2022): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7bf75a8  current_ssid=0x0
D/wpa_supplicant( 2022): scard is not null..
D/wpa_supplicant( 2022): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy p,olicy: 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2022): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2022): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2022): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2022): RSN: PMKSA cache search - network_ctx=0xb7bf75a8 try_opportunistic=0
D/wpa_supplicant( 2022): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2022): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2022): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2022): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2022): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2022): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2022): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2022): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2022): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2022): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2022): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2022): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2022): nl80211: Unsubscribe mgmt frames handle 0xb7bf6590 (mode change)
D/wpa_supplicant( 2022): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb7bf6590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2022): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2022):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022):   * freq=2412
D/wpa_supplicant( 2022):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 10:9a:dd:8e:22:d9]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 a0:c5:62:7a:49:97]
D/wpa_supplicant( 2022):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022):   * Auth Type 0
D/wpa_supplicant( 2022):   * WPA Versions 0x2
D/wpa_supplicant( 2022): nl80211: Connect request send successfully
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  960): handleMessage: E msg.what=147461
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  960): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2022): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
W/WifiMonitor(  960): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  960): processMsg: ConnectModeState
,D/WifiStateMachine(  960): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2022): nl80211: Connect event
D/wpa_supplicant( 2022): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2022): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2022): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2022): wlan0: Association info event
D/wpa_supplicant( 2022): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2022): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2022): wlan0: freq=2412 MHz
D/wpa_supplicant( 2022): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2022): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2022): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2022): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): scard is not null..
D/wpa_supplicant( 2022): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2022): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2022): TDLS: Remove peers on association
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2022): EAPOL: enable timer tick
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  960): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2022): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 11 0c e6 2c 76 8a 92 95 34 43 8b af 9d 5f 2d ...
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2022): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2022): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2022): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2022):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2022):   key_nonce - hexdump(len=32): 11 0c e6 2c 76 8a 92 95 34 43 8b af 9d 5f 2d 6f 99 67 71 2a 88 f9 4a cc 0b e3 ef 96 90 e2 26 09
D/wpa_supplicant( 2022):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 11 0c e6 2c 76 8a 92 95 34 43 8b af 9d 5f 2d ...
D/wpa_supplicant( 2022): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2022): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2022): Get randomness: len=32 entropy=9
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/wpa_supplicant( 2022): WPA: Renewed SNonce - hexdump(len=32): ad 45 e6 9a b8 7d c5 ab 69 6d a5 e9 a7 75 7a 09 01 54 53 90 84 e0 c2 be e0 3e 54 32 d8 dc 78 78
D/wpa_supplicant( 2022): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): WPA: Nonce1 - hexdump(len=32): ad 45 e6 9a b8 7d c5 ab 69 6d a5 e9 a7 75 7a 09 01 54 53 90 84 e0 c2 be e0 3e 54 32 d8 dc 78 78
D/wpa_supplicant( 2022): WPA: Nonce2 - hexdump(len=32): 11 0c e6 2c 76 8a 92 95 34 43 8b af 9d 5f 2d 6f 99 67 71 2a 88 f9 4a cc 0b e3 ef 96 90 e2 26 09
D/wpa_supplicant( 2022): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2022): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2022): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2022): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2022): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): WPA: Derived Key MIC - hexdump(len=16): fb 64 ee be 8b d9 73 64 19 37 f3 6c eb c4 7c ae
,D/wpa_supplicant( 2022): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 ad 45 e6 9a b8 7d c5 ab 69 6d a5 e9 a7 75 7a ...
D/wpa_supplicant( 2022): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 11 0c e6 2c 76 8a 92 95 34 43 8b af 9d 5f 2d ...
D/wpa_supplicant( 2022): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2022): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2022): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2022): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2022):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2022):   key_nonce - hexdump(len=32): 11 0c e6 2c 76 8a 92 95 34 43 8b af 9d 5f 2d 6f 99 67 71 2a 88 f9 4a cc 0b e3 ef 96 90 e2 26 09
D/wpa_supplicant( 2022):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_rsc - hexdump(len=8): 65 35 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_mic - hexdump(len=16): 35 2a 33 1a 86 59 2d 90 a7 a2 8c 85 7c 41 c5 65
D/wpa_supplicant( 2022): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 11 0c e6 2c 76 8a 92 95 34 43 8b af 9d 5f 2d ...
D/wpa_supplicant( 2022): RSN: encrypted key data - hexdump(len=56): d4 dc b0 6b 46 6d 53 8c 12 8c ba 79 45 b4 59 bc c3 5e 13 27 f1 3f 60 ad 8c c1 fd 02 e3 6c e4 d5 ...
D/wpa_supplicant( 2022): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2022): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2022): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2022): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 3e 14 ...
D/wpa_supplicant( 2022): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2022): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2022): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): WPA: Derived Key MIC - hexdump(len=16): 40 a0 54 0d ef c4 66 2e 01 2f 82 2a 43 65 39 b0
D/wpa_supplicant( 2022): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2022): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7bf6c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2022):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2022): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2022): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2022): WPA: RSC - hexdump(len=6): 65 35 00 00 00 00
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f1d03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2022):    broadcast key
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
I/wpa_supplicant( 2022): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2022): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2022): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2022): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2022): EAPOL authentication completed successfully
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  960): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  960): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: DisconnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): Network connection established
D/WifiNative-wlan0(  960): doString: STATUS
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2022): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  960):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  960): ssid=NG700
D/WifiNative-wlan0(  960): id=0
D/WifiNative-wlan0(  960): mode=station
D/WifiNative-wlan0(  960): pairwise_cipher=CCMP
D/WifiNative-wlan0(  960): group_cipher=CCMP
D/WifiNative-wlan0(  960): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  960): wpa_state=COMPLETED
D/WifiNative-wlan0(  960): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  960): address=34:fc:ef:de:0a:e2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/WifiServiceExtension(  960): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  960): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  960): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  960): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  960): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  960): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/DhcpStateMachine(  960): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): ObtainingIpState{ when=-10ms what=147462 obj=android.net.wifi.StateChangeResult@45475508 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/DhcpStateMachine(  960): WaitBeforeStartState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147462
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-7ms what=147462 obj=android.net.wifi.StateChangeResult@45476058 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=147459
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-7ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131155
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-1ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196612
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
V/DownloadManager( 4860): DownloadService onCreate
D/EAS     ( 4630): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4630): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4630): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 4860): in removeSpuriousFiles
V/DownloadManager( 4860): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e280b0 on behalf of 4860
I/LgeMiscReceiver( 4374): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4374): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4374): networkInfo.isConnected() = false
V/DownloadManager( 4860): DownloadService onStartCommand
V/DownloadManager( 4860): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4860): in trimDatabase
V/DownloadManager( 4860): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e2bb30 on behalf of 4860
V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e2d410 on behalf of 4860
V/DownloadManager( 4860): DownloadService onDestroy
W/linker  ( 4630): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4630): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4630): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4630): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4630): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4630): register_HtmlEditor, Success
D/HtmlEditor( 4630): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
I/ActivityManager(  960): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4899 uid=10052 gids={50052, 3003}
D/HtmlEditor( 4630): register_HtmlEditorTimer, Success
D/HtmlEditor( 4630): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4630): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4630): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4630): register_HtmlEditorFont, Success
D/HtmlEditor( 4630): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4630): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4630): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4630): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4630): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4630): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4630): JNI_OnLoad Success
D/HyLog   ( 4899): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4899): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4899): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/HubEmail( 4630): JNI_OnLoad()
I/HubEmail( 4630): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4630): registerNatives()
I/HubEmail( 4630): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4630): registerNativeMethods()
I/HubEmail( 4630): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4630): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4899): [loadRssi] File not exist 
,I/ActivityManager(  960): Killing 3923:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
V/LGRssiData( 4899): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4899): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4899): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4899): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4899): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4899): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 4899): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4899): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
,V/TelephonyAutoProfiling( 4899): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4899): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4899): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4899): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4899): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  960): doBoolean: SET ps 0
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  960):    returned true
,D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  960): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  960):    returned null
E/WifiStateMachine(  960): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  960): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  960): DHCP Start wake lock is acquired.
I/ActivityManager(  960): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4913 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  960): Killing 4411:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/WifiP2pService(  960): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4382c9a8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4382c9a8 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  960): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,V/LgDhcpStateMachineHelper(  960): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=131212
D/WifiStateMachine(  960): processMsg: ObtainingIpState
D/WifiStateMachine(  960): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=196613
D/WifiStateMachine(  960): processMsg: ObtainingIpState
,D/WifiStateMachine(  960): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  960): doBoolean: SET ps 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/HyLog   ( 4913): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4913): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4913): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiNative-wlan0(  960):    returned true
D/WifiNative-wlan0(  960): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
D/WifiP2pService(  960): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  960): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  960):    returned true
D/WifiStateMachine(  960): DHCP successful
D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  960): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  960): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState enter
D/WifiStateMachine(  960): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  960): handleMessage: X
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
D/WifiStateMachine(  960): handleMessage: E msg.what=135190
D/WifiStateMachine(  960): processMsg: VerifyingLinkState
D/WifiStateMachine(  960): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
D/WifiStateMachine(  960): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  960): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  960): CaptivePortalCheckState enter
D/WifiStateMachine(  960): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
E/Parcel  (  408): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  960): handleMessage: X
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  960): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  960): 
W/WifiStateTracker(  960):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  960):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  960): handleMessage: E msg.what=131092
D/WifiStateMachine(  960): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  960): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  408): Reading a NULL string not supported here.
,E/Parcel  (  408): Reading a NULL string not supported here.
,E/Parcel  (  408): Reading a NULL string not supported here.
D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/WifiStateMachine(  960): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/QcConnectivityService(  960): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  960): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  960): transitionTo: destState=ConnectedState
D/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  960): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  960): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  960): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
,E/Parcel  (  408): Reading a NULL string not supported here.
E/ActivityThread(  960): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  960): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  960): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4930 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  960): Killing 4549:com.android.defcontainer/u0a4 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 4930): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4930): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4930): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
,V/        (  264): RouteController
,D/LGDMClient( 2860): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  408): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  408): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  408): |CAC| updateNetCfgInfo
V/QCNEA   (  408): |CAC| *********************************************
V/QCNEA   (  408): |CAC|                   Netconfig               
V/QCNEA   (  408): |CAC| *********************************************
V/QCNEA   (  408): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  408): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  408): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  408): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  408): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  408): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  408): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  408): |CAC| *********************************************
D/QCNEA   (  408): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  408): |CAC| net type = 1
V/QCNEA   (  408): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  408): |CAC| Received ssid= NG700
V/QCNEA   (  408): |CAC| 	ssid           =NG700
V/QCNEA   (  408): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  408): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  408): |CAC| *********************************************
D/QCNEA   (  408): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  408): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  408): |CAC| dispatchNetCfg: updating:0xb8a1a8dc
D/QCNEA   (  408): |CAC| readCallback: read len:0, ret:-1, errno:11
I/ActivityManager(  960): Killing 4588:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LGDMClient( 2860): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2860): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  960): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4955 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  960): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  960): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  960): GC_EXPLICIT freed 23635K, 49% free 29644K/57560K, paused 3ms+8ms, total 133ms
,E/LGDMClient( 2860): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2860): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2860): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
,I/LGDMClient( 2860): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinService( 1967): Checking schedule, now: 1450109410633 next: 1450109350179
D/HyLog   ( 4955): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1967): active receiver: enabled
D/HyLog   ( 4955): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4955): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1967): Preparing to send checkin request
,I/EventLogService( 1967): Accumulating logs since 1450109317357
,D/LGDMSGCM( 4955): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  960): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4978 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  960): Killing 4616:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,I/CheckinRequestBuilder( 1967): Checkin reason type: 8 attempt count: 1
D/HyLog   ( 4978): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4978): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4978): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
E/ActivityThread( 1967): Failed to find provider info for com.google.android.wearable.settings
,I/NFS     ( 4978): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4978): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4978): intf.getDisplayName() = lo
I/Wireless_Storage( 4978): intf.getDisplayName() = sit0
I/Wireless_Storage( 4978): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4978): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4978): intf.getDisplayName() = wlan0
D/NFS     ( 4978): interface name:wlan0 name:wlan0
D/NFS     ( 4978): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4978): interface name:wlan0 name:wlan0
D/NFS     ( 4978): addr:192.168.1.140 broadcast:192.168.1.255
,I/Wireless_Storage( 4978): CONNECT : WIFI_CONNECT
,I/ActivityManager(  960): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4990 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  960): Killing 4264:com.android.contacts/u0a21 (adj 15): empty #17
D/dalvikvm( 1546): GC_EXPLICIT freed 1199K, 29% free 17813K/24832K, paused 1ms+3ms, total 27ms
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4990): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4990): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4990): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 4990): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x437b5a58: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1967): awaiting user notification for token
,V/WebViewChromium( 4990): Binding Chromium to the main looper Looper (main, tid 1) {42dec590}
,I/chromium( 4990): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4990): Initializing chromium process, renderers=0
,W/chromium( 4990): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/ActivityManager(  960): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5011 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
I/Adreno-EGL( 4990): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4990): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4990): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4990): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4990): Remote Branch: 
I/Adreno-EGL( 4990): Local Patches: 
I/Adreno-EGL( 4990): Reconstruct Branch: 
,D/HyLog   ( 5011): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5011): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5011): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
W/dalvikvm( 5011): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 5011): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5011): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5011): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5011): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5011): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5011): install
I/NSApplication( 4990): Starting up...
I/MultiDex( 5011): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 5011): loading existing secondary dex files
,I/MultiDex( 5011): load found 3 secondary dex files
,I/MultiDex( 5011): install done
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  960): Killing 4278:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5011): VFY: unable to resolve instance field 61
,D/dalvikvm( 5011): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5011): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5011): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5011): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5011): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5011): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5011): VFY: replacing opcode 0x62 at 0x000a
D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4831): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 5011): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5011): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5011): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42df3740
D/dalvikvm( 5011): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42df3740
,D/dalvikvm( 5011): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42df3740, skipping init
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 5011): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42df3740
D/dalvikvm( 5011): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42df3740
V/JNIHelp ( 5011): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4831): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4831): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/PCSuite ( 4794): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4794): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 4831): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 4831): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4831): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4831): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/dalvikvm( 5011): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42df3740
,D/dalvikvm( 5011): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42df3740
D/dalvikvm( 5011): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42df3740
,D/dalvikvm( 5011): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42df3740
,I/ProviderInstaller( 5011): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1546): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1546): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1546): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1967): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1875): callingUid 10006, callindPid: 1875
,E/MDM     ( 1424): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1967): Restart initialization of location
,I/dalvikvm( 5011): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5011): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5011): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5011): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,W/dalvikvm( 5011): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5011): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2063000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2063000
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
,D/WVCdm   (  270): PrepareKeyRequest: nonce=3172830295
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5011): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42fadb00
D/dalvikvm( 5011): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42fadb00
,D/dalvikvm( 5011): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42fadb00, skipping init
,D/wpa_supplicant( 2022): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2022): EAPOL: disable timer tick
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5011): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  960): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/dalvikvm( 5044): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 5011): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5011): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 74ms
,I/Adreno-EGL( 5011): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5011): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5011): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5011): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5011): Remote Branch: 
I/Adreno-EGL( 5011): Local Patches: 
I/Adreno-EGL( 5011): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 5011): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5011): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5011): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5011): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5011): Remote Branch: 
I/Adreno-EGL( 5011): Local Patches: 
I/Adreno-EGL( 5011): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  960): handleMessage: E msg.what=131212
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
D/WifiStateMachine(  960): processMsg: SupplicantStartedState
,D/WifiStateMachine(  960): processMsg: DefaultState
,D/WifiStateMachine(  960): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  960): send additional Connectivity Action
,D/WifiStateMachine(  960): handleMessage: X
,D/LocSvc_java(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  960): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  960): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  960): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  960): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  960):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  960): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  960): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  960): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  960): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  960): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  960): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  960): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
V/LgDhcpStateMachineHelper(  960): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  960): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  960): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  960): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  960): RunningState
,W/Settings( 5011): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=243297536
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4725): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4725): 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 5011): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5011): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5011): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5011): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5011): Remote Branch: 
I/Adreno-EGL( 5011): Local Patches: 
I/Adreno-EGL( 5011): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1967): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1546): Connected
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1546): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/CheckinTask( 1967): Sending checkin request (11746 bytes)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/CheckinRequestBuilder( 1967): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1967): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,W/CheckinRequestBuilder( 1967): awaiting user notification for token
D/NotificationService(  960): updateLightListLocked :r=NotificationRecord(0x42ee4920: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  960): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1967): Classify the device as Phone.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinTask( 1967): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1967): Checking schedule, now: 1450109412998 next: 1450686808995
,I/CheckinService( 1967): active receiver: disabled
,D/GCM     ( 1546): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  408): Reading a NULL string not supported here.
,E/Parcel  (  408): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4083): onReceive
D/AppUp4:CustFacade( 4083): Context : android.app.ReceiverRestrictedContext@42e01f48
D/AppUp4:CustFacade( 4083): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4083): isOpenOperator : true
,D/AppUp4:CustFacade( 4083): isPhone : true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LicenseContentProvider( 2968): start selecting data
,D/SIMObserver( 2968): simInfo1
,I/AppUp4:EulaManager( 4083): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4083): begin check event
,I/AppUp4:CustModeStarterReceiver( 4083): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4083): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4083): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4083): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4083): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4083): handleAsyncCustNotification do not startCustService
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4860): DownloadService onCreate
,D/EAS     ( 4630): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 4860): in removeSpuriousFiles
V/DownloadManager( 4860): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4630): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e332c8 on behalf of 4860
,D/eas_req ( 4630): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4860): in trimDatabase
V/DownloadManager( 4860): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4860): DownloadService onStartCommand
,V/DownloadManager( 4860): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e369a8 on behalf of 4860
,V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e36620 on behalf of 4860
,V/DownloadManager( 4860): DownloadService onDestroy
I/LgeMiscReceiver( 4374): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4374): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4374): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4899): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4630): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4899): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2860): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2860): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4955): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2860): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4978): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4978): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2860): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2860): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2860): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2860): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4083): onReceive
D/AppUp4:CustFacade( 4083): Context : android.app.ReceiverRestrictedContext@42e01f48
D/AppUp4:CustFacade( 4083): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4083): isOpenOperator : true
,D/AppUp4:CustFacade( 4083): isPhone : true
,I/LicenseContentProvider( 2968): start selecting data
,D/SIMObserver( 2968): simInfo1
,I/AppUp4:EulaManager( 4083): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4083): begin check event
,I/AppUp4:CustModeStarterReceiver( 4083): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4860): DownloadService onCreate
,I/DownloadManager( 4860): in removeSpuriousFiles
,V/DownloadManager( 4860): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4630): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e3b558 on behalf of 4860
,D/EAS     ( 4630): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4860): DownloadService onStartCommand
V/DownloadManager( 4860): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4860): in trimDatabase
,V/DownloadManager( 4860): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  960): GC_EXPLICIT freed 2054K, 49% free 29541K/57560K, paused 3ms+5ms, total 86ms
,V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e3e790 on behalf of 4860
,V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e3e578 on behalf of 4860
I/LgeMiscReceiver( 4374): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4374): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4860): DownloadService onDestroy
,W/Settings( 4630): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4374): networkInfo.isConnected() = true
,D/PhoneState( 4374): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4899): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4899): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2860): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2860): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4955): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2860): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4978): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4978): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2860): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2860): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,W/ContextImpl( 4955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2860): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2860): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  960): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4083): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4083): onReceive
,D/AppUp4:CustFacade( 4083): Context : android.app.ReceiverRestrictedContext@42e01f48
D/AppUp4:CustFacade( 4083): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4083): isOpenOperator : true
,D/AppUp4:CustFacade( 4083): isPhone : true
,I/LicenseContentProvider( 2968): start selecting data
,D/SIMObserver( 2968): simInfo1
,I/AppUp4:EulaManager( 4083): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4083): begin check event
,I/AppUp4:CustModeStarterReceiver( 4083): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4630): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4860): DownloadService onCreate
,D/EAS     ( 4630): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4374): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4374): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4374): networkInfo.isConnected() = true
,D/PhoneState( 4374): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4899): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4899): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2860): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4955): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4978): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4978): CONNECT : WIFI_CONNECT
,W/Settings( 4630): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4860): in removeSpuriousFiles
,V/DownloadManager( 4860): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e42dc0 on behalf of 4860
D/LGDMClient( 2860): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2860): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 4860): in trimDatabase
V/DownloadManager( 4860): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4860): DownloadService onStartCommand
V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e44bf0 on behalf of 4860
V/DownloadManager( 4860): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4860): created cursor android.database.sqlite.SQLiteCursor@42e46960 on behalf of 4860
E/LGDMClient( 2860): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2860): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2860): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/LGDMClient( 2860): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4860): DownloadService onDestroy
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.448502 Y: -0.410507 Z: 9.747101 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448502 .y:-0.410507 .z:9.747101
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.460709 Y: -0.390533 Z: 9.749329 
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.449615 Y: -0.393860 Z: 9.761536 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.460709 .y:-0.390533 .z:9.749329
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  960): battery changed pluggedType: 2
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  960): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1224): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  960): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/WifiServiceExtension(  960): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  960): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4990): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/Finsky  ( 4295): [399] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4295): [1] 5.onFinished: Installation state replication succeeded.
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  408): Reading a NULL string not supported here.
,E/Parcel  (  408): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  960): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  960): Killing 4649:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5209 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SlideAside( 4071): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4071): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+10ms, total 66ms
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 27ms
,D/administrator(  960): Handling package changes for user 0
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
,D/HyLog   ( 5209): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5209): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5209): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "sms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "smsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mms"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  960):   Action: "android.intent.action.SENDTO"
I/PackageManager(  960):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  960):   Scheme: "mmsto"
I/PackageManager(  960): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5209): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5209): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5209): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5209): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/Babel   ( 5209): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5209): MmsConfig.loadFromDatabase
I/MediaCodecList( 5209): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5209): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5209): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5209): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5209): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5209): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5209): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5209): MmsConfig.loadFromResources
,E/Babel   ( 5209): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5209): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5209): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5209): [loadRssi] File not exist 
V/LGRssiData( 5209): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5209): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4:Utils( 4083): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4083): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4083): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling( 5209): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5209): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5209): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4083): onReceive
D/AppUp4:CustFacade( 4083): Context : android.app.ReceiverRestrictedContext@42e01f48
D/AppUp4:CustFacade( 4083): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4083): isOpenOperator : true
,D/AppUp4:CustFacade( 4083): isPhone : true
I/LicenseContentProvider( 2968): start selecting data
,V/GmsNetworkLocationProvi( 1424): DISABLE
,D/SIMObserver( 2968): simInfo1
,I/AppUp4:EulaManager( 4083): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4083): begin check event
D/AppUp4:Utils( 4083): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4083): Event For Nothing, skip.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/ActivityManager(  960): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5260 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 5260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5260): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,I/SystemConfig( 5260): BUILD Country: EU
,I/SystemConfig( 5260): BUILD Operator: OPEN
I/ActivityManager(  960): Killing 4794:com.lge.sync/1000 (adj 15): empty #17
I/ActivityManager(  960): Killing 4831:com.lge.qremote/u0a96 (adj 15): empty #17
,I/SystemConfig( 5260): systemFeature RCS result false
,D/SystemConfig( 5260): refreshRcsSupport() :false
,I/ActivityManager(  960): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5274 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
,D/LocationProviderProxy(  960): applying state to connected service
,D/LocationProviderProxy(  960): applying state to connected service
D/HyLog   ( 5274): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5274): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5274): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2676): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  960): Killing 4860:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 2 tasks}
,D/PackageBroadcastService( 1967): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1967): Null package name or gms related package.  Ignoreing.
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  960): Delaying start of: ServiceRecord{4440b8d0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1967): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1967): GC_CONCURRENT freed 1910K, 22% free 19540K/24832K, paused 4ms+5ms, total 42ms
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/IcingCorporaProvider( 2676): UpdateCorporaTask done [took 262 ms] updated apps [took 262 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/CaptivePortalTracker(  960): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/QcConnectivityService(  960): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  960): Checking http://216.58.209.78/generate_204
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/CaptivePortalTracker(  960): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  960): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  960): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  960): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  960): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,E/Parcel  (  408): Reading a NULL string not supported here.
,E/Parcel  (  408): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV4    ( 5209): Thread[GAThread,5,main]: No campaign data found.
,I/PowerManagerService(  960): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  960): [updateScreenState] screen on = false
D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  960): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  960): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9439 usec
D/KnockOnPowerController(  960): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  960): hal_acquire_resources
,I/qcom_sensors_hal(  960): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  960): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  960): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  960): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  960): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  960): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  960): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  960): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.433960 Y: -0.415909 Z: 9.757263 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.433960 .y:-0.415909 .z:9.757263
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.451721 Y: -0.409927 Z: 9.761520 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451721 .y:-0.409927 .z:9.761520
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,I/Sensors (  366): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  960): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  960): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  960): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  960): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  960): proximitySensorChanged  positive = true
I/KnockOnPowerController(  960): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.461502 Y: -0.442291 Z: 9.769409 
,V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.455948 Y: -0.397888 Z: 9.766083 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.461502 .y:-0.442291 .z:9.769409
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.443787 Y: -0.401016 Z: 9.777115 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443787 .y:-0.401016 .z:9.777115
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.428497 Y: -0.397217 Z: 9.770905 
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.428497 .y:-0.397217 .z:9.770905
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.462387 Y: -0.406769 Z: 9.767792 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462387 .y:-0.406769 .z:9.767792
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  960): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43a15678)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1141): notifyScreenOnLocked
D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  960): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
I/WindowManager(  960): No lock screen! windowToken=null
,V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  960): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  960): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  960): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  960): hal_process_report_ind: X: -0.469284 Y: -0.405441 Z: 9.753723 
D/qcom_sensors_hal(  960): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469284 .y:-0.405441 .z:9.753723
,D/qcom_sensors_hal(  960): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb81f9450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  960): handleScreenStateChanged: true
,D/WifiServiceExtension(  960): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  960): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=131127
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): handleMessage: X
,D/WifiStateMachine(  960): handleMessage: E msg.what=131158
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  960): handleMessage: X
D/WifiStateMachine(  960): handleMessage: E msg.what=132097
D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
D/WifiStateMachine(  960): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  960): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2022): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  960): handleMessage: X
,D/WifiOffDelayIfNotUsed(  960): stopMonitoring
,E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 960
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4396a2f0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1841): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 17:10:27
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/SlideAside( 4071): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/SlideAside( 4071): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/dalvikvm( 1155): GC_CONCURRENT freed 2894K, 11% free 25469K/28544K, paused 2ms+1ms, total 58ms
D/UpdateThreadPoolManager( 1841): 2 : This is isUpdating : false
D/WeatherAncestor( 1841): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 17:10:27
D/WeatherService( 1841): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1841): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1841): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
D/WifiController(  960): battery changed pluggedType: 2
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
D/WifiController(  960): battery changed pluggedType: 2
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  960): Excessive delay in blankDisplay() while turning screen off: 380ms
D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450109427697, nextTick: 32336, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/Clock   ( 1141): Clock updated, drawingStartTime : 1450109427718, nextTick: 32314, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/WeatherService( 1841): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:10:27
,D/WeatherService( 1841): 2 : ACTION screen on
,D/WeatherService( 1841): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1841): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:10:27
D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
,E/Parcel  (  408): Reading a NULL string not supported here.
D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  960): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  960): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
,D/qcom_sensors_hal(  960): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
D/qcom_sensors_hal(  960): hal_acquire_resources
,D/qcom_sensors_hal(  960): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  960): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  960): hal_wait_for_response: timeout=1000
,I/LGImmersionVibrator(  960): Vibrator off
V/qcom_sensors_hal(  960): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  960): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  960): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/WifiStateMachine(  960): handleScreenStateChanged: false
D/WifiStateMachine(  960): handleMessage: E msg.what=131154
,D/WifiStateMachine(  960): processMsg: ConnectedState
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{442b7bd0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/qcom_sensors_hal(  960): hal_smgr_report_delete: Rcvd success response from request
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): handleMessage: X
D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
D/WifiStateMachine(  960): handleMessage: E msg.what=131158
D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
D/WifiStateMachine(  960): processMsg: ConnectModeState
D/WifiStateMachine(  960): processMsg: DriverStartedState
,D/WifiStateMachine(  960): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  960): doBoolean: DRIVER SETSUSPENDMODE 1
E/AudioSystem(  960): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 960
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
,V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,D/UsbSettings( 2592): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/WifiController(  960): CMD_SCREEN_OFF 
D/WifiController(  960): shouldWifiStayAwake TRUE
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1155): clear
V/UsbSettings( 2592): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2592): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2592): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/TelephonyAutoProfiling(  960): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  960):    returned true
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
E/Parcel  (  408): Reading a NULL string not supported here.
,E/Parcel  (  408): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  960): handleMessage: X
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/WeatherService( 1841): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:10:27
D/WeatherService( 1841): 2 : ACTION screen off
D/WeatherService( 1841): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:10:27
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{432086a0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{43701348 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Going to sleep and all paused
V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/NfcService( 1473): NFC-C OFF
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,I/Sensors (  366): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  960): handleMessage: E msg.what=131155
,D/WifiStateMachine(  960): processMsg: ConnectedState
,D/WifiStateMachine(  960): processMsg: L2ConnectedState
,D/WifiStateMachine(  960): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450109435813329643; DSPS: 4950643; Offset: 1450109284731695122
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1546): Vacuum at: now=1450109436778 tag=VacuumService
,I/GoogleURLConnFactory( 1546): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1546): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1546): GC_CONCURRENT freed 1828K, 28% free 18029K/24832K, paused 3ms+7ms, total 59ms
,D/dalvikvm( 1546): WAIT_FOR_CONCURRENT_GC blocked 33ms
,W/Uploader( 1546):  no longer exists, so no auth token.
,W/Uploader( 1546): No account for auth token provided
,W/Uploader( 1546): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450109455816464218; DSPS: 5606105; Offset: 1450109284731716904
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450109460041, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450109460047, nextTick: 59964, mDrawingTime: 7
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450109475818405928; DSPS: 6261529; Offset: 1450109284731705489
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450109495820262848; DSPS: 6916950; Offset: 1450109284731700837
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450109515821765653; DSPS: 7572359; Offset: 1450109284731708280
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450109520026, nextTick: 60001, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450109520045, nextTick: 59963, mDrawingTime: 9
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450109535824257209; DSPS: 8227801; Offset: 1450109284731697395
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450109555826006367; DSPS: 8883218; Offset: 1450109284731707051
,D/qcom_sensors_hal(  960): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  960): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  960): hal_ts_offset_is: Apps: 1450109575827644745; DSPS: 9538632; Offset: 1450109284731697480
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450109580033, nextTick: 59973, mDrawingTime: 12
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1450109580059, nextTick: 59972, mDrawingTime: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  960): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED

```
